Corporate Investment & Financial Projection Dashboard
(Tutaj wstaw screen ze strony z NPV i wykresem cashflow)

<img width="1165" height="654" alt="image" src="https://github.com/user-attachments/assets/5f63e3ad-9260-4299-9413-c6772b7b3f97" />

🎯 Project Goal
The objective of this project was to build a robust Financial Modeling tool to evaluate long-term investment projects. Unlike standard operational reporting, this dashboard focuses on Capital Budgeting and Risk Assessment.

It serves as a decision-support system for CFOs and Investment Committees to:

Evaluate Viability: Calculate Net Present Value (NPV) and Internal Rate of Return (IRR) for potential projects.

Assess Risk: Perform Sensitivity Analysis to see how changes in sales or discount rates impact profitability.

Forecast Cash Flows: Visualize the "Time Value of Money" over a 5-10 year horizon.

💻 Technologies & Financial Concepts
Microsoft Power BI – The engine for calculation and visualization.

Financial Modeling – Implemented DCF (Discounted Cash Flow) logic directly in DAX.

What-If Parameters – Created dynamic scenarios for sensitivity testing (disconnected tables technique).

DAX (Data Analysis Expressions) – Complex formulas for XNPV equivalent calculations and running totals.

Scenario Planning – Dynamic switching between Optimistic, Base, and Pessimistic cases.

📊 Key Modules & Insights
1. Investment Appraisal (NPV & IRR)
The Concept: I built a dynamic model that calculates the NPV profile based on a user-selected Discount Rate (WACC).

Business Value: This allows management to instantly see if a project creates value (NPV > 0) or destroys it, and at what cost of capital the project becomes unviable (IRR).

2. Sensitivity Analysis (Risk Modeling)
(Tutaj wstaw screen z tabelą macierzową - ten z suwakami)

<img width="1190" height="672" alt="image" src="https://github.com/user-attachments/assets/e042b9ef-936d-4cf9-a246-a9e84f57d15f" />

The Concept: A "What-If" simulation that answers the question: "What happens to our Revenue if sales volume drops by 10% and we increase discounts by 5%?".

Business Value: Crucial for Risk Management. It exposes the project's vulnerability to external market shocks before any money is spent.

3. Profitability & Margin Analysis

<img width="1161" height="654" alt="image" src="https://github.com/user-attachments/assets/865d3337-6cef-4c9e-8710-3a2ecdb6a6f0" />

The Concept: Analysis of the "Whale Curve" – identifying which customers/segments generate the most profit vs. those that erode value.

Business Value: visualizes the profitability distribution, helping to optimize the customer portfolio.

📂 Project Structure
The repository is organized as follows:

images/ - Screenshots of the dashboard (project_profitability.png, sales_sensitivity.png, etc.).

Financial_Analysis.pbix - The Power BI file containing the financial models.

README.md - Documentation (This file).

🚀 How to Run
Download the Financial_Analysis.pbix file.

Open in Power BI Desktop.

Interact: Try moving the "Discount Rate" slider on the Project Profitability page to see how the NPV curve reacts in real-time.

👤 Author Piotr Pszenny Aspiring Risk & Data Analyst 
