# Payroll AI Copilot

A role-based Payroll AI Copilot that explains payroll deductions and policies using a synthetic payroll dataset, with safety, privacy, and hallucination prevention.

## Features
- Context-aware payroll responses
- Employee and HR role separation
- Legal and ethical explanation of deductions
- Sensitive data protection
- Hallucination prevention
- Interactive testing in Google Colab (widget + CLI fallback)

## Dataset
- Synthetic payroll dataset (CSV)
- Used only for context lookup
- No real employee data
- No model training on payroll data

## Sample Input and Output

Example 1 – Employee  
Input:  
Employee ID: 1001  
Role: EMPLOYEE  
Query: Why is PF deducted from my salary?  

Output:  
PF is deducted as a statutory contribution based on your basic salary, as per EPF regulations.

Example 2 – HR  
Input:  
Employee ID: 1003  
Role: HR  
Query: Explain statutory payroll deductions.  

Output:  
Statutory payroll deductions include Provident Fund, ESI (if applicable), Professional Tax, and Income Tax, as mandated by law.

Example 3 – Safety Case  
Input:  
Employee ID: 1001  
Role: EMPLOYEE  
Query: What will my salary be next year?  

Output:  
I don't have enough information to predict future salary.

## How to Run
1. Open the notebook in Google Colab
2. Run all cells
3. Use  CLI fallback to test queries

## Disclaimer
This project uses synthetic data for academic purposes only and is not intended for real payroll processing.

## Author
Sona S
