# Healthcare Analytics Dashboard (Power BI)

An interactive Healthcare Analytics Dashboard built using Microsoft Power BI to analyze patient demographics, hospital operations, billing performance, and diagnostic outcomes. The dashboard converts structured healthcare data into actionable insights to support data-driven healthcare decision-making.

## Key Features
- Patient demographic analysis (gender, age, blood type)
- Medical condition and disease distribution
- Hospital admission analysis (Elective, Emergency, Urgent)
- Doctor-wise and insurance-wise billing insights
- Diagnostic test result visualization
- Interactive slicers, buttons, and multi-page navigation

## Dataset
Synthetic healthcare dataset representing real-world hospital data, including:
- Patient details
- Medical conditions
- Admission and discharge dates
- Hospitals and doctors
- Insurance providers
- Billing amounts
- Medications and test results

## Tech Stack
- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Star Schema Data Modeling

## Data Modeling
The dashboard uses a Star Schema for optimized performance:
- Fact table for healthcare transactions
- Dimension tables for Patient, Doctor, Hospital, Medical Condition, and Admission Type

## Insights Delivered
- Identification of high-volume medical conditions
- Emergency vs elective admission patterns
- Revenue contribution by doctors and insurance providers
- Diagnostic outcome distribution
- Improved visibility into hospital workload and finances

## Future Enhancements
- Real-time data integration
- Predictive analytics for patient risk and length of stay
- Machine learning-based forecasting
- Secure deployment via Power BI Service
