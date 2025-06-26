# GRI Series

**GRI 100 Series (Universal Standards)**

- GRI 101: Foundation
- GRI 102: General Disclosures
- GRI 103: Management Approach

**GRI 200 Series (Economic Standards)**

- GRI 201: Economic Performance
- GRI 202: Market Presence
- GRI 203: Indirect Economic Impacts
- GRI 204: Procurement Practices
- GRI 205: Anti-corruption
- GRI 206: Anti-competitive Behavior
- GRI 207: Tax

**GRI 300 Series (Environmental Standards)**

- GRI 301: Materials
- GRI 302: Energy
- GRI 303: Water and Effluents
- GRI 304: Biodiversity
- GRI 305: Emissions
- GRI 306: Waste
- GRI 307: Environmental Compliance
- GRI 308: Supplier Environmental Assessment

**GRI 400 Series (Social Standards)**

- GRI 401: Employment
- GRI 402: Labor/Management Relations
- GRI 403: Occupational Health and Safety
- GRI 404: Training and Education
- GRI 405: Diversity and Equal Opportunity
- GRI 406: Non-discrimination
- GRI 407: Freedom of Association and Collective Bargaining
- GRI 408: Child Labor
- GRI 409: Forced or Compulsory Labor
- GRI 410: Security Practices
- GRI 411: Rights of Indigenous Peoples
- GRI 412: Human Rights Assessment
- GRI 413: Local Communities
- GRI 414: Supplier Social Assessment
- GRI 415: Public Policy
- GRI 416: Customer Health and Safety
- GRI 417: Marketing and Labeling
- GRI 418: Customer Privacy
- GRI 419: Socioeconomic Compliance

These standards provide a comprehensive framework for sustainability reporting across economic, environmental, and social dimensions.



------

# Comprehensive GRI Questions for AI-Driven Sustainability Reporting Platform

## Foundation and General Disclosures

| Question                                                     | Question Type  | Input Type             | Data Type   | Example Answer                                               |
| ------------------------------------------------------------ | -------------- | ---------------------- | ----------- | ------------------------------------------------------------ |
| What is your organization's legal name?                      | Identification | Text Input             | String      | "Sustainable Solutions Inc."                                 |
| What is your primary business activity according to ISIC classification? | Classification | Dropdown/Search        | Categorical | "C2511 - Manufacture of structural metal products"           |
| In which countries does your organization operate?           | Geographic     | Multi-select           | Array       | ["United States", "Canada", "Mexico"]                        |
| What is your organization's ownership structure?             | Structural     | Radio Button           | Categorical | "Publicly listed company"                                    |
| How many employees does your organization have?              | Quantitative   | Number Input           | Integer     | 15,847                                                       |
| What is your reporting period?                               | Temporal       | Date Range             | Date        | "January 1, 2024 - December 31, 2024"                        |
| Who are your organization's key stakeholder groups?          | Identification | Multi-select Checklist | Array       | ["Employees", "Customers", "Investors", "Local communities"] |
| Does your organization have a formal sustainability strategy? | Binary         | Yes/No                 | Boolean     | Yes                                                          |
| What governance body has ultimate responsibility for sustainability topics? | Governance     | Dropdown               | String      | "Board of Directors"                                         |
| How often does your highest governance body review sustainability performance? | Frequency      | Dropdown               | Categorical | "Quarterly"                                                  |

## Economic Performance (GRI 200 Series)

| Question                                                     | Question Type | Input Type     | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | -------------- | --------- | ------------------------------------------------------------ |
| What was your direct economic value generated (revenues)?    | Financial     | Currency Input | Decimal   | 2,450,000,000.00                                             |
| What was your total operating costs?                         | Financial     | Currency Input | Decimal   | 1,890,000,000.00                                             |
| What were your employee wages and benefits?                  | Financial     | Currency Input | Decimal   | 356,000,000.00                                               |
| What were your payments to providers of capital?             | Financial     | Currency Input | Decimal   | 87,500,000.00                                                |
| What were your payments to government (taxes)?               | Financial     | Currency Input | Decimal   | 98,200,000.00                                                |
| What were your community investments?                        | Financial     | Currency Input | Decimal   | 12,300,000.00                                                |
| What financial implications has climate change created for your organization? | Qualitative   | Text Area      | String    | "Increased insurance costs due to extreme weather events, estimated at $2.3M annually" |
| What is your defined benefit plan obligation?                | Financial     | Currency Input | Decimal   | 145,600,000.00                                               |
| What percentage of senior management hired from local community? | Percentage    | Slider/Number  | Decimal   | 68.5                                                         |
| What is your ratio of standard entry-level wage to local minimum wage? | Ratio         | Number Input   | Decimal   | 1.35                                                         |

## Environmental Performance (GRI 300 Series)

| Question                                                     | Question Type | Input Type    | Data Type | Example Answer         |
| ------------------------------------------------------------ | ------------- | ------------- | --------- | ---------------------- |
| What was your total materials used by weight?                | Quantitative  | Number Input  | Decimal   | 145,678.5              |
| What unit of measurement do you use for materials?           | Unit          | Dropdown      | String    | "Metric tons"          |
| What percentage of materials used were recycled input materials? | Percentage    | Slider/Number | Decimal   | 23.8                   |
| What was your total energy consumption within the organization? | Quantitative  | Number Input  | Decimal   | 2,845,690              |
| What unit do you use for energy measurement?                 | Unit          | Dropdown      | String    | "Gigajoules (GJ)"      |
| What was your total fuel consumption from renewable sources? | Quantitative  | Number Input  | Decimal   | 456,789                |
| What was your total electricity consumption?                 | Quantitative  | Number Input  | Decimal   | 89,345,678             |
| What unit do you use for electricity?                        | Unit          | Dropdown      | String    | "Kilowatt-hours (kWh)" |
| What were your direct (Scope 1) GHG emissions?               | Quantitative  | Number Input  | Decimal   | 125,467.8              |
| What were your energy indirect (Scope 2) GHG emissions?      | Quantitative  | Number Input  | Decimal   | 234,589.2              |
| What were your other indirect (Scope 3) GHG emissions?       | Quantitative  | Number Input  | Decimal   | 567,892.4              |
| What was your total water withdrawal by source?              | Quantitative  | Number Input  | Decimal   | 1,234,567              |
| What unit do you use for water measurement?                  | Unit          | Dropdown      | String    | "Megaliters"           |
| What was your total water consumption?                       | Quantitative  | Number Input  | Decimal   | 987,654                |
| What was your total water discharge?                         | Quantitative  | Number Input  | Decimal   | 765,432                |
| What was your total weight of waste generated?               | Quantitative  | Number Input  | Decimal   | 45,678.9               |
| What was your total weight of waste diverted from disposal?  | Quantitative  | Number Input  | Decimal   | 34,567.2               |
| Are any of your operational sites in or adjacent to protected areas? | Binary        | Yes/No        | Boolean   | No                     |
| What is the total size of your operational sites?            | Quantitative  | Number Input  | Decimal   | 2,345.6                |
| What unit do you use for land area?                          | Unit          | Dropdown      | String    | "Hectares"             |

## Social Performance (GRI 400 Series)

| Question                                                     | Question Type   | Input Type         | Data Type | Example Answer      |
| ------------------------------------------------------------ | --------------- | ------------------ | --------- | ------------------- |
| What was your total number of new employee hires?            | Quantitative    | Number Input       | Integer   | 1,247               |
| What was your total number of employee turnover?             | Quantitative    | Number Input       | Integer   | 987                 |
| What is your employee turnover rate?                         | Percentage      | Calculated/Display | Decimal   | 6.2                 |
| How many employees took parental leave?                      | Quantitative    | Number Input       | Integer   | 234                 |
| What is your return to work rate after parental leave?       | Percentage      | Number Input       | Decimal   | 94.5                |
| What is the minimum notice period for operational changes?   | Temporal        | Number Input       | Integer   | 30                  |
| What unit do you use for notice period?                      | Unit            | Dropdown           | String    | "Days"              |
| Do you have an occupational health and safety management system? | Binary          | Yes/No             | Boolean   | Yes                 |
| What was your rate of work-related injuries?                 | Rate            | Number Input       | Decimal   | 2.34                |
| What was your rate of high-consequence work-related injuries? | Rate            | Number Input       | Decimal   | 0.12                |
| How many work-related fatalities occurred?                   | Quantitative    | Number Input       | Integer   | 0                   |
| What was the average hours of training per employee?         | Average         | Number Input       | Decimal   | 34.5                |
| What percentage of employees received regular performance reviews? | Percentage      | Slider/Number      | Decimal   | 98.7                |
| What is the percentage of women in governance bodies?        | Percentage      | Number Input       | Decimal   | 42.3                |
| What is the percentage of women in management positions?     | Percentage      | Number Input       | Decimal   | 38.9                |
| How many incidents of discrimination were reported?          | Quantitative    | Number Input       | Integer   | 3                   |
| How many discrimination incidents were resolved?             | Quantitative    | Number Input       | Integer   | 3                   |
| Are there operations at risk for child labor violations?     | Risk Assessment | Multi-select       | Array     | ["None identified"] |
| Are there operations at risk for forced labor violations?    | Risk Assessment | Multi-select       | Array     | ["None identified"] |
| What percentage of security personnel received human rights training? | Percentage      | Number Input       | Decimal   | 100.0               |
| How many operations have community engagement programs?      | Quantitative    | Number Input       | Integer   | 45                  |
| What percentage of suppliers were screened using social criteria? | Percentage      | Number Input       | Decimal   | 78.5                |
| What was your total political contributions?                 | Financial       | Currency Input     | Decimal   | 0.00                |
| What percentage of products assessed for health and safety impacts? | Percentage      | Number Input       | Decimal   | 100.0               |
| How many incidents of non-compliance with health and safety regulations? | Quantitative    | Number Input       | Integer   | 2                   |
| What percentage of products require health and safety information? | Percentage      | Number Input       | Decimal   | 85.4                |
| How many complaints regarding customer privacy breaches?     | Quantitative    | Number Input       | Integer   | 5                   |
| How many customer privacy complaints were resolved?          | Quantitative    | Number Input       | Integer   | 5                   |

## Materiality and Management Approach

| Question                                                     | Question Type   | Input Type          | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | --------------- | ------------------- | --------- | ------------------------------------------------------------ |
| How did you determine your material topics?                  | Process         | Text Area           | String    | "Through stakeholder engagement surveys, impact assessments, and board review process" |
| What are your organization's material topics?                | Multi-selection | Checklist           | Array     | ["Climate change", "Employee health and safety", "Data privacy", "Supply chain management"] |
| Where do the impacts for each material topic occur?          | Boundary        | Matrix/Grid         | Object    | {"Climate change": {"Own operations": true, "Upstream": true, "Downstream": true}} |
| Who is involved in impacts for each material topic?          | Involvement     | Matrix/Grid         | Object    | {"Employee safety": {"Own workforce": true, "Contractors": true, "Suppliers": false}} |
| How do you manage each material topic?                       | Management      | Text Area per Topic | Object    | {"Climate change": "Through our Net Zero strategy, including renewable energy procurement and efficiency programs"} |
| How do you evaluate the effectiveness of your management approach? | Evaluation      | Text Area per Topic | Object    | {"Data privacy": "Annual third-party audits and customer satisfaction surveys on data handling"} |
| What policies do you have for each material topic?           | Policy          | Text Area per Topic | Object    | {"Supply chain": "Supplier Code of Conduct requiring adherence to labor and environmental standards"} |
| What commitments have you made for each material topic?      | Commitments     | Text Area per Topic | Object    | {"Climate change": "Science-based targets for 50% emissions reduction by 2030 and net zero by 2050"} |
| What goals and targets do you have for each material topic?  | Goals           | Text Area per Topic | Object    | {"Employee safety": "Zero workplace fatalities and 20% reduction in injury rate by 2025"} |
| What actions are you taking for each material topic?         | Actions         | Text Area per Topic | Object    | {"Data privacy": "Implementation of privacy-by-design principles and staff training programs"} |

## Stakeholder Engagement

| Question                                                     | Question Type    | Input Type     | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | ---------------- | -------------- | --------- | ------------------------------------------------------------ |
| How do you identify your stakeholders?                       | Process          | Text Area      | String    | "Through stakeholder mapping exercises considering influence, dependence, and impact relationships" |
| How frequently do you engage with each stakeholder group?    | Frequency Matrix | Grid/Matrix    | Object    | {"Employees": "Monthly", "Customers": "Quarterly", "Investors": "Quarterly", "Communities": "Bi-annually"} |
| What methods do you use to engage each stakeholder group?    | Methods Matrix   | Grid/Matrix    | Object    | {"Employees": ["Surveys", "Town halls", "Focus groups"], "Customers": ["Surveys", "User panels"]} |
| What key concerns were raised by each stakeholder group?     | Concerns Matrix  | Text Area Grid | Object    | {"Employees": "Work-life balance and career development opportunities"} |
| How have you responded to stakeholder concerns?              | Response Matrix  | Text Area Grid | Object    | {"Employees": "Implemented flexible work arrangements and expanded training programs"} |
| What percentage of your workforce is covered by collective bargaining? | Percentage       | Number Input   | Decimal   | 45.8                                                         |
| Do you have a grievance mechanism for stakeholders?          | Binary           | Yes/No         | Boolean   | Yes                                                          |
| How many grievances were received through your mechanism?    | Quantitative     | Number Input   | Integer   | 23                                                           |
| How many grievances were resolved?                           | Quantitative     | Number Input   | Integer   | 21                                                           |
| What is your average time to resolve grievances?             | Temporal         | Number Input   | Integer   | 15                                                           |
| What unit do you use for grievance resolution time?          | Unit             | Dropdown       | String    | "Business days"                                              |

## Due Diligence and Risk Management

| Question                                                     | Question Type   | Input Type             | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | --------------- | ---------------------- | --------- | ------------------------------------------------------------ |
| Do you conduct human rights due diligence?                   | Binary          | Yes/No                 | Boolean   | Yes                                                          |
| How often do you conduct human rights impact assessments?    | Frequency       | Dropdown               | String    | "Every two years"                                            |
| What human rights issues have you identified in your operations? | Risk Assessment | Multi-select Checklist | Array     | ["Working hours compliance", "Freedom of association"]       |
| What human rights issues have you identified in your supply chain? | Risk Assessment | Multi-select Checklist | Array     | ["Child labor risk", "Forced labor risk"]                    |
| Do you conduct environmental due diligence?                  | Binary          | Yes/No                 | Boolean   | Yes                                                          |
| What environmental risks have you identified?                | Risk Assessment | Multi-select Checklist | Array     | ["Water scarcity", "Climate change physical risks", "Biodiversity loss"] |
| How do you monitor the effectiveness of your due diligence processes? | Monitoring      | Text Area              | String    | "Through annual audits, KPI tracking, and third-party assessments" |
| Do you have remediation processes for negative impacts?      | Binary          | Yes/No                 | Boolean   | Yes                                                          |
| How many remediation processes were initiated this reporting period? | Quantitative    | Number Input           | Integer   | 7                                                            |
| What was the total cost of remediation activities?           | Financial       | Currency Input         | Decimal   | 2,450,000.00                                                 |

## Supply Chain and Business Relationships

| Question                                                     | Question Type | Input Type   | Data Type | Example Answer |
| ------------------------------------------------------------ | ------------- | ------------ | --------- | -------------- |
| How many suppliers do you have?                              | Quantitative  | Number Input | Integer   | 2,847          |
| What percentage of suppliers are local?                      | Percentage    | Number Input | Decimal   | 34.7           |
| What percentage of procurement spending was on local suppliers? | Percentage    | Number Input | Decimal   | 28.9           |
| Do you screen suppliers for environmental criteria?          | Binary        | Yes/No       | Boolean   | Yes            |
| What percentage of suppliers were screened for environmental criteria? | Percentage    | Number Input | Decimal   | 89.3           |
| How many suppliers were assessed for environmental impacts?  | Quantitative  | Number Input | Integer   | 456            |
| How many suppliers were identified as having negative environmental impacts? | Quantitative  | Number Input | Integer   | 23             |
| Do you screen suppliers for social criteria?                 | Binary        | Yes/No       | Boolean   | Yes            |
| What percentage of suppliers were screened for social criteria? | Percentage    | Number Input | Decimal   | 91.2           |
| How many suppliers were assessed for social impacts?         | Quantitative  | Number Input | Integer   | 523            |
| How many suppliers were identified as having negative social impacts? | Quantitative  | Number Input | Integer   | 18             |
| Do you have a supplier code of conduct?                      | Binary        | Yes/No       | Boolean   | Yes            |
| What percentage of suppliers have signed your code of conduct? | Percentage    | Number Input | Decimal   | 96.8           |
| How many supplier contracts were terminated due to ESG concerns? | Quantitative  | Number Input | Integer   | 5              |

## Innovation and Future-Oriented Metrics

| Question                                                     | Question Type      | Input Type     | Data Type | Example Answer                    |
| ------------------------------------------------------------ | ------------------ | -------------- | --------- | --------------------------------- |
| What percentage of revenue comes from sustainable products/services? | Percentage         | Number Input   | Decimal   | 42.8                              |
| What was your R&D investment in sustainability innovation?   | Financial          | Currency Input | Decimal   | 45,600,000.00                     |
| How many sustainability-related patents do you hold?         | Quantitative       | Number Input   | Integer   | 127                               |
| What percentage of products are designed for circular economy principles? | Percentage         | Number Input   | Decimal   | 78.4                              |
| Do you have science-based targets?                           | Binary             | Yes/No         | Boolean   | Yes                               |
| What is your target year for achieving net-zero emissions?   | Temporal           | Year Input     | Integer   | 2050                              |
| What percentage progress have you made toward your emissions reduction target? | Percentage         | Number Input   | Decimal   | 34.7                              |
| Do you conduct scenario analysis for climate risks?          | Binary             | Yes/No         | Boolean   | Yes                               |
| What climate scenarios do you use for analysis?              | Scenario Selection | Multi-select   | Array     | ["RCP 2.6", "RCP 4.5", "RCP 8.5"] |
| What is your estimated financial impact from climate risks?  | Financial          | Currency Input | Decimal   | 125,000,000.00                    |
| What is your estimated financial opportunity from climate action? | Financial          | Currency Input | Decimal   | 89,500,000.00                     |

## Assurance and Verification

| Question                                                     | Question Type   | Input Type   | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | --------------- | ------------ | --------- | ------------------------------------------------------------ |
| Do you obtain external assurance for your sustainability report? | Binary          | Yes/No       | Boolean   | Yes                                                          |
| What type of assurance do you obtain?                        | Selection       | Radio Button | String    | "Limited assurance"                                          |
| Which assurance standard is used?                            | Selection       | Dropdown     | String    | "ISAE 3000"                                                  |
| Who provides your external assurance?                        | Identification  | Text Input   | String    | "PricewaterhouseCoopers LLP"                                 |
| Which metrics/indicators are covered by external assurance?  | Multi-selection | Checklist    | Array     | ["GHG emissions", "Energy consumption", "Water usage", "Waste generation"] |
| Do you have internal assurance processes?                    | Binary          | Yes/No       | Boolean   | Yes                                                          |
| How often do you conduct internal audits of sustainability data? | Frequency       | Dropdown     | String    | "Quarterly"                                                  |
| What data quality control measures do you have in place?     | Quality Control | Multi-select | Array     | ["Automated validation", "Management review", "Third-party verification"] |

------

**Note**: This table represents a comprehensive collection of questions that would be essential for any GRI-compliant AI-driven sustainability reporting platform. The questions cover all major GRI standards and are designed to capture both quantitative metrics and qualitative disclosures required for comprehensive sustainability reporting.
