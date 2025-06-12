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
