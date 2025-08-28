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

# GRI 416: Customer Health and Safety  

## Management Approach Questions

| Question                                                     | Question Type          | Input Type                                      | Data Type          | Example Answer                                               |
| ------------------------------------------------------------ | ---------------------- | ----------------------------------------------- | ------------------ | ------------------------------------------------------------ |
| What is your organization's policy on customer health and safety? | Policy/Strategy        | Text Editor with Rich Formatting                | String (Long Text) | "Our Customer Health & Safety Policy commits to zero harm through rigorous product testing, transparent labeling, and continuous monitoring of health impacts across all product categories." |
| Who is responsible for customer health and safety at the organizational level? | Governance             | Single Select + Text                            | String             | "Chief Quality Officer, supported by Product Safety Committee with representatives from R&D, Legal, and Operations" |
| What customer health and safety management systems do you have in place? | Management System      | Multiple Select + Text                          | Array of Strings   | ["ISO 22000 Food Safety Management", "HACCP Implementation", "Product Liability Insurance Program", "Customer Complaint Tracking System"] |
| How do you identify customer health and safety risks in your products/services? | Risk Assessment        | Text Editor + File Upload                       | String + File      | "We conduct comprehensive risk assessments using FMEA methodology, third-party laboratory testing, and consumer usage studies. See attached Risk Assessment Protocol." |
| What are your customer health and safety objectives and targets for the reporting period? | Objectives/Targets     | Structured Form (Objective + Target + Timeline) | JSON Object        | {"objective": "Reduce product-related health incidents", "target": "Zero Class I recalls", "timeline": "2024-2025", "status": "On track"} |
| How do you engage with customers regarding health and safety matters? | Stakeholder Engagement | Multiple Select + Text                          | Array + String     | ["Customer advisory panels", "Social media monitoring", "Direct feedback channels", "Regular surveys on safety perceptions"] |
| What training do employees receive on customer health and safety? | Training/Capacity      | Structured Form                                 | JSON Array         | [{"department": "R&D", "training": "Product Safety Design", "hours": 40, "frequency": "Annual", "completion_rate": 98}] |
| How do you monitor and evaluate customer health and safety performance? | Monitoring/Evaluation  | Text Editor + Metrics Input                     | String + Numerical | "Monthly safety metrics review, quarterly customer satisfaction surveys, annual third-party safety audits. Key metrics: incident rate, response time, customer satisfaction score." |

## GRI 416-1: Assessment of Health and Safety Impacts of Product and Service Categories

| Question                                                     | Question Type            | Input Type                             | Data Type        | Example Answer                                               |
| ------------------------------------------------------------ | ------------------------ | -------------------------------------- | ---------------- | ------------------------------------------------------------ |
| What percentage of significant product and service categories have been assessed for health and safety impacts? | Quantitative             | Number Input (Percentage)              | Float            | 95.5                                                         |
| List all significant product and service categories in your organization | Product Classification   | Dynamic List with Categories           | Array of Objects | [{"category": "Pharmaceuticals", "revenue_share": 45, "assessed": true}, {"category": "Medical Devices", "revenue_share": 35, "assessed": true}] |
| For each product category, has a health and safety impact assessment been conducted? | Assessment Status        | Table Input (Category + Yes/No + Date) | Array of Objects | [{"category": "Food Products", "assessed": true, "assessment_date": "2024-03-15", "assessor": "External Lab", "certification": "FDA Approved"}] |
| What methodologies do you use for health and safety impact assessments? | Methodology              | Multiple Select + Text Description     | Array + String   | ["Life Cycle Assessment (LCA)", "Hazard Analysis and Critical Control Points (HACCP)", "Failure Mode and Effects Analysis (FMEA)", "Toxicological Risk Assessment"] |
| Which third parties conduct or verify your health and safety assessments? | Third Party Verification | Dynamic List with Organization Details | Array of Objects | [{"organization": "SGS Testing Services", "accreditation": "ISO 17025", "scope": "Chemical Safety Testing", "last_audit": "2024-02-20"}] |
| What criteria do you use to determine 'significant' product categories? | Significance Criteria    | Multiple Select + Weighting            | Weighted Array   | [{"criterion": "Revenue impact", "weight": 30}, {"criterion": "Health risk potential", "weight": 40}, {"criterion": "Regulatory requirements", "weight": 30}] |
| How frequently are health and safety assessments updated for each category? | Assessment Frequency     | Select + Custom Input                  | String + Number  | "Every 2 years for low-risk products, annually for high-risk products, immediately upon regulatory changes" |
| What is the total number of product and service categories your organization offers? | Total Categories         | Number Input                           | Integer          | 127                                                          |
| How many categories were assessed during the reporting period? | Assessed This Period     | Number Input                           | Integer          | 121                                                          |
| What percentage of total revenue do assessed categories represent? | Revenue Coverage         | Percentage Input                       | Float            | 98.7                                                         |

## GRI 416-2: Incidents of Non-compliance Concerning Health and Safety Impacts

| Question                                                     | Question Type       | Input Type                 | Data Type        | Example Answer                                               |
| ------------------------------------------------------------ | ------------------- | -------------------------- | ---------------- | ------------------------------------------------------------ |
| How many incidents of non-compliance concerning health and safety impacts of products occurred during the reporting period? | Quantitative Count  | Number Input               | Integer          | 3                                                            |
| How many non-compliance incidents resulted in a fine or penalty? | Regulatory Penalty  | Number Input + Details     | Integer + String | "2 incidents: FDA warning letter for labeling non-compliance ($50,000 fine), EU recall notice for undeclared allergens ($125,000 penalty)" |
| How many non-compliance incidents resulted in a warning?     | Warning Count       | Number Input + Details     | Integer + String | "1 incident: State health department warning for temperature control deviation during transport" |
| How many non-compliance incidents resulted in voluntary recalls? | Voluntary Recall    | Number Input + Details     | Integer + Array  | 1, [{"product": "Organic Baby Food Batch #A2024", "reason": "Potential contamination", "units_recalled": 50000, "market_coverage": "North America"}] |
| How many non-compliance incidents resulted in mandatory recalls? | Mandatory Recall    | Number Input + Details     | Integer + Array  | 0, []                                                        |
| What was the total financial impact of non-compliance incidents? | Financial Impact    | Currency Input + Breakdown | Float + Object   | {"total": 275000, "fines": 175000, "recall_costs": 75000, "legal_fees": 25000, "currency": "USD"} |
| Describe each non-compliance incident in detail              | Incident Details    | Repeating Form Fields      | Array of Objects | [{"incident_id": "INC-2024-001", "date": "2024-06-15", "product": "Protein Powder", "non_compliance_type": "Labeling", "regulatory_body": "FDA", "resolution": "Label correction implemented", "status": "Closed"}] |
| What corrective actions were taken for each incident?        | Corrective Actions  | Text per Incident          | Array of Strings | ["Immediate product recall and customer notification", "Updated manufacturing protocols", "Enhanced supplier quality audits", "Staff retraining on GMP compliance"] |
| How do you track and manage non-compliance incidents?        | Incident Management | System Description         | String           | "Integrated ERP system with automated incident logging, stakeholder notifications, regulatory reporting workflows, and corrective action tracking with timeline monitoring" |
| What preventive measures have been implemented to avoid future incidents? | Prevention Measures | Multiple Select + Text     | Array + String   | ["Enhanced supplier qualification", "Increased testing frequency", "AI-powered quality monitoring", "Cross-functional safety review committees"] |

## Additional Context and Verification Questions

| Question                                                     | Question Type           | Input Type                | Data Type        | Example Answer                                               |
| ------------------------------------------------------------ | ----------------------- | ------------------------- | ---------------- | ------------------------------------------------------------ |
| What regulatory frameworks govern customer health and safety in your industry? | Regulatory Context      | Multiple Select + Custom  | Array of Strings | ["FDA Food Safety Modernization Act", "EU General Food Law", "ISO 22000", "CODEX Alimentarius", "Local health department regulations"] |
| How do you ensure compliance across different geographical markets? | Geographic Compliance   | Text + Regional Mapping   | String + Object  | "Market-specific compliance matrices maintained for each region, with local regulatory experts and automated compliance monitoring systems" |
| What customer communication channels do you use for health and safety information? | Communication Channels  | Multiple Select           | Array of Strings | ["Product labeling", "Company website", "Mobile app notifications", "Social media", "Direct customer service", "Email alerts", "Retail partner communications"] |
| How do you handle customer complaints related to health and safety? | Complaint Handling      | Process Description       | String           | "24/7 customer hotline with trained safety specialists, immediate escalation protocols, root cause analysis within 48 hours, and follow-up within 7 days" |
| What external certifications or accreditations do you maintain for customer health and safety? | Certifications          | Dynamic List with Details | Array of Objects | [{"certification": "BRC Global Standard", "certifying_body": "SGS", "valid_until": "2025-08-30", "scope": "Food Safety", "grade": "AA"}] |
| How do you measure customer satisfaction with health and safety performance? | Customer Satisfaction   | Metrics + Methodology     | Object           | {"method": "Annual customer survey", "sample_size": 5000, "response_rate": 32, "satisfaction_score": 4.2, "scale": "1-5"} |
| What emerging health and safety risks have you identified for your products? | Emerging Risks          | Risk Assessment Table     | Array of Objects | [{"risk": "Microplastics in packaging", "probability": "Medium", "impact": "High", "mitigation": "Alternative packaging research", "timeline": "2025-2026"}] |
| How do you incorporate health and safety considerations into new product development? | Design Integration      | Process Description       | String           | "Stage-gate process with mandatory safety reviews at each phase, toxicological assessments for all new ingredients, consumer safety testing before market launch" |
| What is your process for monitoring post-market safety performance? | Post-Market Monitoring  | Process + Metrics         | String + Object  | "Continuous adverse event monitoring, social media sentiment analysis, retail partner feedback loops, and quarterly safety performance reviews" |
| How do you ensure supply chain compliance with health and safety standards? | Supply Chain Management | Multiple Approaches       | Array of Strings | ["Supplier audits", "Contractual requirements", "Certification mandates", "Real-time monitoring systems", "Surprise inspections", "Third-party verification"] |

## Data Quality and Verification Questions

| Question                                                     | Question Type            | Input Type              | Data Type        | Example Answer                                               |
| ------------------------------------------------------------ | ------------------------ | ----------------------- | ---------------- | ------------------------------------------------------------ |
| What internal controls exist to ensure data accuracy for health and safety reporting? | Internal Controls        | Process Description     | String           | "Multi-level review process, automated data validation rules, quarterly internal audits, and cross-functional verification committees" |
| Has this health and safety data been externally assured?     | External Assurance       | Yes/No + Details        | Boolean + Object | {"assured": true, "assurer": "KPMG", "standard": "ISAE 3000", "level": "Limited assurance", "report_date": "2024-12-15"} |
| What documentation supports your health and safety performance data? | Supporting Documentation | File Upload + List      | Array + Files    | ["Internal audit reports", "Third-party certificates", "Regulatory correspondence", "Customer complaint logs", "Test results", "Training records"] |
| How do you ensure consistency in health and safety data collection across different locations? | Data Consistency         | Methodology Description | String           | "Standardized data collection protocols, centralized reporting systems, regular training for data collectors, and periodic inter-location audits" |
| What limitations or uncertainties exist in your health and safety data? | Data Limitations         | Text Description        | String           | "Some legacy product categories lack comprehensive historical data; third-party distributor incident reporting may have delays; emerging market regulatory frameworks still developing" |
