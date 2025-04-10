# Product Funnel Analysis for SaaS FinTech

## Executive Summary:

A significant number of customers sign up for a subscription but fail to complete the payment process, resulting in lost revenue. This analysis explores the payment funnel to identify friction points, track user drop-offs, and analyze errors that prevent successful payments. Using SQL and data visualization techniques, we uncover key obstacles and provide actionable recommendations to improve conversion rates and increase revenue.


### Business Problem: 

The finance team has raised concerns about an increasing number of unpaid subscriptions. While customers opt into a plan, they fail to complete the payment process, negatively impacting the company’s revenue. To address this, we need to analyze the payment funnel and determine where users drop off, identify common errors, and propose solutions to enhance the payment experience and increase successful transactions.

![Image](https://github.com/user-attachments/assets/0d55c6a6-962f-41cb-ad5a-860185c773ff)

Key Business Questions <br> 
At which stage of the payment funnel do customers drop off the most? <br>
What are the most common errors preventing successful payments? <br>
How do user errors (e.g., incorrect payment details) compare to vendor errors (e.g., processing failures)? <br>
What actionable steps can be taken to reduce friction and improve conversion rates? <br>

### Methodology: 

1. Exploratory Data Analysis (EDA)
    -Understand the dataset and define key metrics.
    -Identify trends in user behavior within the payment process.
2. Product Funnel Analysis
    -Track subscriptions through each stage of the payment process.
    -Measure conversion rates at each step.
    -Determine abandonment rates and common drop-off points.
3. Error Analysis
    -Classify errors into user errors vs. vendor errors.
    -Measure the frequency of each error type.
    -Assess the impact of errors on conversion rates.
4. Data Visualization
    -Create funnel charts to illustrate user flow.
    -Develop bar charts to highlight common errors.
    -Use line graphs to track trends over time.

### Skills:

SQL: CTEs, CASE statements, subqueries, window functions
Data Wrangling & Cleaning: Handling missing data, formatting inconsistencies
Data Visualization: Funnel charts, error distribution plots
Product Analytics: Understanding user behavior and conversion rates

### RESULTS
-subscriptions fail to open the payment portal, indicating a major drop-off at the initial step.
-users encounter errors when entering payment details, highlighting a need for UX improvements.
-transactions fail due to vendor processing errors, suggesting potential issues with the payment provider.

### Business Recommendations

1. Reduce friction at the payment entry point:
-Implement one-click payment options (Apple Pay, Google Pay, PayPal) to streamline the process.
-Offer auto-fill payment details for returning customers.

2. Address user errors in payment details:
-Provide real-time validation and error messages to correct input mistakes before submission.
-Implement a retry mechanism with clear instructions for failed attempts.

3. Optimize vendor processing reliability:
-Work with the third-party vendor to investigate and reduce processing errors.
-Explore alternative payment processors or redundancy options.

4. Increase engagement for users who abandon the process:
-Implement email and SMS reminders for incomplete payments.
-Introduce customer support outreach to assist users facing payment difficulties.

### Next Steps: 

1. Deep dive into error breakdowns to identify the most common failure reasons.
2. Conduct A/B testing on different payment flows to evaluate conversion improvements.
3. Assess whether subscription reminders or incentives (e.g., discounts, free trials) can encourage payment completion.


