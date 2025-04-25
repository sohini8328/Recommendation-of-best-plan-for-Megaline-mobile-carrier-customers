
Project Purpose
The goal of this project is to recommend the most suitable mobile plan to new customers based on their mobile usage behavior. By analyzing customer data and evaluating various machine learning models, this project aims to provide data-driven recommendations to enhance user satisfaction and optimize plan offerings.
Key Observations and Approach
- Initial Insights:- Customers on the Ultra plan predominantly use more call services.
- Smart plan customers exhibit significantly higher internet usage, indicating they rely heavily on data services.
- Based on these patterns, the model was designed to recommend the Smart plan for individuals prioritizing internet usage.

- Model Evaluation:- Three machine learning models were considered: Logistic Regression, Decision Tree, and Random Forest.
- The Random Forest model stood out with an accuracy score of 0.79, surpassing the accuracy threshold of 0.75. Upon final evaluation, the Random Forest Classifier achieved a notable accuracy of 0.80, confirming it as the most reliable option.
- In comparison:- Logistic Regression yielded an accuracy of 0.71.
- The Decision Tree model fell short of the performance delivered by Random Forest.

Recommendations for Megaline Customers
To choose the best plan, customers are advised to evaluate their individual requirements, including:
- Data Usage: Customers with heavy internet consumption should consider plans with unlimited data options.
- Coverage Needs: Evaluate network performance and coverage in your area.
- Budget Constraints: Explore affordable prepaid options or multi-line plans for cost savings.

By combining this model’s predictions with customer-specific preferences, Megaline can provide tailored recommendations to its users.

The Random Forest model is the optimal choice for predicting and recommending mobile plans. It effectively captures customer usage trends and aligns with accuracy requirements, making it a valuable tool for enhancing the customer experience.

Does this revision align with the tone and purpose you envisioned? Let me know if you'd like any further adjustments!

Use BLANK_README.md to get started Build With: This is the list of the libraries used by me to run this project were pandas,numpy, matplotlib.pyplot, plotly.express and stats.

Getting Started: This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple steps. Prequisites: This is an example of software and how to install them. VS Code

Clone the repo: https://github.com/sohini8328/Recommendation-of-best-plan-for-Megaline-mobile-carrier-customers.git
