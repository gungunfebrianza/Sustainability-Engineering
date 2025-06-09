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



---



## Scope 2 - Indirect Emissions from Purchased Energy

| Question                                                     | Scope | Category                     | Input Type               | Data Type                | Example Answer                                              |
| ------------------------------------------------------------ | ----- | ---------------------------- | ------------------------ | ------------------------ | ----------------------------------------------------------- |
| What is the total electricity consumption at all company-operated facilities? | 2     | Purchased Electricity        | Quantitative             | kWh per year by location | Headquarters: 450,000 kWh/year; Warehouse: 800,000 kWh/year |
| Do you track electricity consumption for ATM testing/quality control operations? | 2     | Purchased Electricity        | Quantitative             | kWh per year             | ATM testing lab: 125,000 kWh/year                           |
| What percentage of your electricity comes from renewable sources or RECs? | 2     | Purchased Electricity        | Quantitative             | Percentage and MWh       | 30% renewable (375,000 kWh from solar PPA)                  |
| Do you purchase any steam, heating, or cooling from external suppliers? | 2     | Purchased Heat/Steam/Cooling | Quantitative             | GJ or MWh per year       | District cooling: 250 MWh/year for data center              |
| What are the grid emission factors for each facility location? | 2     | Purchased Electricity        | Qualitative/Quantitative | kg CO2e/kWh by region    | Texas facility: 0.396 kg CO2e/kWh                           |

## Scope 3 - Value Chain Emissions

### Category 1: Purchased Goods and Services

| Question                                                     | Scope | Category        | Input Type               | Data Type                         | Example Answer                                               |
| ------------------------------------------------------------ | ----- | --------------- | ------------------------ | --------------------------------- | ------------------------------------------------------------ |
| How many ATM units do you purchase annually from manufacturers? | 3     | Purchased Goods | Quantitative             | Units by model type               | NCR SelfServ: 2,500 units; Diebold DN: 1,800 units           |
| What is the average weight and material composition of ATMs you distribute? | 3     | Purchased Goods | Quantitative             | kg by material type               | Average 380 kg: Steel 65%, Electronics 20%, Plastic 10%, Other 5% |
| Do you have supplier-specific emission factors or EPDs for ATM manufacturing? | 3     | Purchased Goods | Qualitative/Quantitative | kg CO2e per unit or EPD documents | NCR provides 1,250 kg CO2e/unit cradle-to-gate               |
| What spare parts and components do you stock for maintenance? | 3     | Purchased Goods | Quantitative             | Annual spend or units by category | Card readers: 5,000 units/year; Displays: 2,000 units/year   |
| What packaging materials do you purchase for ATM shipping?   | 3     | Purchased Goods | Quantitative             | kg or units by material type      | Wooden crates: 450 tonnes/year; Foam: 25 tonnes/year         |

### Category 2: Capital Goods

| Question                                                     | Scope | Category      | Input Type   | Data Type                           | Example Answer                                       |
| ------------------------------------------------------------ | ----- | ------------- | ------------ | ----------------------------------- | ---------------------------------------------------- |
| What major equipment was purchased for warehouses/testing facilities? | 3     | Capital Goods | Quantitative | Cost and type of equipment          | 5 forklifts ($250,000), Testing equipment ($500,000) |
| Did you construct or renovate any facilities in the reporting year? | 3     | Capital Goods | Quantitative | Square meters and construction type | New 5,000 m² warehouse expansion                     |

### Category 3: Fuel and Energy Related Activities

| Question                                                     | Scope | Category        | Input Type   | Data Type                         | Example Answer                                       |
| ------------------------------------------------------------ | ----- | --------------- | ------------ | --------------------------------- | ---------------------------------------------------- |
| What are the upstream emissions for fuel used in company vehicles? | 3     | Fuel and Energy | Quantitative | Calculated from Scope 1 fuel use  | Well-to-tank: 15% additional on combustion emissions |
| What are the T&D losses for purchased electricity?           | 3     | Fuel and Energy | Quantitative | Percentage of Scope 2 electricity | 4.5% grid losses on 1,375,000 kWh                    |

### Category 4: Upstream Transportation and Distribution

| Question                                                     | Scope | Category           | Input Type               | Data Type                             | Example Answer                                        |
| ------------------------------------------------------------ | ----- | ------------------ | ------------------------ | ------------------------------------- | ----------------------------------------------------- |
| How are ATMs shipped from manufacturers to your warehouses?  | 3     | Upstream Transport | Qualitative/Quantitative | Mode, distance, weight                | Sea freight from Asia: 8,000 km, 1,520 tonnes/year    |
| What is the average distance and mode for inbound spare parts shipments? | 3     | Upstream Transport | Quantitative             | Tonne-km by mode                      | Air freight: 250,000 tonne-km; Road: 450,000 tonne-km |
| Do you use third-party logistics providers? What data do they provide? | 3     | Upstream Transport | Qualitative/Quantitative | Emissions reports or fuel consumption | DHL reports 125 tCO2e for our account annually        |

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
