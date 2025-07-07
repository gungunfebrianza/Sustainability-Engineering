# Datindo Carbon Accounting Preparation

## Scope

**Scope 1**: Fleet vehicles for ATM delivery and service, facility heating, refrigerants, and backup generators

**Scope 2**: Electricity consumption at warehouses, offices, and ATM testing facilities, plus renewable energy tracking

**Scope 3**:

- Upstream: ATM manufacturing emissions, spare parts, packaging, and inbound logistics
- Downstream: ATM delivery to banks, use-phase electricity consumption (the largest emission source), service/maintenance trips, and end-of-life recycling
- Supporting activities: Business travel, employee commuting, and leased assets

## **Technical specifics included**

- Quantitative data requirements (units, weights, distances, energy consumption)
- Material composition tracking for recycling calculations
- Power consumption specifications (watts/kWh per ATM)
- Transportation modes and distances for logistics emissions
- Grid emission factors for different regions
- Lifecycle considerations (7-10 year operational life)



# Carbon Accounting for Technology Distributor Company

## Scope 1 - Direct Emissions

| Question                                                     | Scope | Category              | Input Type   | Data Type                                        | Example Answer                                           |
| ------------------------------------------------------------ | ----- | --------------------- | ------------ | ------------------------------------------------ | -------------------------------------------------------- |
| What is the total fuel consumption of company-owned delivery vehicles for ATM transportation? | 1     | Mobile Combustion     | Quantitative | Liters/gallons per year by fuel type             | Diesel: 45,000 liters/year; Gasoline: 12,000 liters/year |
| Do you operate any company-owned service vehicles for ATM maintenance? What is their fuel consumption? | 1     | Mobile Combustion     | Quantitative | Liters/gallons per year by fuel type             | 15 service vans: 28,000 liters diesel/year               |
| What type and amount of refrigerants are used in your warehouse/office HVAC systems? | 1     | Fugitive Emissions    | Quantitative | kg of refrigerant by type (R-410A, R-134a, etc.) | R-410A: 45 kg total capacity, 3.5 kg annual leakage      |
| Do you use any backup generators at warehouses or offices? What is their fuel consumption? | 1     | Stationary Combustion | Quantitative | Liters/hours of operation by fuel type           | 2 diesel generators, 500 liters/year total               |
| What is the natural gas consumption for heating at owned facilities? | 1     | Stationary Combustion | Quantitative | Cubic meters or therms per year                  | 12,000 m³/year for warehouse heating                     |



---



**Transportation Emissions Calculation (EPA Factors)**

Commercial delivery trucks, especially those used for transporting heavy equipment like ATMs, are almost always diesel-powered due to better fuel efficiency and torque for heavy loads.

**Your diesel consumption:** 45,000 liters/year

**Results:**

- **Total annual emissions: 121.78 metric tons CO2e**
- **Emissions per liter: 2.706 kg CO2e/liter**

**Detailed breakdown**

1. **CO2 emissions:** 121,373.91 kg (99.7% of total) 

   Every liter of diesel produces ~2.68 kg of CO2

2. **CH4 emissions:** 121.85 kg CO2e (0.1% of total) 

   **Actual emission** Only 4.87 kg of CH4, but equals 122 kg CO2e (**25x more potent** than CO2 at trapping heat)

3. **N2O emissions:** 283.40 kg CO2e (0.2% of total)

   **Actual emission** Only 0.95 kg of N2O, but equals 283 kg CO2e (**298x more potent** than CO2)

**Practical insights**

- If a typical ATM delivery uses 50 liters of diesel (round trip), each delivery generates approximately **135.31 kg CO2e**
- This means delivering one ATM has roughly the same carbon footprint as burning 57 liters of gasoline in a passenger car

**EPA Emission Factors Used**

- **CO2**: 10.21 kg CO2/gallon of diesel = 2.697 kg CO2/liter (99.7%)
- **CH4**: 0.41 g CH4/gallon (heavy-duty diesel trucks) = 0.0027 kg CO2e/liter (0.1%)
- **N2O**: 0.08 g N2O/gallon (heavy-duty diesel trucks) = 0.0063 kg CO2e/liter (0.2%)
- **GWP factors**: CH4 = 25, N2O = 298



---

**Delivery/Transportation Vehicles**

**Purpose**: Vehicles used for initial ATM delivery from warehouse to bank locations

**Characteristics**:

- Typically larger vehicles (heavy trucks, flatbeds)
- Make planned routes for new ATM installations
- Carry whole ATM units (e.g 380+ kg each)
- Require special handling equipment
- Often deliver multiple units per trip

**Example**: A delivery truck transports 5 new ATMs from the central warehouse to various bank branches across a 300 km route

Note : Delivery trucks typically consume more fuel per km but may be used less frequently, while service vehicles make many more trips with lower fuel consumption per trip. 

- **Vehicle Size and Weight (Heavier vehicles require more energy to accelerate and maintain speed)**, 
  - **Delivery trucks**: Often 7.5-26 tonnes gross vehicle weight
  - **Service vans**: Typically 2-3.5 tonnes
- **Engine Size and Type (Larger engines inherently consume more fuel)**, 
  - **Delivery trucks**: Large diesel engines (6-12 liters)
  - **Service vans**: Smaller engines (2-3 liters)
- **Aerodynamics (Trucks have larger frontal areas and poor aerodynamic profiles)**
  - Creates more air resistance, especially at highway speeds
  - Box trucks can consume 20-35 L/100km vs. 7-10 L/100km for vans



# Fuel Consumption of Company-Owned ATM Delivery Vehicles

## Scenario: ATM Distributor Fleet Operations

| Name Activity                             | Category Activity           | Emission Source              | Emission Factor (EPA) | Unit           | GWP  | GHG Type | Quantity Source Emissions | Total Calculation  |
| ----------------------------------------- | --------------------------- | ---------------------------- | --------------------- | -------------- | ---- | -------- | ------------------------- | ------------------ |
| Heavy-duty diesel trucks - ATM delivery   | Mobile Combustion - Scope 1 | Diesel fuel combustion       | 10.21                 | kg CO2e/gallon | 1    | CO2      | 11,889 gallons/year       | 121,386.69 kg CO2e |
| Medium-duty diesel trucks - ATM delivery  | Mobile Combustion - Scope 1 | Diesel fuel combustion       | 10.21                 | kg CO2e/gallon | 1    | CO2      | 6,604 gallons/year        | 67,426.84 kg CO2e  |
| Light-duty diesel vans - Local delivery   | Mobile Combustion - Scope 1 | Diesel fuel combustion       | 10.21                 | kg CO2e/gallon | 1    | CO2      | 3,170 gallons/year        | 32,365.70 kg CO2e  |
| Gasoline cargo vans - Urban delivery      | Mobile Combustion - Scope 1 | Gasoline combustion          | 8.78                  | kg CO2e/gallon | 1    | CO2      | 3,170 gallons/year        | 27,832.60 kg CO2e  |
| Heavy-duty diesel trucks - CH4 emissions  | Mobile Combustion - Scope 1 | Diesel fuel combustion (CH4) | 0.0051                | kg CH4/gallon  | 28   | CH4      | 11,889 gallons/year       | 1,698.23 kg CO2e   |
| Medium-duty diesel trucks - CH4 emissions | Mobile Combustion - Scope 1 | Diesel fuel combustion (CH4) | 0.0048                | kg CH4/gallon  | 28   | CH4      | 6,604 gallons/year        | 887.90 kg CO2e     |
| Light-duty diesel vans - CH4 emissions    | Mobile Combustion - Scope 1 | Diesel fuel combustion (CH4) | 0.0005                | kg CH4/gallon  | 28   | CH4      | 3,170 gallons/year        | 44.38 kg CO2e      |
| Gasoline cargo vans - CH4 emissions       | Mobile Combustion - Scope 1 | Gasoline combustion (CH4)    | 0.0003                | kg CH4/gallon  | 28   | CH4      | 3,170 gallons/year        | 26.63 kg CO2e      |
| Heavy-duty diesel trucks - N2O emissions  | Mobile Combustion - Scope 1 | Diesel fuel combustion (N2O) | 0.0010                | kg N2O/gallon  | 265  | N2O      | 11,889 gallons/year       | 3,150.59 kg CO2e   |
| Medium-duty diesel trucks - N2O emissions | Mobile Combustion - Scope 1 | Diesel fuel combustion (N2O) | 0.0010                | kg N2O/gallon  | 265  | N2O      | 6,604 gallons/year        | 1,750.06 kg CO2e   |
| Light-duty diesel vans - N2O emissions    | Mobile Combustion - Scope 1 | Diesel fuel combustion (N2O) | 0.0001                | kg N2O/gallon  | 265  | N2O      | 3,170 gallons/year        | 84.01 kg CO2e      |
| Gasoline cargo vans - N2O emissions       | Mobile Combustion - Scope 1 | Gasoline combustion (N2O)    | 0.0003                | kg N2O/gallon  | 265  | N2O      | 3,170 gallons/year        | 252.02 kg CO2e     |

**Summary by Fuel Type**

**Diesel Vehicles Total**

- **Total Diesel Consumption**: 21,663 gallons/year (82,000 liters/year)

- Total Diesel Emissions

  : 228,589.1 kg CO2e/year

  - CO2: 221,179.2 kg
  - CH4: 2,630.5 kg CO2e
  - N2O: 4,984.7 kg CO2e

**Gasoline Vehicles Total**

- **Total Gasoline Consumption**: 3,170 gallons/year (12,000 liters/year)

- Total Gasoline Emissions

  : 28,111.3 kg CO2e/year

  - CO2: 27,832.6 kg
  - CH4: 26.6 kg CO2e
  - N2O: 252.0 kg CO2e

**Grand Total Fleet Emissions**

**Total Annual Emissions from ATM Delivery Fleet: 256,700.4 kg CO2e (256.7 metric tons CO2e)**

**Notes on Calculations**

1. **Emission Factors Source**: EPA Emission Factors for Greenhouse Gas Inventories (March 2024)
   - Table 2: Mobile Combustion CO2 Emission Factors
   - Table 3: Mobile Combustion CH4 and N2O Emission Factors
2. **Vehicle Categories**:
   - Heavy-duty trucks (Class 8): Used for bulk ATM deliveries, long-distance routes
   - Medium-duty trucks (Class 6-7): Regional distribution, multiple ATM deliveries
   - Light-duty vans: Last-mile delivery, single ATM installations
   - Gasoline vans: Urban deliveries where diesel restrictions apply
3. **GWP Values** (IPCC AR6):
   - CO2: 1
   - CH4: 28
   - N2O: 265
4. **Calculation Formula**:
   - For CO2: Fuel Quantity × CO2 Emission Factor
   - For CH4 & N2O: Fuel Quantity × Gas Emission Factor × GWP
5. **Data Collection Requirements**:
   - Track fuel purchases by vehicle type
   - Maintain fuel logs by vehicle class
   - Record odometer readings for verification
   - Monitor fuel efficiency trends

**Recommendations for Emissions Reduction**

1. **Fleet Optimization**:
   - Route optimization software to reduce total miles driven
   - Load consolidation to maximize delivery efficiency
   - Consider electric or hybrid vehicles for urban routes
2. **Fuel Efficiency**:
   - Driver training on eco-driving techniques
   - Regular vehicle maintenance schedules
   - Tire pressure monitoring systems
3. **Alternative Fuels**:
   - Biodiesel blends (B20) for compatible diesel vehicles
   - Compressed natural gas (CNG) for new vehicle purchases
   - Electric vehicles for short-range urban deliveries



---



**Service/Maintenance Vehicles**

**Purpose**: Vehicles used for ATM repairs, maintenance calls, and technical support

**Characteristics**:

- Typically smaller vehicles (vans, light trucks)
- Make frequent, shorter trips to individual ATM locations
- Carry tools, spare parts, and technicians
- Often have irregular routes based on service requests
- May include specialized equipment (diagnostic tools, lifts)

**Example**: A technician drives a service van 80 km to fix a card reader jam at a single ATM location

Based on the service vehicle characteristics for ATM maintenance, here's a detailed emissions calculation table:

| Name Activity              | Category Activity | Emission Source                   | Emission Factor (EPA) | Unit           | GWP  | GHG Type | Quantity Source Emissions | Total Calculation        |
| -------------------------- | ----------------- | --------------------------------- | --------------------- | -------------- | ---- | -------- | ------------------------- | ------------------------ |
| Service Van - Gasoline     | Mobile Combustion | 15 Ford Transit vans (gasoline)   | 8.78                  | kg CO2e/gallon | 1    | CO2      | 18,000 gallons/year       | 158,040 kg CO2e          |
| Service Van - Gasoline CH4 | Mobile Combustion | 15 Ford Transit vans (gasoline)   | 0.38                  | g CH4/mile     | 28   | CH4      | 450,000 miles/year        | 4,788 kg CO2e            |
| Service Van - Gasoline N2O | Mobile Combustion | 15 Ford Transit vans (gasoline)   | 0.04                  | g N2O/mile     | 265  | N2O      | 450,000 miles/year        | 4,770 kg CO2e            |
| Light Truck - Diesel       | Mobile Combustion | 8 Chevrolet Express 2500 (diesel) | 10.21                 | kg CO2e/gallon | 1    | CO2      | 12,000 gallons/year       | 122,520 kg CO2e          |
| Light Truck - Diesel CH4   | Mobile Combustion | 8 Chevrolet Express 2500 (diesel) | 0.051                 | g CH4/mile     | 28   | CH4      | 240,000 miles/year        | 343 kg CO2e              |
| Light Truck - Diesel N2O   | Mobile Combustion | 8 Chevrolet Express 2500 (diesel) | 0.048                 | g N2O/mile     | 265  | N2O      | 240,000 miles/year        | 3,053 kg CO2e            |
| Hybrid Service Vehicle     | Mobile Combustion | 5 Toyota Sienna Hybrid            | 8.78                  | kg CO2e/gallon | 1    | CO2      | 4,500 gallons/year        | 39,510 kg CO2e           |
| Hybrid Service Vehicle CH4 | Mobile Combustion | 5 Toyota Sienna Hybrid            | 0.38                  | g CH4/mile     | 28   | CH4      | 125,000 miles/year        | 1,330 kg CO2e            |
| Hybrid Service Vehicle N2O | Mobile Combustion | 5 Toyota Sienna Hybrid            | 0.04                  | g N2O/mile     | 265  | N2O      | 125,000 miles/year        | 1,325 kg CO2e            |
| **Total Fleet Emissions**  |                   |                                   |                       |                |      |          |                           | **335,679 kg CO2e/year** |

**Key Assumptions for Calculations**:

- Average 30,000 miles/year per gasoline van (80-100 km/day service routes)
- Average 30,000 miles/year per diesel truck (heavier equipment transport)
- Average 25,000 miles/year per hybrid vehicle (urban routes)
- Gasoline vans: 25 mpg average
- Diesel trucks: 20 mpg average
- Hybrid vehicles: 36 mpg average
- EPA emission factors from EPA GHG Emission Factors Hub (2024)
- GWP values from IPCC AR6

**Additional Context**:

- Service calls average 80 km round trip
- Each vehicle handles 6-8 service calls per day
- Fleet includes tool storage, diagnostic equipment, spare parts inventory
- Some vehicles equipped with lifts for heavy component replacement



---

**HVAC Emissions Calculation (EPA Factors)**

R-410A is a hydrofluorocarbon (HFC) refrigerant commonly used in residential and commercial air conditioning systems. The "45 kg" in the example refers to the total refrigerant capacity in a large commercial system.

Samsung WindFree Lite 1.5 PK Specifications

For a 1.5 PK (approximately 1.5 HP or 12,000-13,000 BTU) residential air conditioner:

- **Typical R-410A charge**: 1.0-1.5 kg (your specific model likely contains around 1.2 kg)
- **Annual leakage rate**: 2-5% for residential units (EPA default is 2% for well-maintained systems)

**PK/HP**: Used in regions with European influence (simpler whole numbers). 1 HP = 746 watts of electrical power. 1 HP ≈ 9,000-10,000 BTU/hr of cooling capacity.

**BTU**: Used in USA, UK, and countries following American standards (more precise for HVAC calculations)

**kW**: Scientific/international standard (1 kW = 3,412 BTU/hr)

**Emissions Calculation**

Using EPA emission factors:

**R-410A Global Warming Potential (GWP)**: 2,088 kg CO2e per kg

**Annual Leakage Emissions:**

Refrigerant charge × Leakage rate × GWP = Annual emissions

1.2 kg × 0.02 × 2,088 = 50.1 kg CO2e per year



# Refrigerant Emissions from Warehouse/Office HVAC Systems

## Emission Calculation Table

| Name Activity               | Category Activity                  | Emission Source            | Emission Factor (EPA)    | Unit                | GWP   | GHG Type                                          | Quantity Source Emissions                     | Total Calculation                   |
| --------------------------- | ---------------------------------- | -------------------------- | ------------------------ | ------------------- | ----- | ------------------------------------------------- | --------------------------------------------- | ----------------------------------- |
| Office Building AC Units    | Fugitive Emissions - Refrigeration | R-410A Refrigerant Leakage | 2.0% annual leakage rate | kg refrigerant/year | 2,088 | HFC Blend (50% HFC-32, 50% HFC-125)               | Total charge: 25 kg × 2% = 0.5 kg leakage     | 0.5 kg × 2,088 = 1,044 kg CO2e      |
| Warehouse Rooftop Units     | Fugitive Emissions - Refrigeration | R-410A Refrigerant Leakage | 2.0% annual leakage rate | kg refrigerant/year | 2,088 | HFC Blend (50% HFC-32, 50% HFC-125)               | Total charge: 120 kg × 2% = 2.4 kg leakage    | 2.4 kg × 2,088 = 5,011.2 kg CO2e    |
| Server Room Cooling         | Fugitive Emissions - Refrigeration | R-134a Refrigerant Leakage | 1.5% annual leakage rate | kg refrigerant/year | 1,430 | HFC-134a                                          | Total charge: 15 kg × 1.5% = 0.225 kg leakage | 0.225 kg × 1,430 = 321.75 kg CO2e   |
| Office Building AC Disposal | Fugitive Emissions - Refrigeration | R-410A End-of-Life Release | 10% disposal loss rate   | kg refrigerant      | 2,088 | HFC Blend (50% HFC-32, 50% HFC-125)               | 1 unit replaced: 8 kg × 10% = 0.8 kg released | 0.8 kg × 2,088 = 1,670.4 kg CO2e    |
| Warehouse Chiller           | Fugitive Emissions - Refrigeration | R-407C Refrigerant Leakage | 2.5% annual leakage rate | kg refrigerant/year | 1,774 | HFC Blend (23% HFC-32, 25% HFC-125, 52% HFC-134a) | Total charge: 45 kg × 2.5% = 1.125 kg leakage | 1.125 kg × 1,774 = 1,995.75 kg CO2e |
| Office Split Systems        | Fugitive Emissions - Refrigeration | R-32 Refrigerant Leakage   | 1.5% annual leakage rate | kg refrigerant/year | 675   | HFC-32                                            | Total charge: 18 kg × 1.5% = 0.27 kg leakage  | 0.27 kg × 675 = 182.25 kg CO2e      |
| **TOTAL ANNUAL EMISSIONS**  |                                    |                            |                          |                     |       |                                                   | **Total Refrigerant Leakage: 4.72 kg**        | **10,225.35 kg CO2e**               |

**Additional Details for Complete Reporting**

**Equipment Inventory**

- **Office Building**: 5 rooftop units (5 kg R-410A each), 6 split systems (3 kg R-32 each)
- **Warehouse**: 3 large rooftop units (40 kg R-410A each), 1 chiller (45 kg R-407C)
- **Server Room**: 2 precision cooling units (7.5 kg R-134a each)

**Leakage Rate Sources**

- EPA default factors for commercial refrigeration equipment
- Enhanced rates for older equipment (>10 years)
- Lower rates for new equipment with leak detection systems

**Key Assumptions**

- Annual service records used to track actual refrigerant additions
- Disposal emissions calculated only for equipment replaced during reporting year
- GWP values from IPCC Fifth Assessment Report (AR5)

**Data Quality Notes**

- Actual leakage data preferred over default emission factors where available
- Service technician logs provide refrigerant addition quantities
- Equipment nameplates document total refrigerant charge capacity



---



# Backup Generator Emissions Calculation

Example Answer: 2 Diesel Generators, 500 Liters/Year Total

| Name Activity          | Category Activity     | Emission Source        | Emission Factor (EPA) | Unit          | GWP  | GHG Type | Quantity Source Emissions | Total Calculation                 |
| ---------------------- | --------------------- | ---------------------- | --------------------- | ------------- | ---- | -------- | ------------------------- | --------------------------------- |
| Diesel Generator - CO2 | Stationary Combustion | Diesel fuel combustion | 10.21                 | kg CO2/gallon | 1    | CO2      | 132.09 gallons (500 L)    | 1,349.64 kg CO2                   |
| Diesel Generator - CH4 | Stationary Combustion | Diesel fuel combustion | 0.0006                | kg CH4/gallon | 28   | CH4      | 132.09 gallons (500 L)    | 0.079 kg CH4 × 28 = 2.21 kg CO2e  |
| Diesel Generator - N2O | Stationary Combustion | Diesel fuel combustion | 0.0001                | kg N2O/gallon | 265  | N2O      | 132.09 gallons (500 L)    | 0.013 kg N2O × 265 = 3.45 kg CO2e |

**Total Annual Emissions: 1,355.30 kg CO2e (1.36 metric tons CO2e)**

**Emission Factor Sources and Notes:**

**EPA Emission Factors Used:**

- Source: EPA Emission Factors for Greenhouse Gas Inventories (March 2024)
- Table 1.3 - Stationary Combustion Emission Factors
- Diesel fuel density: 3.785 liters/gallon

**GWP Values:**

- Based on IPCC Sixth Assessment Report (AR6)
- 100-year time horizon values

**Conversion Calculations:**

- 500 liters ÷ 3.785 liters/gallon = 132.09 gallons
- CO2: 132.09 gallons × 10.21 kg CO2/gallon = 1,349.64 kg CO2
- CH4: 132.09 gallons × 0.0006 kg CH4/gallon × 28 GWP = 2.21 kg CO2e
- N2O: 132.09 gallons × 0.0001 kg N2O/gallon × 265 GWP = 3.45 kg CO2e

## Alternative Calculation Using Higher Heating Value (HHV):

| Name Activity                | Category Activity     | Emission Source        | Emission Factor (EPA) | Unit         | GWP  | GHG Type | Quantity Source Emissions | Total Calculation |
| ---------------------------- | --------------------- | ---------------------- | --------------------- | ------------ | ---- | -------- | ------------------------- | ----------------- |
| Diesel Generator - CO2 (HHV) | Stationary Combustion | Diesel fuel combustion | 73.96                 | kg CO2/MMBtu | 1    | CO2      | 18.24 MMBtu               | 1,349.23 kg CO2   |
| Diesel Generator - CH4 (HHV) | Stationary Combustion | Diesel fuel combustion | 0.003                 | g CH4/MMBtu  | 28   | CH4      | 18.24 MMBtu               | 1.53 kg CO2e      |
| Diesel Generator - N2O (HHV) | Stationary Combustion | Diesel fuel combustion | 0.0006                | g N2O/MMBtu  | 265  | N2O      | 18.24 MMBtu               | 2.90 kg CO2e      |

**HHV Conversion:**

- Diesel HHV: 138,074 Btu/gallon
- 132.09 gallons × 138,074 Btu/gallon = 18.24 MMBtu

**Total using HHV method: 1,353.66 kg CO2e**

**Additional Considerations:**

1. **Operating Hours**: If available, track hours of operation for more accurate activity data
2. **Generator Size**: Larger generators may have different emission factors
3. **Maintenance**: Well-maintained generators typically have lower CH4 and N2O emissions
4. **Load Factor**: Emissions can vary based on generator load (% of capacity used)
5. **Fuel Quality**: Ultra-low sulfur diesel (ULSD) is standard in most regions

**Data Quality Notes:**

- **Uncertainty**: ±5% for CO2, ±50% for CH4 and N2O based on EPA guidance
- **Recommendation**: Install hour meters on generators for more precise tracking
- **Best Practice**: Keep fuel purchase records as backup documentation



---







## Scope 2 - Indirect Emissions from Purchased Energy

| Question                                                     | Scope | Category                     | Input Type               | Data Type                | Example Answer                                              |
| ------------------------------------------------------------ | ----- | ---------------------------- | ------------------------ | ------------------------ | ----------------------------------------------------------- |
| What is the total electricity consumption at all company-operated facilities? | 2     | Purchased Electricity        | Quantitative             | kWh per year by location | Headquarters: 450,000 kWh/year; Warehouse: 800,000 kWh/year |
| Do you track electricity consumption for ATM testing/quality control operations? | 2     | Purchased Electricity        | Quantitative             | kWh per year             | ATM testing lab: 125,000 kWh/year                           |
| What percentage of your electricity comes from renewable sources or RECs? | 2     | Purchased Electricity        | Quantitative             | Percentage and MWh       | 30% renewable (375,000 kWh from solar PPA)                  |
| Do you purchase any steam, heating, or cooling from external suppliers? | 2     | Purchased Heat/Steam/Cooling | Quantitative             | GJ or MWh per year       | District cooling: 250 MWh/year for data center              |
| What are the grid emission factors for each facility location? | 2     | Purchased Electricity        | Qualitative/Quantitative | kg CO2e/kWh by region    | Texas facility: 0.396 kg CO2e/kWh                           |



# Electricity Consumption Emissions Calculation - Company-Operated Facilities

## Scope 2 Emissions from Purchased Electricity

| Name Activity                   | Category Activity                      | Emission Source       | Emission Factor (EPA)       | Unit            | GWP   | GHG Type | Quantity Source Emissions | Total Calculation                 |
| ------------------------------- | -------------------------------------- | --------------------- | --------------------------- | --------------- | ----- | -------- | ------------------------- | --------------------------------- |
| Headquarters Office Electricity | Purchased Electricity - Location Based | GRID                  | 0.396                       | kg CO2e/kWh     | 1     | CO2      | 450,000 kWh               | 450,000 × 0.396 = 178,200 kg CO2e |
| Main Warehouse Electricity      | Purchased Electricity - Location Based | GRID                  | 0.203                       | kg CO2e/kWh     | 1     | CO2      | 800,000 kWh               | 800,000 × 0.203 = 162,400 kg CO2e |
| ATM Testing Laboratory          | Purchased Electricity - Location Based | GRID                  | 0.368                       | kg CO2e/kWh     | 1     | CO2      | 125,000 kWh               | 125,000 × 0.368 = 46,000 kg CO2e  |
| Regional Service Center - East  | Purchased Electricity - Location Based | GRID                  | 0.274                       | kg CO2e/kWh     | 1     | CO2      | 75,000 kWh                | 75,000 × 0.274 = 20,550 kg CO2e   |
| Regional Service Center - West  | Purchased Electricity - Location Based | GRID                  | 0.291                       | kg CO2e/kWh     | 1     | CO2      | 65,000 kWh                | 65,000 × 0.291 = 18,915 kg CO2e   |
| Data Center (ATM Monitoring)    | Purchased Electricity - Location Based | GRID                  | 0.405                       | kg CO2e/kWh     | 1     | CO2      | 180,000 kWh               | 180,000 × 0.405 = 72,900 kg CO2e  |
| Training Facility               | Purchased Electricity - Location Based | GRIDt                 | 0.418                       | kg CO2e/kWh     | 1     | CO2      | 55,000 kWh                | 55,000 × 0.418 = 22,990 kg CO2e   |
| **TOTAL LOCATION-BASED**        | **Scope 2 - Location Based**           | **Multiple ID Grids** | **Weighted Average: 0.317** | **kg CO2e/kWh** | **1** | **CO2**  | **1,750,000 kWh**         | **521,955 kg CO2e**               |

## Market-Based Method (if renewable energy is purchased)

| Name Activity                    | Category Activity                    | Emission Source            | Emission Factor (EPA)       | Unit            | GWP   | GHG Type | Quantity Source Emissions | Total Calculation                          |
| -------------------------------- | ------------------------------------ | -------------------------- | --------------------------- | --------------- | ----- | -------- | ------------------------- | ------------------------------------------ |
| Headquarters - Grid Electricity  | Purchased Electricity - Market Based | Residual Mix               | 0.425                       | kg CO2e/kWh     | 1     | CO2      | 315,000 kWh               | 315,000 × 0.425 = 133,875 kg CO2e          |
| Headquarters - Solar PPA         | Purchased Electricity - Market Based | Solar PPA (100% renewable) | 0.000                       | kg CO2e/kWh     | 1     | CO2      | 135,000 kWh               | 135,000 × 0.000 = 0 kg CO2e                |
| Warehouse - Green Tariff Program | Purchased Electricity - Market Based | Wind RECs                  | 0.000                       | kg CO2e/kWh     | 1     | CO2      | 240,000 kWh               | 240,000 × 0.000 = 0 kg CO2e                |
| Warehouse - Grid Electricity     | Purchased Electricity - Market Based | Residual Mix               | 0.235                       | kg CO2e/kWh     | 1     | CO2      | 560,000 kWh               | 560,000 × 0.235 = 131,600 kg CO2e          |
| All Other Facilities - Grid      | Purchased Electricity - Market Based | Various Residual Mix       | Various                     | kg CO2e/kWh     | 1     | CO2      | 500,000 kWh               | (Calculated by location) = 164,925 kg CO2e |
| **TOTAL MARKET-BASED**           | **Scope 2 - Market Based**           | **Mixed Sources**          | **Weighted Average: 0.246** | **kg CO2e/kWh** | **1** | **CO2**  | **1,750,000 kWh**         | **430,400 kg CO2e**                        |



## Scope 3 - Value Chain Emissions

### Category 1: Purchased Goods and Services

| Question                                                     | Scope | Category        | Input Type               | Data Type                         | Example Answer                                               |
| ------------------------------------------------------------ | ----- | --------------- | ------------------------ | --------------------------------- | ------------------------------------------------------------ |
| How many ATM units do you purchase annually from manufacturers? | 3     | Purchased Goods | Quantitative             | Units by model type               | NCR SelfServ: 2,500 units; Diebold DN: 1,800 units           |
| What is the average weight and material composition of ATMs you distribute? | 3     | Purchased Goods | Quantitative             | kg by material type               | Average 380 kg: Steel 65%, Electronics 20%, Plastic 10%, Other 5% |
| Do you have supplier-specific emission factors or EPDs for ATM manufacturing? | 3     | Purchased Goods | Qualitative/Quantitative | kg CO2e per unit or EPD documents | NCR provides 1,250 kg CO2e/unit cradle-to-gate               |
| What spare parts and components do you stock for maintenance? | 3     | Purchased Goods | Quantitative             | Annual spend or units by category | Card readers: 5,000 units/year; Displays: 2,000 units/year   |
| What packaging materials do you purchase for ATM shipping?   | 3     | Purchased Goods | Quantitative             | kg or units by material type      | Wooden crates: 450 tonnes/year; Foam: 25 tonnes/year         |



# ATM Purchase Emissions Calculation Table

## Annual ATM Purchases from Manufacturers - Emission Calculations

| Name Activity                    | Category Activity           | Emission Source                     | Emission Factor (EPA) | Unit          | GWP  | GHG Type | Quantity Source Emissions                        | Total Calculation                       |
| -------------------------------- | --------------------------- | ----------------------------------- | --------------------- | ------------- | ---- | -------- | ------------------------------------------------ | --------------------------------------- |
| ATM Manufacturing - NCR SelfServ | Purchased Goods (Scope 3.1) | Cradle-to-gate manufacturing        | 2,847.6               | kg CO2e/tonne | 1    | CO2e     | 2,500 units × 0.380 tonnes/unit = 950 tonnes     | 950 × 2,847.6 = 2,705,220 kg CO2e       |
| ATM Manufacturing - Diebold DN   | Purchased Goods (Scope 3.1) | Cradle-to-gate manufacturing        | 2,847.6               | kg CO2e/tonne | 1    | CO2e     | 1,800 units × 0.385 tonnes/unit = 693 tonnes     | 693 × 2,847.6 = 1,973,387 kg CO2e       |
| ATM Electronics Components       | Purchased Goods (Scope 3.1) | Electronic components manufacturing | 10,124.0              | kg CO2e/tonne | 1    | CO2e     | 4,300 units × 0.076 tonnes/unit = 326.8 tonnes   | 326.8 × 10,124.0 = 3,308,523 kg CO2e    |
| ATM Steel Housing                | Purchased Goods (Scope 3.1) | Steel production                    | 2,103.0               | kg CO2e/tonne | 1    | CO2e     | 4,300 units × 0.247 tonnes/unit = 1,062.1 tonnes | 1,062.1 × 2,103.0 = 2,233,596 kg CO2e   |
| ATM Plastic Components           | Purchased Goods (Scope 3.1) | Plastic production                  | 3,117.0               | kg CO2e/tonne | 1    | CO2e     | 4,300 units × 0.038 tonnes/unit = 163.4 tonnes   | 163.4 × 3,117.0 = 509,318 kg CO2e       |
| ATM Display Screens              | Purchased Goods (Scope 3.1) | LCD/LED manufacturing               | 15,642.0              | kg CO2e/tonne | 1    | CO2e     | 4,300 units × 0.012 tonnes/unit = 51.6 tonnes    | 51.6 × 15,642.0 = 807,127 kg CO2e       |
| ATM Packaging Materials          | Purchased Goods (Scope 3.1) | Wooden crates/pallets               | 432.2                 | kg CO2e/tonne | 1    | CO2e     | 450 tonnes                                       | 450 × 432.2 = 194,490 kg CO2e           |
| ATM Packaging Materials          | Purchased Goods (Scope 3.1) | Foam packaging                      | 3,718.0               | kg CO2e/tonne | 1    | CO2e     | 25 tonnes                                        | 25 × 3,718.0 = 92,950 kg CO2e           |
| **TOTAL ANNUAL EMISSIONS**       | **Scope 3.1**               | **All ATM purchasing**              | -                     | -             | -    | **CO2e** | **4,300 ATMs + packaging**                       | **11,824,611 kg CO2e (11,824.6 tCO2e)** |



### Category 2: Capital Goods

| Question                                                     | Scope | Category      | Input Type   | Data Type                           | Example Answer                                       |
| ------------------------------------------------------------ | ----- | ------------- | ------------ | ----------------------------------- | ---------------------------------------------------- |
| What major equipment was purchased for warehouses/testing facilities? | 3     | Capital Goods | Quantitative | Cost and type of equipment          | 5 forklifts ($250,000), Testing equipment ($500,000) |
| Did you construct or renovate any facilities in the reporting year? | 3     | Capital Goods | Quantitative | Square meters and construction type | New 5,000 m² warehouse expansion                     |



# Major Equipment Emissions - Warehouse/Testing Facilities

## Capital Goods Equipment Purchases (Scope 3 - Category 2)

| Name Activity                        | Category Activity           | Emission Source               | Emission Factor (EPA) | Unit                    | GWP  | GHG Type | Quantity Source Emissions           | Total Calculation                  |
| ------------------------------------ | --------------------------- | ----------------------------- | --------------------- | ----------------------- | ---- | -------- | ----------------------------------- | ---------------------------------- |
| Electric Forklift Purchase (5 units) | Material Handling Equipment | Manufacturing/Production      | 8.5                   | kg CO2e/kg product      | 1    | CO2      | 5 units × 3,500 kg/unit = 17,500 kg | 17,500 kg × 8.5 = 148,750 kg CO2e  |
| Diesel Forklift Purchase (2 units)   | Material Handling Equipment | Manufacturing/Production      | 9.2                   | kg CO2e/kg product      | 1    | CO2      | 2 units × 4,200 kg/unit = 8,400 kg  | 8,400 kg × 9.2 = 77,280 kg CO2e    |
| ATM Testing Equipment - Electronic   | Testing Equipment           | Electronics Manufacturing     | 15.8                  | kg CO2e/kg electronics  | 1    | CO2      | 1,250 kg electronic components      | 1,250 kg × 15.8 = 19,750 kg CO2e   |
| Conveyor System                      | Material Handling           | Steel Manufacturing           | 2.89                  | kg CO2e/kg steel        | 1    | CO2      | 12,000 kg steel structure           | 12,000 kg × 2.89 = 34,680 kg CO2e  |
| Pallet Racking System                | Storage Equipment           | Steel Manufacturing           | 2.89                  | kg CO2e/kg steel        | 1    | CO2      | 45,000 kg steel                     | 45,000 kg × 2.89 = 130,050 kg CO2e |
| HVAC System Upgrade                  | Building Equipment          | Mixed Materials Manufacturing | 4.5                   | kg CO2e/$ spent         | 1    | CO2      | $125,000 equipment cost             | 125,000 × 4.5/1000 = 562.5 kg CO2e |
| Security Systems (Cameras, Access)   | Electronic Equipment        | Electronics Manufacturing     | 15.8                  | kg CO2e/kg electronics  | 1    | CO2      | 85 kg equipment                     | 85 kg × 15.8 = 1,343 kg CO2e       |
| Backup Generator (500kW)             | Power Equipment             | Engine Manufacturing          | 7.2                   | kg CO2e/kg product      | 1    | CO2      | 1 unit × 3,800 kg = 3,800 kg        | 3,800 kg × 7.2 = 27,360 kg CO2e    |
| Packaging Equipment                  | Processing Equipment        | Mixed Manufacturing           | 5.6                   | kg CO2e/kg equipment    | 1    | CO2      | 2,200 kg equipment                  | 2,200 kg × 5.6 = 12,320 kg CO2e    |
| Office Furniture                     | Office Equipment            | Mixed Materials               | 3.2                   | kg CO2e/kg product      | 1    | CO2      | 4,500 kg furniture                  | 4,500 kg × 3.2 = 14,400 kg CO2e    |
| Server/IT Infrastructure             | Computing Equipment         | Electronics Manufacturing     | 24.5                  | kg CO2e/kg electronics  | 1    | CO2      | 350 kg servers/networking           | 350 kg × 24.5 = 8,575 kg CO2e      |
| LED Lighting Retrofit                | Building Equipment          | Electronics Manufacturing     | 12.3                  | kg CO2e/kg LED fixtures | 1    | CO2      | 850 kg LED fixtures                 | 850 kg × 12.3 = 10,455 kg CO2e     |
| Air Compressor System                | Utility Equipment           | Industrial Manufacturing      | 6.8                   | kg CO2e/kg equipment    | 1    | CO2      | 1,100 kg equipment                  | 1,100 kg × 6.8 = 7,480 kg CO2e     |
| Battery Charging Stations            | Electrical Equipment        | Electrical Manufacturing      | 8.9                   | kg CO2e/kg equipment    | 1    | CO2      | 450 kg charging equipment           | 450 kg × 8.9 = 4,005 kg CO2e       |
| Workshop Tools & Equipment           | Maintenance Equipment       | Tool Manufacturing            | 11.2                  | kg CO2e/kg tools        | 1    | CO2      | 580 kg various tools                | 580 kg × 11.2 = 6,496 kg CO2e      |



### Category 3: Fuel and Energy Related Activities

| Question                                                     | Scope | Category        | Input Type   | Data Type                         | Example Answer                                       |
| ------------------------------------------------------------ | ----- | --------------- | ------------ | --------------------------------- | ---------------------------------------------------- |
| What are the upstream emissions for fuel used in company vehicles? | 3     | Fuel and Energy | Quantitative | Calculated from Scope 1 fuel use  | Well-to-tank: 15% additional on combustion emissions |
| What are the T&D losses for purchased electricity?           | 3     | Fuel and Energy | Quantitative | Percentage of Scope 2 electricity | 4.5% grid losses on 1,375,000 kWh                    |



# Upstream Emissions for Company Vehicle Fuels

## Scope 3 Category 3: Fuel and Energy-Related Activities (Not Included in Scope 1 or 2)

### Well-to-Tank (WTT) Emissions for Company Vehicles

| Name Activity                                         | Category Activity        | Emission Source       | Emission Factor (EPA) | Unit          | GWP  | GHG Type | Quantity Source Emissions | Total Calculation               |
| ----------------------------------------------------- | ------------------------ | --------------------- | --------------------- | ------------- | ---- | -------- | ------------------------- | ------------------------------- |
| Diesel fuel extraction & refining - Delivery trucks   | Upstream fuel production | Well-to-tank diesel   | 0.620                 | kg CO2e/liter | 1    | CO2e     | 45,000 liters/year        | 45,000 × 0.620 = 27,900 kg CO2e |
| Diesel fuel extraction & refining - Service vans      | Upstream fuel production | Well-to-tank diesel   | 0.620                 | kg CO2e/liter | 1    | CO2e     | 28,000 liters/year        | 28,000 × 0.620 = 17,360 kg CO2e |
| Gasoline fuel extraction & refining - Company cars    | Upstream fuel production | Well-to-tank gasoline | 0.610                 | kg CO2e/liter | 1    | CO2e     | 12,000 liters/year        | 12,000 × 0.610 = 7,320 kg CO2e  |
| Diesel fuel extraction & refining - Backup generators | Upstream fuel production | Well-to-tank diesel   | 0.620                 | kg CO2e/liter | 1    | CO2e     | 500 liters/year           | 500 × 0.620 = 310 kg CO2e       |
| **TOTAL UPSTREAM FUEL EMISSIONS**                     |                          |                       |                       |               |      |          |                           | **52,890 kg CO2e**              |

### Breakdown by Fuel Type

| Fuel Type | Total Annual Consumption | WTT Emission Factor | Total WTT Emissions |
| --------- | ------------------------ | ------------------- | ------------------- |
| Diesel    | 73,500 liters            | 0.620 kg CO2e/liter | 45,570 kg CO2e      |
| Gasoline  | 12,000 liters            | 0.610 kg CO2e/liter | 7,320 kg CO2e       |
| **TOTAL** | **85,500 liters**        |                     | **52,890 kg CO2e**  |

### Notes on Emission Factors:

- **EPA Emission Factors Source**: EPA's Emission Factors for Greenhouse Gas Inventories (March 2024) - Table 8 Indirect Emissions from Mobile Combustion
- Well-to-Tank (WTT) factors include emissions from:
  - Crude oil extraction
  - Transportation to refineries
  - Refining processes
  - Distribution to fuel stations
  - Storage and handling

### Alternative Emission Factor Sources for Comparison:

| Source       | Diesel WTT Factor | Gasoline WTT Factor | Units         |
| ------------ | ----------------- | ------------------- | ------------- |
| EPA 2024     | 0.620             | 0.610               | kg CO2e/liter |
| DEFRA 2024   | 0.594             | 0.642               | kg CO2e/liter |
| GHG Protocol | 0.570             | 0.580               | kg CO2e/liter |
| IEA 2023     | 0.635             | 0.625               | kg CO2e/liter |

### Relationship to Scope 1 Emissions:

| Activity            | Scope 1 (Direct Combustion) | Scope 3 Cat 3 (WTT) | Total Fuel Lifecycle |
| ------------------- | --------------------------- | ------------------- | -------------------- |
| Diesel (73,500 L)   | 195,405 kg CO2e*            | 45,570 kg CO2e      | 240,975 kg CO2e      |
| Gasoline (12,000 L) | 28,440 kg CO2e*             | 7,320 kg CO2e       | 35,760 kg CO2e       |
| **Total**           | **223,845 kg CO2e**         | **52,890 kg CO2e**  | **276,735 kg CO2e**  |

*Using EPA combustion factors: Diesel = 2.659 kg CO2e/L, Gasoline = 2.370 kg CO2e/L



# Transmission & Distribution (T&D) Losses for Purchased Electricity

## Calculation Table for Scope 3 Category 3: Fuel and Energy-Related Activities

| Name Activity                         | Category Activity                            | Emission Source                       | Emission Factor (EPA) | Unit            | GWP   | GHG Type | Quantity Source Emissions             | Total Calculation                   |
| ------------------------------------- | -------------------------------------------- | ------------------------------------- | --------------------- | --------------- | ----- | -------- | ------------------------------------- | ----------------------------------- |
| T&D losses - Headquarters electricity | Fuel & Energy-Related Activities (Scope 3.3) | Grid electricity lost in transmission | 0.396                 | kg CO2e/kWh     | 1     | CO2e     | 450,000 kWh × 4.5% = 20,250 kWh       | 20,250 × 0.396 = 8,019 kg CO2e      |
| T&D losses - Warehouse electricity    | Fuel & Energy-Related Activities (Scope 3.3) | Grid electricity lost in transmission | 0.396                 | kg CO2e/kWh     | 1     | CO2e     | 800,000 kWh × 4.5% = 36,000 kWh       | 36,000 × 0.396 = 14,256 kg CO2e     |
| T&D losses - Testing lab electricity  | Fuel & Energy-Related Activities (Scope 3.3) | Grid electricity lost in transmission | 0.396                 | kg CO2e/kWh     | 1     | CO2e     | 125,000 kWh × 4.5% = 5,625 kWh        | 5,625 × 0.396 = 2,228 kg CO2e       |
| **Total T&D Losses**                  | **Scope 3.3**                                | **Grid electricity losses**           | **0.396**             | **kg CO2e/kWh** | **1** | **CO2e** | **1,375,000 kWh × 4.5% = 61,875 kWh** | **61,875 × 0.396 = 24,503 kg CO2e** |



### Category 4: Upstream Transportation and Distribution

| Question                                                     | Scope | Category           | Input Type               | Data Type                             | Example Answer                                        |
| ------------------------------------------------------------ | ----- | ------------------ | ------------------------ | ------------------------------------- | ----------------------------------------------------- |
| How are ATMs shipped from manufacturers to your warehouses?  | 3     | Upstream Transport | Qualitative/Quantitative | Mode, distance, weight                | Sea freight from Asia: 8,000 km, 1,520 tonnes/year    |
| What is the average distance and mode for inbound spare parts shipments? | 3     | Upstream Transport | Quantitative             | Tonne-km by mode                      | Air freight: 250,000 tonne-km; Road: 450,000 tonne-km |
| Do you use third-party logistics providers? What data do they provide? | 3     | Upstream Transport | Qualitative/Quantitative | Emissions reports or fuel consumption | DHL reports 125 tCO2e for our account annually        |



# ATM Shipping Emissions from Manufacturers to Warehouses

## Scenario: International ATM Distributor importing from Asian manufacturers to ID warehouses

### Shipping Route Details:

- Origin: Manufacturing facilities in China/South Korea
- Destination: Distribution warehouses in ID
- Annual volume: 4,300 ATM units
- Average weight per ATM: 380 kg (0.38 tonnes)
- Total annual shipping weight: 1,634 tonnes

## Emissions Calculation Table

| Name Activity                               | Category Activity       | Emission Source                | Emission Factor (EPA) | Unit                   | GWP   | GHG Type | Quantity Source Emissions                     | Total Calculation                       |
| ------------------------------------------- | ----------------------- | ------------------------------ | --------------------- | ---------------------- | ----- | -------- | --------------------------------------------- | --------------------------------------- |
| Ocean Freight - Transpacific                | Upstream Transportation | Container Ship Fuel Combustion | 0.0087                | kg CO2e/tonne-km       | 1     | CO2      | 1,634 tonnes × 9,000 km = 14,706,000 tonne-km | 14,706,000 × 0.0087 = 127,942 kg CO2e   |
| Port x - Origin                             | Upstream Transportation | Heavy-Duty Truck               | 0.0674                | kg CO2e/tonne-km       | 1     | CO2      | 1,634 tonnes × 50 km = 81,700 tonne-km        | 81,700 × 0.0674 = 5,507 kg CO2e         |
| Port x - Destination                        | Upstream Transportation | Heavy-Duty Truck               | 0.0674                | kg CO2e/tonne-km       | 1     | CO2      | 1,634 tonnes × 75 km = 122,550 tonne-km       | 122,550 × 0.0674 = 8,260 kg CO2e        |
| Inland Rail Transport                       | Upstream Transportation | Freight Rail                   | 0.0209                | kg CO2e/tonne-km       | 1     | CO2      | 1,634 tonnes × 2,500 km = 4,085,000 tonne-km  | 4,085,000 × 0.0209 = 85,377 kg CO2e     |
| Final Truck Delivery                        | Upstream Transportation | Medium-Duty Truck              | 0.0894                | kg CO2e/tonne-km       | 1     | CO2      | 1,634 tonnes × 150 km = 245,100 tonne-km      | 245,100 × 0.0894 = 21,912 kg CO2e       |
| Refrigerant Leakage (if climate-controlled) | Upstream Transportation | R-134a Refrigerant             | 1,430                 | kg CO2e/kg refrigerant | 1,430 | HFC      | 2 kg leakage per container × 25 containers    | 2 × 25 × 1,430 = 71,500 kg CO2e         |
| **Total Annual Emissions**                  |                         |                                |                       |                        |       |          |                                               | **320,498 kg CO2e (320.5 tonnes CO2e)** |

## Alternative Shipping Scenarios

### Air Freight (Express Delivery for Urgent Orders)

| Name Activity                    | Category Activity       | Emission Source          | Emission Factor (EPA) | Unit             | GWP  | GHG Type | Quantity Source Emissions                   | Total Calculation                     |
| -------------------------------- | ----------------------- | ------------------------ | --------------------- | ---------------- | ---- | -------- | ------------------------------------------- | ------------------------------------- |
| Air Cargo - International        | Upstream Transportation | Aircraft Fuel Combustion | 0.543                 | kg CO2e/tonne-km | 1    | CO2      | 200 tonnes × 11,000 km = 2,200,000 tonne-km | 2,200,000 × 0.543 = 1,194,600 kg CO2e |
| Ground Transport to/from Airport | Upstream Transportation | Heavy-Duty Truck         | 0.0674                | kg CO2e/tonne-km | 1    | CO2      | 200 tonnes × 100 km = 20,000 tonne-km       | 20,000 × 0.0674 = 1,348 kg CO2e       |

### Domestic Shipping (ID Manufacturers)

| Name Activity      | Category Activity       | Emission Source  | Emission Factor (EPA) | Unit             | GWP  | GHG Type | Quantity Source Emissions                  | Total Calculation                   |
| ------------------ | ----------------------- | ---------------- | --------------------- | ---------------- | ---- | -------- | ------------------------------------------ | ----------------------------------- |
| Long-Haul Trucking | Upstream Transportation | Heavy-Duty Truck | 0.0674                | kg CO2e/tonne-km | 1    | CO2      | 500 tonnes × 2,000 km = 1,000,000 tonne-km | 1,000,000 × 0.0674 = 67,400 kg CO2e |
| Rail Transport     | Upstream Transportation | Freight Rail     | 0.0209                | kg CO2e/tonne-km | 1    | CO2      | 500 tonnes × 3,000 km = 1,500,000 tonne-km | 1,500,000 × 0.0209 = 31,350 kg CO2e |





### Category 5: Waste Generated in Operations

| Question                                                     | Scope | Category | Input Type   | Data Type                                | Example Answer                                            |
| ------------------------------------------------------------ | ----- | -------- | ------------ | ---------------------------------------- | --------------------------------------------------------- |
| How much packaging waste is generated from inbound ATM shipments? | 3     | Waste    | Quantitative | Tonnes by waste type and disposal method | Cardboard: 85 tonnes recycled; Wood: 120 tonnes recycled  |
| What happens to damaged ATMs or components that cannot be distributed? | 3     | Waste    | Quantitative | Units and disposal method                | 45 ATMs/year sent for refurbishment; 12 scrapped          |
| How much electronic waste is generated from testing operations? | 3     | Waste    | Quantitative | kg by component type                     | Circuit boards: 450 kg/year to certified e-waste recycler |

### Category 6: Business Travel

| Question                                                     | Scope | Category        | Input Type   | Data Type                        | Example Answer                                         |
| ------------------------------------------------------------ | ----- | --------------- | ------------ | -------------------------------- | ------------------------------------------------------ |
| What is the total distance traveled by employees for business purposes? | 3     | Business Travel | Quantitative | Passenger-km by mode             | Air: 2.5 million km; Rail: 150,000 km; Car: 200,000 km |
| How many employees travel for ATM installation support or training? | 3     | Business Travel | Quantitative | Number of trips and destinations | 450 installation support trips/year, average 500 km    |

### Category 7: Employee Commuting

| Question                                                    | Scope | Category           | Input Type   | Data Type                      | Example Answer                                               |
| ----------------------------------------------------------- | ----- | ------------------ | ------------ | ------------------------------ | ------------------------------------------------------------ |
| How many employees work at each facility?                   | 3     | Employee Commuting | Quantitative | Headcount by location          | HQ: 125 employees; Warehouse: 85 employees                   |
| What is the average commute distance and mode split?        | 3     | Employee Commuting | Quantitative | km and percentage by mode      | Average 25 km one-way; 70% car, 20% public transit, 10% other |
| Do you offer any remote work options that reduce commuting? | 3     | Employee Commuting | Quantitative | Percentage of remote work days | 40% hybrid schedule (2 days remote/week)                     |

### Category 8: Upstream Leased Assets

| Question                                                     | Scope | Category      | Input Type   | Data Type                  | Example Answer                                               |
| ------------------------------------------------------------ | ----- | ------------- | ------------ | -------------------------- | ------------------------------------------------------------ |
| Do you lease any warehouses or vehicles not included in Scope 1&2? | 3     | Leased Assets | Quantitative | Area or number, energy use | 2 overflow warehouses: 3,000 m² total, landlord-controlled utilities |

### Category 9: Downstream Transportation and Distribution

| Question                                                     | Scope | Category             | Input Type   | Data Type                     | Example Answer                                          |
| ------------------------------------------------------------ | ----- | -------------------- | ------------ | ----------------------------- | ------------------------------------------------------- |
| How are ATMs delivered from your warehouses to bank locations? | 3     | Downstream Transport | Quantitative | Tonne-km by mode and distance | Third-party trucks: 2.8 million tonne-km/year           |
| What is the average delivery distance to customer sites?     | 3     | Downstream Transport | Quantitative | km per delivery               | Average 180 km per ATM delivery                         |
| Do you track fuel efficiency of third-party delivery contractors? | 3     | Downstream Transport | Quantitative | L/100km or mpg                | Contract requires min 8.5 L/100km for delivery trucks   |
| How many service calls require transportation to ATM locations? | 3     | Downstream Transport | Quantitative | Number of trips and distance  | 8,500 maintenance visits/year, average 75 km round trip |

### Category 10: Processing of Sold Products

| Question                                                   | Scope | Category   | Input Type  | Data Type             | Example Answer                                     |
| ---------------------------------------------------------- | ----- | ---------- | ----------- | --------------------- | -------------------------------------------------- |
| Do banks perform any modifications to ATMs after delivery? | 3     | Processing | Qualitative | Type of modifications | Minimal - only software customization and branding |

### Category 11: Use of Sold Products

| Question                                                     | Scope | Category  | Input Type               | Data Type                          | Example Answer                                         |
| ------------------------------------------------------------ | ----- | --------- | ------------------------ | ---------------------------------- | ------------------------------------------------------ |
| What is the average power consumption of ATMs during operation? | 3     | Use Phase | Quantitative             | Watts or kWh per year per unit     | 350W continuous, ~3,066 kWh/year per ATM               |
| What is the expected operational lifetime of distributed ATMs? | 3     | Use Phase | Quantitative             | Years                              | 7-10 years depending on model and usage                |
| How many ATMs are currently in operation from your distributions? | 3     | Use Phase | Quantitative             | Total installed base               | 45,000 active units in the field                       |
| Do you provide power-saving features or settings?            | 3     | Use Phase | Qualitative/Quantitative | Description and savings percentage | Sleep mode reduces consumption by 40% during off-peak  |
| What percentage of ATMs are installed in climate-controlled vs. outdoor locations? | 3     | Use Phase | Quantitative             | Percentage split                   | 75% indoor (bank branches), 25% outdoor (kiosks)       |
| Do you track regional grid factors where ATMs are deployed?  | 3     | Use Phase | Quantitative             | kg CO2e/kWh by region              | Mapped to 15 different grid regions across the country |

### Category 12: End-of-Life Treatment of Sold Products

| Question                                                     | Scope | Category    | Input Type               | Data Type                   | Example Answer                                       |
| ------------------------------------------------------------ | ----- | ----------- | ------------------------ | --------------------------- | ---------------------------------------------------- |
| What is your take-back or recycling program for old ATMs?    | 3     | End-of-Life | Qualitative/Quantitative | Program details and volumes | Take-back program: 3,200 units/year collected        |
| What is the typical material recovery rate from ATM recycling? | 3     | End-of-Life | Quantitative             | Percentage by material      | Steel: 95% recovery; Electronics: 85%; Plastics: 60% |
| How are data security and component destruction handled?     | 3     | End-of-Life | Qualitative              | Process description         | Certified data destruction for all storage devices   |
| What percentage of end-of-life ATMs are refurbished vs. recycled? | 3     | End-of-Life | Quantitative             | Percentage split            | 30% refurbished for resale, 70% recycled             |

### Category 13: Downstream Leased Assets

| Question                                                | Scope | Category      | Input Type   | Data Type                      | Example Answer                     |
| ------------------------------------------------------- | ----- | ------------- | ------------ | ------------------------------ | ---------------------------------- |
| Do you lease ATMs to any customers rather than selling? | 3     | Leased Assets | Quantitative | Number of units and energy use | 2,500 units under operating leases |

### Category 14: Franchises

| Question                                                 | Scope | Category   | Input Type  | Data Type      | Example Answer                 |
| -------------------------------------------------------- | ----- | ---------- | ----------- | -------------- | ------------------------------ |
| Do you operate through any franchise or dealer networks? | 3     | Franchises | Qualitative | Not applicable | N/A - Direct distribution only |

### Category 15: Investments

| Question                                                     | Scope | Category    | Input Type   | Data Type                  | Example Answer                                              |
| ------------------------------------------------------------ | ----- | ----------- | ------------ | -------------------------- | ----------------------------------------------------------- |
| Do you have joint ventures or investments in ATM-related businesses? | 3     | Investments | Quantitative | Equity share and emissions | 40% stake in ATM servicing company (250 tCO2e proportional) |

## Additional Technical Data Requirements

| Question                                                    | Scope | Category     | Input Type  | Data Type                     | Example Answer                                               |
| ----------------------------------------------------------- | ----- | ------------ | ----------- | ----------------------------- | ------------------------------------------------------------ |
| What emission factors database do you use for calculations? | All   | Methodology  | Qualitative | Database name and version     | DEFRA 2024, EPA eGRID 2023, Ecoinvent 3.9                    |
| Do you have ISO 14064 or GHG Protocol verification?         | All   | Verification | Qualitative | Certification details         | ISO 14064-1 verified by SGS for 2025 inventory               |
| What is your inventory boundary and consolidation approach? | All   | Methodology  | Qualitative | Operational or equity control | Operational control for all majority-owned entities          |
| How do you handle data gaps or estimates?                   | All   | Data Quality | Qualitative | Methodology description       | Industry averages for <5% of Scope 3 where supplier data unavailable |
| What is your base year for emissions tracking?              | All   | Methodology  | Qualitative | Year and recalculation policy | 2020 base year, recalculate if >5% change from acquisitions  |







# Notes

Buat Target Jangka Pendek 10% dengan timeline dua tahun, tambahkan catatan tambahan
"Belum Memenuhi Standar Metodologi, Naikkan target reduksi agar sesuai standar."



Fitur Delete Target Reduction.

Fittur Delete Company Boundary
