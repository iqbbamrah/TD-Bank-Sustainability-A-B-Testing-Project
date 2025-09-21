# TD-Bank-Sustainability-A-B-Testing-Project
This project demonstrates an end-to-end A/B testing framework
The project simulates a customer-facing sustainability initiative, where customers are nudged to enroll in paperless billing through a "green message" in their online portal. The goal is to measure the causal impact of the intervention on adoption rates.

Key Features
• Synthetic Data Simulation: Creates a mock dataset of ~50,000 customers randomly assigned to control (standard messaging) and treatment (green nudge) groups.
• Sample Ratio Mismatch (SRM) Check: Validates randomization integrity.
• Statistical Analysis:
• Difference-in-proportions test (conversion rates)
• Logistic regression with controls for customer demographics
• Subgroup Analysis: Examines heterogeneity by age group.
• Guardrail Metrics: Checks retention rates to ensure no unintended negative impacts.
• Visualization: Conversion rates by group and subgroup.
• Business Insights: Interprets results in terms of practical recommendations for TD’s sustainability
strategy.

Tech Stack
• Python: Core language
• Pandas & NumPy: Data manipulation
• SciPy & Statsmodels: Statistical tests & regression • Matplotlib & Seaborn: Visualizations

How to Run
1. Clone this repository.
2. Open the Jupyter Notebook ( td_abtest_green_nudge.ipynb ). 3. Run all cells in order — the notebook is fully self-contained.

Expected Outcomes
• Evidence of whether the green nudge significantly increases enrollment in paperless billing. • Subgroup insights (e.g., younger customers may be more responsive).
• Guardrail validation that retention isn’t harmed by the intervention.

Why This Project Matters
This project simulates real-world A/B testing scenarios. It demonstrates not only technical skills in experimental design and data science, but also business-facing communication by translating analytics into actionable recommendations.
