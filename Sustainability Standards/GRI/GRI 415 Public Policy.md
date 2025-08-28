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

# GRI 415: Public Policy  

## Management Approach and Governance

| Question                                                     | Question Type | Input Type    | Data Type   | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | ----------- | ------------------------------------------------------------ |
| Does your organization have a formal public policy engagement strategy or framework? | Closed        | Single Select | Boolean     | Yes                                                          |
| Who has ultimate responsibility for public policy decisions within your organization? | Open          | Text Area     | String      | Chief Executive Officer and Board of Directors               |
| How frequently does your board review public policy positions and political contributions? | Closed        | Single Select | Categorical | Quarterly                                                    |
| What is the total budget allocated for public policy activities in the reporting period? | Open          | Number Input  | Currency    | $2,500,000 USD                                               |
| Does your organization publicly disclose its political spending and lobbying activities? | Closed        | Single Select | Boolean     | Yes                                                          |
| What geographic regions does your public policy engagement cover? | Closed        | Multi-Select  | Array       | ["North America", "European Union", "Asia-Pacific"]          |
| How does your organization ensure public policy positions align with stated values and ESG commitments? | Open          | Text Area     | String      | Regular review by ESG committee and stakeholder consultation |
| What mechanisms exist for stakeholder input on public policy positions? | Open          | Text Area     | String      | Annual stakeholder surveys and public consultation periods   |

## Political Contributions (GRI 415-1)

### Direct Political Contributions

| Question                                                     | Question Type | Input Type   | Data Type | Example Answer |
| ------------------------------------------------------------ | ------------- | ------------ | --------- | -------------- |
| What was the total monetary value of political contributions made directly by your organization? | Open          | Number Input | Currency  | $150,000 USD   |
| How many individual political candidates received direct contributions from your organization? | Open          | Number Input | Integer   | 12             |
| What was the total value of contributions to political parties? | Open          | Number Input | Currency  | $75,000 USD    |
| What was the total value of contributions to political action committees (PACs)? | Open          | Number Input | Currency  | $200,000 USD   |
| What was the total value of contributions to ballot measure campaigns? | Open          | Number Input | Currency  | $50,000 USD    |
| What was the total value of contributions to trade associations for political purposes? | Open          | Number Input | Currency  | $125,000 USD   |
| What was the total value of contributions to tax-exempt groups (e.g., 501(c)(4)) for political purposes? | Open          | Number Input | Currency  | $80,000 USD    |
| What was the total value of other political expenditures not captured above? | Open          | Number Input | Currency  | $25,000 USD    |

### Contribution Recipients and Details

| Question                                                     | Question Type | Input Type  | Data Type        | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ----------- | ---------------- | ------------------------------------------------------------ |
| Please provide details of contributions to individual candidates over $1,000 | Open          | Table Input | Array of Objects | [{"candidate": "Jane Smith", "office": "Governor", "amount": 5000, "jurisdiction": "California"}] |
| Please provide details of contributions to political parties | Open          | Table Input | Array of Objects | [{"party": "Democratic Party", "jurisdiction": "Federal", "amount": 25000}] |
| Please provide details of contributions to PACs over $5,000  | Open          | Table Input | Array of Objects | [{"pac_name": "Energy Future PAC", "amount": 15000, "focus_area": "Energy Policy"}] |
| Which ballot measures or referendums did your organization support financially? | Open          | Table Input | Array of Objects | [{"measure": "Proposition 15", "jurisdiction": "California", "position": "Support", "amount": 25000}] |
| What trade associations received political contributions and for what purposes? | Open          | Table Input | Array of Objects | [{"association": "National Manufacturing Association", "amount": 50000, "purpose": "Trade policy advocacy"}] |

### In-Kind Political Contributions

| Question                                                     | Question Type | Input Type    | Data Type | Example Answer |
| ------------------------------------------------------------ | ------------- | ------------- | --------- | -------------- |
| What was the total estimated value of in-kind political contributions? | Open          | Number Input  | Currency  | $75,000 USD    |
| Did your organization provide office space, equipment, or facilities for political activities? | Closed        | Single Select | Boolean   | Yes            |
| What was the estimated value of office space or facilities provided? | Open          | Number Input  | Currency  | $25,000 USD    |
| Did your organization provide staff time for political activities during work hours? | Closed        | Single Select | Boolean   | No             |
| What was the estimated value of staff time contributed to political activities? | Open          | Number Input  | Currency  | $0 USD         |
| Did your organization provide goods or services at below-market rates for political purposes? | Closed        | Single Select | Boolean   | Yes            |
| What was the estimated value of goods or services provided below market rate? | Open          | Number Input  | Currency  | $15,000 USD    |

## Lobbying Activities and Expenditures

### Lobbying Scope and Structure

| Question                                                     | Question Type | Input Type    | Data Type | Example Answer                                 |
| ------------------------------------------------------------ | ------------- | ------------- | --------- | ---------------------------------------------- |
| Does your organization engage in direct lobbying activities? | Closed        | Single Select | Boolean   | Yes                                            |
| What was the total amount spent on lobbying activities?      | Open          | Number Input  | Currency  | $1,200,000 USD                                 |
| How many registered lobbyists does your organization employ or contract? | Open          | Number Input  | Integer   | 8                                              |
| What was the total compensation paid to external lobbying firms? | Open          | Number Input  | Currency  | $800,000 USD                                   |
| What was the total internal cost of lobbying activities (staff salaries, travel, etc.)? | Open          | Number Input  | Currency  | $400,000 USD                                   |
| Which government levels does your organization lobby?        | Closed        | Multi-Select  | Array     | ["Federal", "State", "Local", "International"] |
| How many jurisdictions did your organization lobby in during the reporting period? | Open          | Number Input  | Integer   | 15                                             |

### Lobbying Issues and Positions

| Question                                                     | Question Type | Input Type   | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------ | --------- | ------------------------------------------------------------ |
| What are the primary policy issues your organization lobbied on? | Closed        | Multi-Select | Array     | ["Climate Policy", "Tax Reform", "Trade Policy", "Labor Relations"] |
| Please describe your organization's position on climate change legislation | Open          | Text Area    | String    | Support for market-based carbon pricing mechanisms and clean energy incentives |
| Please describe your organization's position on tax policy   | Open          | Text Area    | String    | Support for competitive corporate tax rates and R&D tax credits |
| Please describe your organization's position on trade policy | Open          | Text Area    | String    | Support for free trade agreements and reduced tariffs on raw materials |
| Please describe your organization's position on labor and employment policy | Open          | Text Area    | String    | Support for flexible workforce policies and skills-based training programs |
| Please describe your organization's position on environmental regulations | Open          | Text Area    | String    | Support for science-based, cost-effective environmental standards |
| Please describe your organization's position on financial services regulation | Open          | Text Area    | String    | Support for balanced regulation that ensures stability while promoting innovation |

### Lobbying Contacts and Meetings

| Question                                                     | Question Type | Input Type    | Data Type        | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | ---------------- | ------------------------------------------------------------ |
| How many meetings did your organization have with government officials for lobbying purposes? | Open          | Number Input  | Integer          | 156                                                          |
| Please provide details of significant lobbying meetings with senior officials | Open          | Table Input   | Array of Objects | [{"official": "Secretary of Energy", "date": "2024-03-15", "topic": "Clean Energy Tax Credits", "outcome": "Discussed implementation timeline"}] |
| Which government departments or agencies did your organization lobby most frequently? | Open          | Text Area     | String           | Department of Energy, Environmental Protection Agency, Treasury Department |
| Did your organization participate in formal government consultations or comment periods? | Closed        | Single Select | Boolean          | Yes                                                          |
| How many formal submissions did your organization make to government consultations? | Open          | Number Input  | Integer          | 23                                                           |

## Trade Association Memberships and Dues

### Trade Association Relationships

| Question                                                     | Question Type | Input Type    | Data Type        | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | ---------------- | ------------------------------------------------------------ |
| What was the total amount paid in trade association dues and fees? | Open          | Number Input  | Currency         | $450,000 USD                                                 |
| How many trade associations is your organization a member of? | Open          | Number Input  | Integer          | 12                                                           |
| Please list your organization's trade association memberships and annual dues | Open          | Table Input   | Array of Objects | [{"association": "American Chemistry Council", "dues": 75000, "political_portion": 15000}] |
| What portion of trade association dues was used for political activities? | Open          | Number Input  | Currency         | $85,000 USD                                                  |
| Does your organization request disclosure of how trade association dues are used? | Closed        | Single Select | Boolean          | Yes                                                          |
| Has your organization disagreed with any trade association's political positions? | Closed        | Single Select | Boolean          | Yes                                                          |
| Please describe any significant disagreements with trade association positions | Open          | Text Area     | String           | Disagreed with the Manufacturing Alliance's opposition to carbon pricing legislation |

### Trade Association Influence and Governance

| Question                                                     | Question Type | Input Type    | Data Type        | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | ---------------- | ------------------------------------------------------------ |
| Does your organization hold leadership positions in any trade associations? | Closed        | Single Select | Boolean          | Yes                                                          |
| Please list leadership positions held in trade associations  | Open          | Table Input   | Array of Objects | [{"association": "Energy Council", "position": "Board Member", "duration": "2022-2025"}] |
| Does your organization participate in trade association political strategy decisions? | Closed        | Single Select | Boolean          | Yes                                                          |
| How does your organization ensure trade association activities align with your ESG commitments? | Open          | Text Area     | String           | Regular review of association positions and voting against misaligned political activities |
| Has your organization ever withdrawn from a trade association due to political disagreements? | Closed        | Single Select | Boolean          | No                                                           |

## Other Political Expenditures

### Indirect Political Activities

| Question                                                     | Question Type | Input Type    | Data Type | Example Answer |
| ------------------------------------------------------------ | ------------- | ------------- | --------- | -------------- |
| What was spent on grassroots lobbying or advocacy campaigns? | Open          | Number Input  | Currency  | $200,000 USD   |
| What was spent on political advertising or communications?   | Open          | Number Input  | Currency  | $150,000 USD   |
| What was spent on political events, fundraisers, or conferences? | Open          | Number Input  | Currency  | $75,000 USD    |
| What was spent on think tank funding or policy research?     | Open          | Number Input  | Currency  | $100,000 USD   |
| Did your organization fund any ballot measure campaigns?     | Closed        | Single Select | Boolean   | Yes            |
| What was the total spent on ballot measure campaigns?        | Open          | Number Input  | Currency  | $50,000 USD    |
| Did your organization make any independent expenditures?     | Closed        | Single Select | Boolean   | No             |

### Political Event Participation

| Question                                                     | Question Type | Input Type    | Data Type        | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | ---------------- | ------------------------------------------------------------ |
| How many political fundraising events did your organization sponsor or attend? | Open          | Number Input  | Integer          | 8                                                            |
| What was the total cost of political event sponsorships?     | Open          | Number Input  | Currency         | $45,000 USD                                                  |
| Please describe significant political events your organization participated in | Open          | Table Input   | Array of Objects | [{"event": "Governor's Economic Summit", "cost": 15000, "purpose": "Infrastructure policy discussion"}] |
| Did your organization host any political events or fundraisers? | Closed        | Single Select | Boolean          | Yes                                                          |
| What was the total cost of political events hosted by your organization? | Open          | Number Input  | Currency         | $30,000 USD                                                  |

## Oversight and Governance Controls

### Internal Controls and Approval Processes

| Question                                                     | Question Type | Input Type    | Data Type   | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | ----------- | ------------------------------------------------------------ |
| What is the approval process for political contributions over $1,000? | Open          | Text Area     | String      | Requires approval from Government Affairs Committee and CFO  |
| What is the approval process for political contributions over $10,000? | Open          | Text Area     | String      | Requires Board of Directors approval and public disclosure   |
| How often does senior management review political spending?  | Closed        | Single Select | Categorical | Monthly                                                      |
| What controls exist to prevent unauthorized political expenditures? | Open          | Text Area     | String      | Segregation of duties, approval hierarchies, and quarterly audits |
| Does your organization have a political spending policy?     | Closed        | Single Select | Boolean     | Yes                                                          |
| When was the political spending policy last updated?         | Open          | Date Input    | Date        | 2024-01-15                                                   |
| Who is responsible for ensuring compliance with campaign finance laws? | Open          | Text Area     | String      | Chief Legal Officer and Government Affairs Director          |

### Board and Committee Oversight

| Question                                                     | Question Type | Input Type    | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | --------- | ------------------------------------------------------------ |
| Does your board have a committee that oversees political activities? | Closed        | Single Select | Boolean   | Yes                                                          |
| What is the name of the committee that oversees political activities? | Open          | Text Input    | String    | Government Affairs and Public Policy Committee               |
| How many times per year does this committee meet?            | Open          | Number Input  | Integer   | 6                                                            |
| What reports does the committee receive on political activities? | Open          | Text Area     | String    | Quarterly spending reports, annual strategy review, and compliance updates |
| Does the committee pre-approve major political expenditures? | Closed        | Single Select | Boolean   | Yes                                                          |
| What is the threshold for committee pre-approval of political spending? | Open          | Number Input  | Currency  | $25,000 USD                                                  |

## Transparency and Disclosure

### Public Disclosure Practices

| Question                                                     | Question Type | Input Type    | Data Type   | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | ----------- | ------------------------------------------------------------ |
| Does your organization publicly disclose political contributions? | Closed        | Single Select | Boolean     | Yes                                                          |
| How frequently are political spending disclosures updated?   | Closed        | Single Select | Categorical | Quarterly                                                    |
| Where are political spending disclosures published?          | Closed        | Multi-Select  | Array       | ["Company Website", "SEC Filings", "Sustainability Report"]  |
| What level of detail is provided in public political spending disclosures? | Open          | Text Area     | String      | Recipient name, amount, date, and purpose for all contributions over $1,000 |
| Does your organization disclose trade association political spending separately? | Closed        | Single Select | Boolean     | Yes                                                          |
| Are lobbying expenditures disclosed beyond legal requirements? | Closed        | Single Select | Boolean     | Yes                                                          |
| Does your organization provide explanations for its political positions? | Closed        | Single Select | Boolean     | Yes                                                          |

### Stakeholder Communication

| Question                                                     | Question Type | Input Type    | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | --------- | ------------------------------------------------------------ |
| How does your organization communicate political positions to stakeholders? | Closed        | Multi-Select  | Array     | ["Annual Report", "Website", "Stakeholder Meetings", "Press Releases"] |
| Does your organization engage with shareholders on political spending? | Closed        | Single Select | Boolean   | Yes                                                          |
| How many shareholder proposals related to political spending were received? | Open          | Number Input  | Integer   | 2                                                            |
| How did your organization vote on shareholder proposals regarding political disclosure? | Open          | Text Area     | String    | Supported enhanced disclosure proposal, opposed restriction proposal |
| Does your organization provide political spending information to proxy advisory firms? | Closed        | Single Select | Boolean   | Yes                                                          |

## Risk Management and Compliance

### Legal Compliance Framework

| Question                                                     | Question Type | Input Type    | Data Type   | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | ----------- | ------------------------------------------------------------ |
| What systems are in place to ensure compliance with campaign finance laws? | Open          | Text Area     | String      | Legal review process, compliance training, and automated monitoring systems |
| How many jurisdictions' political contribution laws must your organization comply with? | Open          | Number Input  | Integer     | 28                                                           |
| Does your organization use external counsel for political compliance? | Closed        | Single Select | Boolean     | Yes                                                          |
| How often is political compliance training provided to relevant staff? | Closed        | Single Select | Categorical | Annually                                                     |
| Have there been any violations of campaign finance laws in the reporting period? | Closed        | Single Select | Boolean     | No                                                           |
| What was the total amount of fines or penalties related to political activities? | Open          | Number Input  | Currency    | $0 USD                                                       |
| Does your organization conduct internal audits of political spending? | Closed        | Single Select | Boolean     | Yes                                                          |

### Reputational Risk Management

| Question                                                     | Question Type | Input Type    | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------- | --------- | ------------------------------------------------------------ |
| How does your organization assess reputational risks of political activities? | Open          | Text Area     | String    | Stakeholder impact analysis and media monitoring for all significant contributions |
| What criteria are used to evaluate potential political contribution recipients? | Open          | Text Area     | String    | Alignment with business interests, ethical record, and stakeholder impact |
| Has your organization ever withdrawn support from a political candidate or cause? | Closed        | Single Select | Boolean   | Yes                                                          |
| Please describe circumstances of any withdrawn political support | Open          | Text Area     | String    | Withdrew support from candidate following ethics investigation |
| How does your organization handle political activities by senior executives? | Open          | Text Area     | String    | Clear separation between personal and corporate political activities with disclosure requirements |

## Performance Metrics and Analysis

### Spending Analysis and Trends

| Question                                                     | Question Type | Input Type   | Data Type        | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------ | ---------------- | ------------------------------------------------------------ |
| How has total political spending changed compared to the previous reporting period? | Open          | Number Input | Percentage       | +15%                                                         |
| What was the percentage breakdown of political spending by type? | Open          | Table Input  | Array of Objects | [{"type": "Lobbying", "percentage": 60}, {"type": "Contributions", "percentage": 25}, {"type": "Trade Associations", "percentage": 15}] |
| What was the geographic distribution of political spending?  | Open          | Table Input  | Array of Objects | [{"region": "Federal", "percentage": 45}, {"region": "State", "percentage": 40}, {"region": "Local", "percentage": 15}] |
| Which policy issues received the most funding?               | Open          | Table Input  | Array of Objects | [{"issue": "Climate Policy", "amount": 400000}, {"issue": "Tax Policy", "amount": 300000}] |
| What is the ratio of political spending to total revenue?    | Open          | Number Input | Percentage       | 0.025%                                                       |
| What is the ratio of political spending to total lobbying budget? | Open          | Number Input | Percentage       | 85%                                                          |

### Effectiveness and Impact Assessment

| Question                                                     | Question Type | Input Type   | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------ | --------- | ------------------------------------------------------------ |
| How does your organization measure the effectiveness of political activities? | Open          | Text Area    | String    | Policy outcome tracking, stakeholder feedback, and ROI analysis |
| What key policy outcomes were achieved through political engagement? | Open          | Text Area    | String    | Support for renewable energy tax credits and infrastructure investment |
| How many pieces of favorable legislation were influenced by your organization's advocacy? | Open          | Number Input | Integer   | 3                                                            |
| What regulatory outcomes were achieved through lobbying efforts? | Open          | Text Area    | String    | Achieved regulatory clarity on emissions reporting and flexible compliance timelines |
| How does your organization evaluate return on investment for political spending? | Open          | Text Area    | String    | Cost-benefit analysis comparing spending to estimated business impact of policy outcomes |

## Future Planning and Strategy

### Strategic Planning

| Question                                                     | Question Type | Input Type   | Data Type | Example Answer                                               |
| ------------------------------------------------------------ | ------------- | ------------ | --------- | ------------------------------------------------------------ |
| What is your organization's planned political spending for the next reporting period? | Open          | Number Input | Currency  | $2,750,000 USD                                               |
| Which emerging policy issues will your organization focus on? | Closed        | Multi-Select | Array     | ["AI Regulation", "Supply Chain Resilience", "Digital Tax Policy"] |
| How is your political strategy evolving to address ESG considerations? | Open          | Text Area    | String    | Increased focus on climate policy and greater emphasis on stakeholder alignment |
| What changes are planned for political disclosure practices? | Open          | Text Area    | String    | Real-time disclosure portal and enhanced explanation of policy positions |
| How will your organization adapt to changing political landscapes? | Open          | Text Area    | String    | Diversified engagement strategy and enhanced scenario planning |
