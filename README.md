# Boundary Value Analysis for Form Validation

## Overview
This repository contains test cases designed using **Boundary Value Analysis (BVA)** to validate a form's input fields. The tested fields include **Username, Age, and Password** with specific input constraints.

## 📌 Test Case Details
### **1. Username Validation**
- Allowed: **5 to 15 characters** (Alphabets only)
- **Test Scenarios:**
  - ✅ 5-character username (Valid)
  - ✅ 6 to 15-character username (Valid)
  - ❌ Below 5 characters (Invalid)
  - ❌ Above 15 characters (Invalid)

### **2. Age Validation**
- Allowed: **18 to 65** (Only integer values)
- **Test Scenarios:**
  - ✅ Age 18 to 65 (Valid)
  - ❌ Below 18 and above 65 (Invalid)

### **3. Password Validation**
- Allowed: **8 to 20 characters** (Alphabets & Numbers)
- **Test Scenarios:**
  - ✅ 8 to 20-character password (Valid)
  - ❌ Below 8 and above 20 characters (Invalid)

## 📂 Files Included
- `Username_TestCases.csv` - Test cases for Username validation
- `Age_TestCases.csv` - Test cases for Age validation
- `Password_TestCases.csv` - Test cases for Password validation

## 🚀 How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/Shardul13102001/Boundary-Value-Analysis.git
   ```
2. Open the test case files to review the validation results.
3. Use the test cases for manual or automated testing of similar form validations.

## 🔗 Repository Link
[GitHub Repository](https://github.com/Shardul13102001/Boundary-Value-Analysis)

## 🏷️ Tags
#SoftwareTesting #BoundaryValueAnalysis #LearnInPublic #Testing
