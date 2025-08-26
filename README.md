# Environmental-Sustainability-in-Supply-Chain-Management
This project focuses on evaluating environmental sustainability in supply chain.
Project Overview

This project focuses on evaluating environmental sustainability in supply chains using machine learning. It applies logistic regression to predict whether companies meet certain sustainability criteria based on their environmental metrics.

The model analyzes factors such as:

Carbon Emissions (kg CO2e)

Recycling Rate (%)

Use of Renewable Energy (%)

Green Packaging Usage (%)

By setting sustainability thresholds (using statistical percentiles), the project classifies companies into two categories:
✅ Sustainability Met
❌ Sustainability Not Met
<img width="756" height="586" alt="image" src="https://github.com/user-attachments/assets/5e04556a-a9e1-44ce-ae86-40a91ef5a171" />

This enables organizations to assess their environmental performance and benchmark against peers.

⚙️ Features

Preprocesses dataset by handling missing values.

Calculates sustainability thresholds dynamically based on percentiles.

Creates a binary classification target: Sustainability_Met.

Builds a Logistic Regression pipeline with:

Feature scaling (StandardScaler)

Hyperparameter tuning (GridSearchCV)

Evaluates performance with:

Training Accuracy

Test Accuracy

Cross-Validation Accuracy

Allows users to check individual company metrics and determine if sustainability criteria are met.

Python Model Features

Preprocesses data by handling missing values.

Defines sustainability thresholds dynamically using percentiles.

Creates a binary target variable: Sustainability_Met.

Builds a Logistic Regression pipeline with scaling and hyperparameter tuning.

Evaluates model performance with train/test/validation accuracies.

Provides company-level evaluation by entering a company name.
<img width="763" height="268" alt="image" src="https://github.com/user-attachments/assets/d7e324c0-dc29-4d94-bb0a-78b811eee780" />

📊 Power BI Dashboard: Sustainability Efficiency Score (SES)
<img width="942" height="598" alt="image" src="https://github.com/user-attachments/assets/cfb22e24-10e7-4035-a816-d15abf6ebcfe" />

Alongside the Python logistic regression model, this project also includes a Power BI dashboard to visualize sustainability metrics across companies.

🔹 Dashboard Features

Average Sustainability Efficiency Score (SES):

Displays the overall average SES across companies.

In this example: 51.28.

Top 10 Companies by SES:

Highlights the leading companies with the highest sustainability scores.

Example: Palantir (61.85), Stripe (60.72), Snowflake (59.87), etc.

Sustainability Breakdown by Company:

A stacked column chart showing the average use of renewable energy and other sustainability metrics.

Enables comparison between companies like Audi, Lime, Twitter, ResMed, etc.

Carbon Emission Breakdown by SES:

A pie chart visualization of carbon emissions distribution by sustainability efficiency score.

Provides insights into how emissions are spread across companies.

📌 Business Insights from Dashboard

Companies like Palantir, Stripe, and Snowflake show stronger sustainability performance compared to peers.

The breakdown highlights renewable energy adoption as a key driver of SES.

Carbon emission visualization provides transparency into environmental impact, useful for compliance tracking and green supply chain strategies.

📷 Dashboard Preview

👉 This makes your project look end-to-end:

Python (ML Model): Predict & evaluate sustainability criteria.

Power BI Dashboard: Visualize company performance, rankings, and emission breakdowns.
