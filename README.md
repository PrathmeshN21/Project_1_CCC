# 🚀 CCC Mandatory Fields Checker

A rule-based validation tool for Common Corporate Components (CCC) that ensures mandatory field compliance, detects data inconsistencies, and prevents processing errors. The tool provides a web interface to upload files, view validation results, and download error reports.

---

## 📌 Features

- ✅ Upload CSV or Excel files  
- ✅ Rule-based validation engine  
- ✅ Detects missing / incorrect data  
- ✅ Displays errors in tabular format  
- ✅ Downloadable Excel error report  

---

## 🧠 Business Rules Implemented

- Product = **P** → Model Year must be **2075**  
- ANA Description contains **"Chart Current Mass" / "New Mass"** → Mass must be **0**  
- Part Type must be **D**  
- Part DRD must be **SD**  
- Engineer Code must be **PAN1**  
- Model Code must be **PPPA**  

---

## ⚙️ Installation

Install required libraries:

```bash
pip install flask pandas openpyxl pyngrok
