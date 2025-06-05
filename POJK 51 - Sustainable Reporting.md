# OJK POJK No. 51 Sustainability Reporting

## Company Information & Governance

| Question                                                     | Question Type | Input Type    | Data Type  | Example Answer                       |
| ------------------------------------------------------------ | ------------- | ------------- | ---------- | ------------------------------------ |
| What is your company's full legal name?                      | Mandatory     | Text          | String     | PT Bank Mandiri (Persero) Tbk        |
| What is your company's registration number (NIB/NPWP)?       | Mandatory     | Text          | String     | 9120208140796                        |
| What type of financial institution are you?                  | Mandatory     | Single Select | Enum       | Commercial Bank                      |
| What is your company's total assets (in IDR billion)?        | Mandatory     | Number        | Decimal    | 1850.5                               |
| Does your company have a dedicated sustainability committee? | Mandatory     | Yes/No        | Boolean    | Yes                                  |
| Who is the Chief Sustainability Officer or equivalent?       | Mandatory     | Text          | String     | John Doe, Director of Sustainability |
| How many board members have sustainability expertise?        | Mandatory     | Number        | Integer    | 3                                    |
| What percentage of executive compensation is linked to sustainability targets? | Optional      | Number        | Percentage | 25%                                  |

## Environmental Management

| Question                                                     | Question Type | Input Type      | Data Type  | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | --------------- | ---------- | ------------------------------------------------------------ |
| What is your company's total energy consumption (kWh) for the reporting period? | Mandatory     | Number          | Decimal    | 45000000                                                     |
| What percentage of your energy comes from renewable sources? | Mandatory     | Number          | Percentage | 15%                                                          |
| What is your total water consumption (cubic meters) for the reporting period? | Mandatory     | Number          | Decimal    | 125000                                                       |
| What is your total waste generation (tons) for the reporting period? | Mandatory     | Number          | Decimal    | 450.5                                                        |
| What percentage of your waste is recycled?                   | Mandatory     | Number          | Percentage | 65%                                                          |
| What are your total Scope 1 GHG emissions (tCO2e)?           | Mandatory     | Number          | Decimal    | 12500.8                                                      |
| What are your total Scope 2 GHG emissions (tCO2e)?           | Mandatory     | Number          | Decimal    | 28750.3                                                      |
| Do you have Scope 3 GHG emissions data?                      | Optional      | Yes/No          | Boolean    | Yes                                                          |
| If yes, what are your total Scope 3 GHG emissions (tCO2e)?   | Conditional   | Number          | Decimal    | 156780.2                                                     |
| Do you have environmental management certification (ISO 14001)? | Optional      | Yes/No          | Boolean    | Yes                                                          |
| What environmental initiatives did you implement this year?  | Optional      | Multi-line Text | String     | LED lighting upgrade, paperless banking promotion, green building certification |

## Social Responsibility & Human Resources

| Question                                                     | Question Type | Input Type | Data Type  | Example Answer |
| ------------------------------------------------------------ | ------------- | ---------- | ---------- | -------------- |
| What is your total number of employees?                      | Mandatory     | Number     | Integer    | 45680          |
| What percentage of your employees are women?                 | Mandatory     | Number     | Percentage | 52%            |
| What percentage of your leadership positions are held by women? | Mandatory     | Number     | Percentage | 35%            |
| What is your employee turnover rate?                         | Mandatory     | Number     | Percentage | 8.5%           |
| How many hours of training did employees receive on average? | Mandatory     | Number     | Decimal    | 42.5           |
| What percentage of employees received sustainability training? | Mandatory     | Number     | Percentage | 85%            |
| Do you have a diversity and inclusion policy?                | Mandatory     | Yes/No     | Boolean    | Yes            |
| How much did you spend on employee development (IDR million)? | Optional      | Number     | Decimal    | 15750.0        |
| How many workplace safety incidents occurred?                | Mandatory     | Number     | Integer    | 12             |
| What is your employee satisfaction score (1-10)?             | Optional      | Number     | Decimal    | 8.2            |
| How much did you contribute to community development (IDR million)? | Mandatory     | Number     | Decimal    | 125000.0       |
| How many people benefited from your community programs?      | Optional      | Number     | Integer    | 50000          |

## Sustainable Finance & Products

| Question                                                     | Question Type | Input Type | Data Type  | Example Answer |
| ------------------------------------------------------------ | ------------- | ---------- | ---------- | -------------- |
| What is your total sustainable financing portfolio (IDR billion)? | Mandatory     | Number     | Decimal    | 275.8          |
| What percentage of your total loan portfolio is sustainable financing? | Mandatory     | Number     | Percentage | 18.5%          |
| How many green/sustainable products do you offer?            | Mandatory     | Number     | Integer    | 8              |
| What is your total green bond issuance (IDR billion)?        | Optional      | Number     | Decimal    | 50.0           |
| Do you apply ESG criteria in your investment decisions?      | Mandatory     | Yes/No     | Boolean    | Yes            |
| What is your exposure to high-carbon industries (IDR billion)? | Mandatory     | Number     | Decimal    | 85.2           |
| Do you have a policy to phase out fossil fuel financing?     | Optional      | Yes/No     | Boolean    | Yes            |
| How many MSME customers do you serve?                        | Mandatory     | Number     | Integer    | 125000         |
| What percentage of your customers are from underbanked communities? | Optional      | Number     | Percentage | 12%            |
| Do you offer financial literacy programs?                    | Mandatory     | Yes/No     | Boolean    | Yes            |
| How many people participated in your financial literacy programs? | Conditional   | Number     | Integer    | 25000          |

## Risk Management & Compliance

| Question                                                     | Question Type | Input Type    | Data Type  | Example Answer |
| ------------------------------------------------------------ | ------------- | ------------- | ---------- | -------------- |
| Do you conduct climate risk assessments?                     | Mandatory     | Yes/No        | Boolean    | Yes            |
| How often do you update your climate risk assessment?        | Conditional   | Single Select | Enum       | Annually       |
| Do you have ESG risk integration in credit processes?        | Mandatory     | Yes/No        | Boolean    | Yes            |
| What is your Non-Performing Loan (NPL) ratio?                | Mandatory     | Number        | Percentage | 2.8%           |
| Do you have anti-corruption policies and procedures?         | Mandatory     | Yes/No        | Boolean    | Yes            |
| How many compliance violations occurred this year?           | Mandatory     | Number        | Integer    | 3              |
| Do you conduct regular ESG supplier assessments?             | Optional      | Yes/No        | Boolean    | Yes            |
| What percentage of suppliers signed your sustainability code of conduct? | Optional      | Number        | Percentage | 78%            |
| Do you have a whistleblowing mechanism?                      | Mandatory     | Yes/No        | Boolean    | Yes            |
| How many ethics violations were reported and addressed?      | Optional      | Number        | Integer    | 8              |

## Digital Innovation & Financial Inclusion

| Question                                                     | Question Type | Input Type | Data Type  | Example Answer |
| ------------------------------------------------------------ | ------------- | ---------- | ---------- | -------------- |
| What percentage of your transactions are digital?            | Mandatory     | Number     | Percentage | 75%            |
| How many digital banking users do you have?                  | Optional      | Number     | Integer    | 8500000        |
| Do you offer mobile banking services in local languages?     | Optional      | Yes/No     | Boolean    | Yes            |
| How many rural/remote areas do you serve?                    | Mandatory     | Number     | Integer    | 1250           |
| What is your financial inclusion index score?                | Optional      | Number     | Decimal    | 7.8            |
| Do you partner with fintech companies for sustainable solutions? | Optional      | Yes/No     | Boolean    | Yes            |
| How much did you invest in digital infrastructure (IDR million)? | Optional      | Number     | Decimal    | 450000.0       |
| Do you have cybersecurity measures for customer data protection? | Mandatory     | Yes/No     | Boolean    | Yes            |

## Reporting & Transparency

| Question                                                     | Question Type | Input Type    | Data Type | Example Answer                |
| ------------------------------------------------------------ | ------------- | ------------- | --------- | ----------------------------- |
| Do you publish an annual sustainability report?              | Mandatory     | Yes/No        | Boolean   | Yes                           |
| Which sustainability reporting framework do you follow?      | Mandatory     | Multi Select  | Array     | GRI Standards, TCFD           |
| Do you have third-party assurance for your sustainability report? | Optional      | Yes/No        | Boolean   | Yes                           |
| Who provides the third-party assurance?                      | Conditional   | Text          | String    | Ernst & Young Indonesia       |
| How often do you report sustainability metrics to regulators? | Mandatory     | Single Select | Enum      | Quarterly                     |
| Do you disclose climate-related financial risks (TCFD)?      | Mandatory     | Yes/No        | Boolean   | Yes                           |
| What is your sustainability rating from external agencies?   | Optional      | Text          | String    | MSCI BBB, Sustainalytics 25.8 |
| Do you participate in sustainability indices?                | Optional      | Yes/No        | Boolean   | Yes                           |

## Performance Targets & Future Plans

| Question                                                     | Question Type | Input Type | Data Type  | Example Answer |
| ------------------------------------------------------------ | ------------- | ---------- | ---------- | -------------- |
| What is your target for renewable energy usage by 2030?      | Optional      | Number     | Percentage | 50%            |
| What is your net-zero commitment target year?                | Optional      | Number     | Integer    | 2050           |
| What is your sustainable financing target for next year (IDR billion)? | Optional      | Number     | Decimal    | 325.0          |
| Do you have science-based emissions reduction targets?       | Optional      | Yes/No     | Boolean    | Yes            |
| What is your target for women in leadership by 2025?         | Optional      | Number     | Percentage | 40%            |
| How much do you plan to invest in sustainability initiatives next year (IDR million)? | Optional      | Number     | Decimal    | 75000.0        |
| What is your financial inclusion target (number of new customers)? | Optional      | Number     | Integer    | 500000         |
| Do you have a transition plan for climate risks?             | Mandatory     | Yes/No     | Boolean    | Yes            |

## Additional Information

| Question                                               | Question Type | Input Type      | Data Type | Example Answer                                               |
| ------------------------------------------------------ | ------------- | --------------- | --------- | ------------------------------------------------------------ |
| What are your main sustainability challenges?          | Optional      | Multi-line Text | String    | Data collection across branches, measuring Scope 3 emissions, rural market penetration |
| What sustainability innovations are you most proud of? | Optional      | Multi-line Text | String    | Solar-powered ATMs, micro-credit for women entrepreneurs, paperless loan processing |
| Any additional comments or information?                | Optional      | Multi-line Text | String    | We are piloting blockchain for supply chain finance sustainability verification |

------

**Input Type Definitions:**

- **Text**: Single line text input
- **Multi-line Text**: Multiple line text area
- **Number**: Numeric input with decimal support
- **Yes/No**: Boolean checkbox or radio button
- **Single Select**: Dropdown with one choice
- **Multi Select**: Multiple choice selection
- **Conditional**: Only appears based on previous answer

**Question Type Definitions:**

- **Mandatory**: Required for OJK compliance
- **Optional**: Recommended for comprehensive reporting
- **Conditional**: Required only if previous condition is met