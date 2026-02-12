Corporate Investment & Financial Projection Dashboard
(Tutaj wstaw screen ze strony z NPV i wykresem cashflow)

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

The Concept: A "What-If" simulation that answers the question: "What happens to our Revenue if sales volume drops by 10% and we increase discounts by 5%?".

Business Value: Crucial for Risk Management. It exposes the project's vulnerability to external market shocks before any money is spent.

3. Profitability & Margin Analysis
The Concept: Analysis of the "Whale Curve" – identifying which customers/segments generate the most profit vs. those that erode value.

Business Value: visualizes the profitability distribution, helping to optimize the customer portfolio.
<img width="1163" height="655" alt="image" src="https://github.com/user-attachments/assets/a643a3fc-9b1d-4fca-b27f-67f9e6e5ea6d" />

📂 Project Structure
The repository is organized as follows:

images/ - Screenshots of the dashboard (project_profitability.png, sales_sensitivity.png, etc.).

Financial_Analysis.pbix - The Power BI file containing the financial models.

README.md - Documentation (This file).

🚀 How to Run
Download the Financial_Analysis.pbix file.

Open in Power BI Desktop.

Interact: Try moving the "Discount Rate" slider on the Project Profitability page to see how the NPV curve reacts in real-time.

👤 Author Piotr Pszenny Aspiring Risk & Data Analyst | Gdańsk Tech




