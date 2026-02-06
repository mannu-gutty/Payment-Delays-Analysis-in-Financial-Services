# Payment-Delays-Analysis-in-Financial-Services
analizar patrones de pagos tardíos a partir de un conjunto de datos simulado

## Project Overview
In the financial services industry, late payments can significantly impact cash flow, credit risk management, and operational efficiency.  
This project presents an **exploratory data analysis (EDA)** focused on identifying patterns in **late customer payments** using a simulated dataset.

The goal is to demonstrate how transactional payment data can be transformed into **actionable insights** for credit, risk, and operations teams.

---

## Objectives
- Measure the overall rate of late payments.
- Analyze late payment behavior by **payment method**.
- Identify customers with **recurrent late payments**.
- Provide data-driven **business recommendations** to improve payment performance.

---

## Dataset
The dataset used in this project is **simulated** and represents payment activity for a financial services company.

### Main Features:
- `customer_id`: Unique identifier for each customer  
- `payment_due_date`: Payment due date  
- `payment_date`: Actual payment date  
- `amount`: Payment amount  
- `payment_method`: Method used to make the payment  

### Derived Features:
- `days_late`: Number of days the payment was delayed  
- `late_payment`: Binary indicator (1 = late payment, 0 = on-time)

---

## Analysis Performed
The analysis includes:
- Data cleaning and feature engineering
- Calculation of late payment rates
- Comparison of late payments by payment method
- Identification of customers with repeated late payment behavior
- Visualization of key metrics using `matplotlib`

---

## Key Findings
- A significant portion of payments are made after the due date.
- Certain payment methods show higher late payment rates.
- A small group of customers accounts for multiple late payments, indicating potential credit risk.

---

## Business Recommendations
Based on the analysis, the following actions are suggested:
- Implement automated payment reminders before due dates.
- Segment customers based on payment behavior for targeted follow-ups.
- Review and optimize payment methods with higher delay rates.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / VS Code

---

## Notes
This project uses simulated data to focus on **analytical thinking, data manipulation, and business-oriented insights**, rather than data availability.

---

## Next Steps
- Incorporate real-world data when available.
- Extend the analysis with predictive modeling for late payment risk.
- Add dashboards for operational monitoring.

---

## Author
Juan Manuel Ramírez Gutiérrez  
Aspiring Data Analyst | Fintech & Financial Services
