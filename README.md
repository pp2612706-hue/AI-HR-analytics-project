# AI-Driven HR Analytics and Decision Support System

## 1. Project Overview

This project presents an end-to-end AI-driven business solution for Human Resource analytics. It integrates data analysis, dashboard visualization, and a rule-based decision support system to identify employee risk and support managerial decision-making.

The solution demonstrates how organizations can transform raw employee data into actionable insights using analytics and AI logic.

---

## 2. Problem Statement

Organizations face significant challenges in identifying employees at risk of attrition due to fragmented and complex data. Traditional methods rely on manual analysis, which is time-consuming and often reactive rather than proactive.

As a result:

* High-risk employees are not identified early
* Employee dissatisfaction goes unnoticed
* Attrition rates increase
* Decision-making is delayed

This project addresses these challenges by building a system that continuously monitors employee data, identifies risk patterns, and recommends actions.

---

## 3. Objectives

* Analyze employee data to identify trends and patterns
* Build an interactive dashboard for performance monitoring
* Develop a Decision Support System (DSS) for risk classification
* Provide actionable recommendations for HR teams
* Enable data-driven decision-making

---

## 4. Business Flow

Data → Analysis → Dashboard → Decision → Action

---

## 5. Dataset Description

The dataset contains employee-level information used for analytics and decision-making.

### Features:

* employee_id
* department
* satisfaction_score
* attendance_percent
* overtime_hours
* performance_rating
* attrition

### Generated Fields:

* risk_level
* recommended_action

---

## 6. Dashboard Overview

The Power BI dashboard provides a comprehensive view of workforce performance and risk.
<img width="1713" height="801" alt="Screenshot 2026-04-08 204201" src="https://github.com/user-attachments/assets/8442db8b-2bdd-4709-be03-869d782e1581" />
<img width="1680" height="790" alt="image" src="https://github.com/user-attachments/assets/df67da30-9723-4eb4-8518-f428dedcabf6" />




### Key Components:

* KPI Cards: Total Employees, Attrition Count, Satisfaction, Attendance, Performance
* Attrition Analysis by Department
* Risk Level Distribution
* Satisfaction by Department
* Overtime Analysis
* Recommended Action Insights

The dashboard enables quick identification of problem areas and supports strategic decisions.

---

## 7. Decision Support System (DSS)

### Risk Classification Logic:

* High Risk: Low satisfaction and high overtime
* Medium Risk: Low satisfaction or low attendance
* Low Risk: Stable employees

### Recommendation Logic:

* High Risk: Immediate HR intervention
* Medium Risk: Monitoring and engagement programs
* Low Risk: Maintain and reward performance

The DSS converts analytical insights into actionable decisions.

---

## 8. Output

* Risk classification for each employee
* Recommended actions

---

## 10. How to Run

1. Open the notebook in Google Colab
2. https://colab.research.google.com/drive/1HO3ld3nSfk7jQGZ3ETORP1fKws8SwffS
3. Run all cells sequentially
4. Generate output CSV
5. Open Power BI dashboard file
6. Explore insights and filters

---

## 11. Business Insights

* Employees with low satisfaction and high overtime show high attrition risk
* Departments with higher attrition require management intervention
* Attendance and engagement directly impact employee stability
* Early identification of risk improves retention strategies

---

## 12. Conclusion

This project demonstrates how AI and analytics can be integrated to solve real-world business problems. By combining dashboards and decision support systems, organizations can move from reactive to proactive decision-making.

The solution provides a scalable approach for workforce analytics and strategic HR management.
