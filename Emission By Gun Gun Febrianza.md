# Fuels

The **primary purpose** of burning fuels is to release their stored **chemical energy** and convert it into a usable form of energy (like heat, motion, or electricity) to perform work. The energy content is the fundamental value proposition of a fuel.











1. Project setup and repository skeleton
Create a Git repository containing two root folders: **/backend** and **/frontend**.  
Add `.editorconfig`, `.eslintrc`, and a `README.md` describing tech stack, setup instructions, and coding conventions (ES 2018, no TypeScript, no JS frameworks).  
Prepare an `.env.example` with MySQL connection placeholders.  
Configure `npm init -y` inside **/backend** and add scripts: `dev`, `start`, `seed`, `lint`.  
Add `nodemon`, `dotenv`, `eslint`, and `mysql2` as dev/prod dependencies.
2. Design MySQL database schema
Produce an ER-diagram and DDL covering:  
- `facilities` (id, name, country, scope_flags, …)  
- `emission_factors` (id, source, fuel_type, unit, factor_kgco2e, valid_from, valid_to)  
- `fuel_properties` (id, fuel_type, density, calorific_value, unit)  
- `unit_conversions` (id, from_unit, to_unit, multiplier)  
- `activity_data` (id, facility_id, activity_date, scope, source_type, fuel_type, amount, unit, meta_json)  
- `emissions_calculations` (id, activity_id, calc_timestamp, co2e_kg, methodology, audit_json)  
Add reference / lookup tables when needed (e.g., `countries`).  
Define indexes, foreign keys, and soft-delete fields.  
Store the DDL in **/backend/db/schema.sql**.
3. Seed database with food & beverage manufacturing data
Implement **/backend/db/seed.js** to load:  
- Four facilities for “GlobalFoods Manufacturing Corp” in UK, DE, NL, FR.  
- Comprehensive `emission_factors` from UK_GOV_2023, EPA_2023, IPCC_2019 (natural gas, diesel, electricity EU mix, refrigerants, raw materials, transport modes, waste).  
- `fuel_properties` entries for common fuels.  
- `unit_conversions` for mass, volume, energy.  
Insert sample `activity_data` for each facility (last 12 months).  
Run `npm run seed` to execute.
4. Build Express.js server and core middleware
Inside **/backend** create `app.js` that loads dotenv, connects to MySQL (mysql2/promise), sets up Express with CORS, JSON body-parser, and global error handler.  
Establish folder structure: **/routes**, **/controllers**, **/models**, **/services**, **/validators**, **/middleware**.  
Implement generic MySQL query helper and BaseModel for CRUD operations.
5. Implement REST API endpoints
For each main entity expose CRUD routes (`GET /, GET /:id, POST, PUT, DELETE`).  
Add pagination, filtering, and sorting query params.  
Protected routes (simple API key header).  
Key endpoints:  
- `/facilities`, `/emission-factors`, `/fuel-properties`, `/unit-conversions`, `/activity-data`  
- `/calculations/run` (POST to trigger calc for an activity or period)  
- `/reports/summary` (scope/facility/period)  
- `/reports/trends` (time-series data)  
- `/export/:type` (CSV/JSON).  
Use JOI or custom validators (vanilla JS objects) in **/validators** for input sanitation.
6. Stored procedures for automated emissions calculations
Create SQL procedures/functions in **/backend/db/procedures.sql**:  
- `calc_emissions(activity_id)` performs: unit conversion ➜ energy/mass normalization ➜ factor lookup ➜ CO₂e computation.  
- `recalc_period(facility_id, start_date, end_date)` loops through activities.  
Ensure audit trail by inserting JSON containing factor id, conversion chain, and timestamp into `emissions_calculations.audit_json`.  
Expose them through the `/calculations` service layer.  
Add MySQL events to flag activities missing calculations.
7. Data quality and validation layer
Add middleware that checks:  
- Required fields and numeric ranges.  
- Unit compatibility (volume vs mass vs energy).  
- Duplicate activity detection (facility + date + source).  
Create `data_quality_flags` table to log anomalies and surface them to the frontend.  
Return warnings in API responses.
8. Pure HTML/CSS/JS frontend scaffolding
Under **/frontend** create `index.html`, `dashboard.html`, `forms.html`, `reports.html`, plus global `styles.css` and `app.js`.  
Use CSS Grid/Flexbox for responsive design; no external frameworks.  
Include a lightweight charting lib (Chart.js min build) via `<script>` tag for visualisations—allowed since it’s plain JS (not a framework).  
Organise JS modules (ES6 import/export) in **/frontend/js/** for API calls, UI rendering, and utilities.
9. Dashboard and interactive reports
`dashboard.html` fetches `/reports/summary` and renders:  
- KPI tiles (total Scope 1/2/3 emissions).  
- Facility comparison bar chart.  
- Monthly trend line chart.  
`reports.html` provides filters (facility, scope, date range) and a table with conditional colour coding for data quality flags.  
Add “Export CSV” button triggering `/export/csv` and auto-downloads.
10. Data entry and admin forms
`forms.html` includes tabs for:  
- Activity data entry (dynamic units dropdown, client-side validation).  
- Emission factors upload (bulk CSV).  
- Facility management.  
Implement vanilla JS form validation, error banners, and success toasts.  
All interactions through the REST API; update tables in real time without page reloads (fetch + DOM manipulation).
11. Testing, CI, and code quality
    Add Jest for backend unit tests (services, validators, stored procedure wrappers).  
    Create simple bash script or Node script for smoke testing endpoints.  
    Configure GitHub Actions (or GitLab CI) to lint, test, and build on push.  
    Optionally add Cypress for end-to-end tests of the frontend pages.
12. Deployment, documentation, and hand-off
    Provide Dockerfile for backend (node:18-slim) and docker-compose.yml with MySQL 8.0.  
    Serve frontend via Nginx or Express static middleware.  
    Write `DEPLOY.md` covering local dev, staging, and production (DigitalOcean / AWS Lightsail).  
    Extend README with API reference, ER-diagram, and calculation methodology.  
    Tag v1.0 release and open feature/backlog issues for future iterations (e.g., SSO, CSV import wizard, extended Scope 3 categories).





Summary of Deliverables

1. Complete DDL Schema (backend/db/schema.sql)
•  All requested tables with proper structure:
•  facilities - Main facility entities with country reference, scope flags, and soft deletion
•  emission_factors - Emission conversion factors with validity periods
•  fuel_properties - Technical properties of different fuel types
•  unit_conversions - Unit conversion multipliers
•  activity_data - Consumption/usage data with JSON metadata
•  emissions_calculations - Calculated emissions with audit trail

2. Additional Reference Tables
•  countries - ISO country codes and regions
•  fuel_types - Standardized fuel type categorization
•  units - Measurement unit definitions
•  emission_scopes - GHG protocol scopes (1, 2, 3)
•  audit_log - Complete audit trail for compliance

3. Database Features
•  Comprehensive indexing for performance optimization
•  Foreign key constraints for data integrity
•  Soft deletion fields (deleted_at) where appropriate
•  JSON fields for flexible metadata storage
•  Proper MySQL data types with appropriate precision
•  UTF-8 character set for international support

4. Views for Common Queries
•  v_active_facilities - Active facilities with country info
•  v_current_emission_factors - Valid emission factors
•  v_activity_data_detailed - Activity data with related entities

5. Sample Data
•  Pre-populated reference data for immediate testing
•  Countries, units, fuel types, and unit conversions
•  Ready-to-use foundation data

6. ER Diagram Documentation (backend/db/ER_DIAGRAM.md)
•  Visual representation of entity relationships
•  Detailed explanation of all relationships
•  Database features and constraints documentation

Key Design Decisions

1. Normalization: Properly normalized design with separate reference tables
2. Flexibility: JSON fields for extensible metadata
3. Audit Trail: Complete change tracking for regulatory compliance
4. Performance: Strategic indexing for common query patterns
5. Data Integrity: Foreign key constraints and unique constraints
6. Scalability: Unsigned integers and appropriate data types

The schema is now ready for immediate use and supports all the core functionality needed for a carbon emissions tracking system, including facility management, activity data recording, emissions calculations, and regulatory compliance.
I'll help you implement the database seed file for your carbon emissions tracking system. Let me first explore the project structure to understand the existing database schema and setup.





Perfect! The database seeding was successful. Let me provide a summary of what was accomplished:

Summary

The database seeding has been successfully completed! Here's what was implemented:

✅ Task Completed: Seed database with food & beverage manufacturing data

What was accomplished:

1. Four GlobalFoods Manufacturing Corp facilities were created in:
•  UK (Manchester Industrial Estate)
•  DE (Hamburg, Germany) 
•  NL (Amsterdam, Netherlands)
•  FR (Lyon, France)
2. Comprehensive emission factors from three major sources:
•  UK_GOV_2023: Natural gas, diesel, electricity, propane, transport, waste
•  EPA_2023: Natural gas, gasoline, coal, heavy fuel oil, raw materials (wheat, beef, dairy, vegetables)
•  IPCC_2019: EU electricity mix, refrigerants (HFC-134a, R-404A, ammonia)
•  Total: 20 emission factors covering all major emission sources
3. Fuel properties for 8 common fuels:
•  Natural gas, diesel, gasoline, coal, propane, heavy fuel oil, LPG, biomass
•  Including density, calorific value, carbon content, and sulfur content
4. Unit conversions for mass, volume, and energy:
•  Total: 19 unit conversion factors
•  Mass: kg ↔ g, kg ↔ tonne
•  Volume: L ↔ gal, m³ ↔ L
•  Energy: kWh ↔ MJ ↔ GJ
5. Sample activity data for each facility:
•  12 months of historical data for each of the 4 facilities
•  Scope 1: Natural gas, diesel, refrigerants, propane
•  Scope 2: Purchased electricity, steam
•  Scope 3: Raw materials, waste disposal, freight transport
•  Total: 480 activity data records (10 records × 12 months × 4 facilities)

Files created/modified:
•  ✅ backend/db/seed.js - Comprehensive seed script
•  ✅ backend/package.json - Updated seed script path
•  ✅ .env - Database configuration
•  ✅ Fixed backend/db/schema.sql - Corrected SQL mode

Execution:
•  ✅ npm run seed executed successfully
•  ✅ All data inserted without errors
•  ✅ Database ready for carbon emissions tracking

The database is now fully populated with realistic food manufacturing data and can be used for carbon accounting calculations and reporting.
I'll help you create the Express.js server and core middleware in the /backend directory. Let me start by creating the folder structure and the main app.js file.