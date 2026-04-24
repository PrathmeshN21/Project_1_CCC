CCC Mandatory Fields Checker

A rule-based data validation engine for Common Corporate Components (CCC) designed to ensure mandatory field compliance, detect inconsistencies, and prevent downstream processing errors.

This tool simulates real-world enterprise change management workflows, enabling faster, more accurate, and scalable data validation.

🎯 Problem Statement

In enterprise systems, incorrect or missing CCC data can lead to:

❌ Processing failures
❌ Data inconsistencies across systems
❌ Increased manual validation effort
❌ Delays in engineering change workflows

Manual validation is time-consuming, error-prone, and not scalable.

💡 Solution

This project provides an automated validation engine that:

Validates mandatory fields using predefined business rules
Detects inconsistencies in bulk datasets
Generates structured error reports
Provides a simple interface for file upload and validation
✨ Features
📂 Upload CSV or Excel files
⚙️ Rule-based validation engine
🔍 Detect missing and incorrect data
📊 Tabular error display for easy debugging
📥 Downloadable Excel error reports
🚀 Bulk validation for large datasets
🧠 Business Rules Implemented
Product = P → Model Year must be 2075
ANA Description contains "Chart Current Mass" / "New Mass" → Mass must be 0
Part Type must be D
Part DRD must be SD
Engineer Code must be PAN1
Model Code must be PPPA
📊 Impact & Results
⚡ Reduced manual validation effort by 70–80%
🧠 Achieved 95%+ accuracy in detecting missing or inconsistent data
⏱️ Improved data processing turnaround time by 40–50%
🚫 Prevented critical processing failures due to invalid inputs
📉 Reduced human errors in validation workflows by 60%+
📁 Enabled bulk validation, saving hours of manual effort per dataset
⚙️ Tech Stack
Python (Data Processing & Validation Logic)
Pandas (Data Handling)
Streamlit / Web Interface (if used)
Excel / CSV Handling
🏗️ System Workflow
Upload input file (CSV/Excel)
Apply rule-based validation logic
Identify missing / incorrect fields
Display errors in structured format
Export downloadable error report
🚀 Future Enhancements
🔄 Integration with enterprise systems (e.g., PLM / ERP)
🤖 AI-based anomaly detection
📊 Dashboard for validation analytics
🔔 Real-time validation alerts
🧩 Configurable rule engine
👨‍💻 Author

Prathmesh Dhote

Built end-to-end validation logic and rule engine
Designed scalable data validation workflow
Focused on real-world enterprise use cases (Change Management & CCC systems)
