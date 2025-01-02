# BCG-Feature-Engineering-and-Modelling

Background
PowerCo, a prominent gas and electricity utility provider, serves corporate, SME (small and medium enterprise), and residential customers. The liberalization of Europe’s energy market has resulted in substantial customer churn, particularly within the SME segment. PowerCo has engaged BCG to analyze the drivers behind SME customer churn and recommend actionable strategies to mitigate this issue.

A key hypothesis suggests that price changes significantly influence customer churn. Identifying customers likely to churn at the current price point can guide interventions, such as offering discounts. The SME division head is considering a 20% discount as a potential solution to retain customers, especially those who are highly price-sensitive.

Task 1: Business Understanding and Hypothesis Testing
The first step involves gaining a comprehensive understanding of the client’s challenges and formulating the hypothesis as a structured data science problem. Key considerations include:

Hypothesis: Price sensitivity is a primary driver of churn, and offering targeted discounts can reduce churn rates.
Approach:
Identify factors influencing customers’ decisions to stay or switch providers (e.g., price, usage patterns, and service quality).
Define the necessary data fields and sources, including customer demographics, historical usage, pricing, and churn indicators.
Structure a data frame where rows represent individual customers and columns capture relevant variables.
Conduct exploratory analyses to assess variable relationships and test the price sensitivity hypothesis.
Task 2: Exploratory Data Analysis (EDA)
BCG has received the following datasets:

Customer Data: Historical customer usage, sign-up dates, and forecasted usage.
Pricing Data: Historical fixed and variable pricing.
Churn Data: Indicators of whether a customer has churned.
Steps for EDA:

Analyze data types, distributions, and key statistics for critical variables.
Explore correlations between price changes and churn behavior to verify the hypothesis.
Summarize findings and identify gaps in data coverage.
Suggest additional data sources for augmentation, such as open-source energy market pricing or customer sentiment datasets.
Output: A concise half-page summary of insights, including recommendations for data enrichment.

Task 3: Feature Engineering and Modeling
With a deeper understanding of the data, the next phase involves uncovering meaningful signals to enhance the churn prediction model through feature engineering.

Steps:

Feature Engineering: Develop features such as price elasticity, historical churn trends, and customer segmentation based on usage and pricing.
Feature Optimization: Propose refinements to improve predictive power, explaining the rationale behind these choices.
Model Training: Train a Random Forest Classifier on the engineered features to predict churn, and evaluate its performance using appropriate metrics.
Model Evaluation:
Advantages: Robustness to overfitting, ability to handle complex interactions, and interpretability through feature importance.
Disadvantages: Higher computational cost and reduced interpretability for individual predictions.
Bonus Analysis: Estimate the financial savings PowerCo could achieve by deploying the model, considering customer retention rates and discount impact.

Task 4: Findings and Recommendations
Develop a summary slide synthesizing project progress and insights for the client.

Key Considerations:

Metrics to Highlight: Share the most impactful numbers, such as churn reduction potential and financial impact of implementing the model.
Level of Detail: Provide high-level insights, avoiding overly technical explanations unless requested.
Client Impact: Quantify the model's potential to improve customer retention and enhance PowerCo’s bottom line.
“So What” Test: Ensure every point clearly articulates its relevance and importance to PowerCo’s business objectives.
