# Hackathon-Assignment-Brief-Data-Driven-Business-Decisions
Objective: Analyze the Toy Store E-Commerce dataset to identify actionable business insights. Each student must formulate a business hypothesis, translate it into a statistical hypothesis, test it using the dataset, and make data-driven recommendations.
Toy Store E-Commerce Analytics Hackathon Report
Project Overview
This project, conducted as part of the Toy Store E-Commerce Analytics Hackathon, aimed to derive actionable business insights from a provided dataset. The core objective was to formulate and test business hypotheses, supported by statistical analysis, and to provide data-driven recommendations.

Dataset
The analysis utilized a dataset from a Toy Store E-Commerce platform, comprising the following tables:

website_sessions.csv: User session data, including source, campaign, device type, and whether it was a repeat session.
website_pageviews.csv: Records of page views within each session.
orders.csv: Details of customer orders, including price and associated session.
order_items.csv: Information about individual items within orders.
order_item_refunds.csv: Data on refunded order items.
products.csv: Product catalog information.
maven_fuzzy_factory_data_dictionary.csv: A data dictionary providing definitions for all columns across the datasets.
Analyses Performed
Three key analyses were conducted to address specific business questions related to marketing effectiveness, user experience, and customer value:

1. Paid vs. Other Marketing Channels Conversion Rate
Business Hypothesis: Sessions originating from 'gsearch' (Google Search) will exhibit a higher conversion rate to orders compared to sessions originating from 'bsearch' (Bing Search), or more broadly, 'paid' channels will have a higher conversion rate than 'other' channels.

Key Findings:

Observed Conversion Rates: Paid channels had a conversion rate of 6.85%, while 'Other' channels had a conversion rate of 6.70%.
Statistical Significance: A two-sample proportion z-test yielded a p-value of 0.0900. With a significance level (α) of 0.05, we failed to reject the Null Hypothesis. This means there was no statistically significant evidence to conclude that paid marketing channels lead to a higher conversion rate compared to other marketing channels based on the provided data.
2. Desktop vs. Mobile Conversion Rate
Business Hypothesis: Desktop users will exhibit a higher conversion rate to orders compared to mobile users.

Key Findings:

Observed Conversion Rates: Desktop users converted at approximately 8.50%, significantly higher than mobile users at approximately 3.09%.
Statistical Significance: A two-sample proportion z-test resulted in a p-value of 0.0000. Since this was less than the significance level (α = 0.05), we rejected the Null Hypothesis. There is statistically significant evidence that desktop users have a higher conversion rate compared to mobile users.
3. New vs. Returning Customer Average Order Value (AOV)
Business Hypothesis: Returning customers will exhibit a higher Average Order Value (AOV) compared to new customers.

Key Findings:

Observed Average Order Values: Returning customers had an AOV of approximately  60.54∗∗,whichwasslightlyhigherthannewcustomerswithanAOVofapproximately∗∗ 59.86.
Statistical Significance: An independent two-sample t-test yielded a p-value of 0.0044. As this was less than the significance level (α = 0.05), we rejected the Null Hypothesis. There is statistically significant evidence that returning customers have a higher Average Order Value compared to new customers.
Combined Business Recommendations
Based on the comprehensive analysis, the following actionable business recommendations are proposed:

Re-evaluate and Refine Paid Marketing Strategy:

Avoid increasing investment in paid marketing channels solely based on a conversion rate advantage at this time, as no statistically significant difference was found in conversion rates between 'paid' and 'other' channels.
Conduct deeper analysis into other performance metrics for paid channels, such as Cost Per Acquisition (CPA), Return on Ad Spend (ROAS), or Customer Lifetime Value (LTV) to determine their true value.
Investigate 'other' marketing channels more deeply to identify specific high-performing sources and potential areas for increased investment.
Implement more granular A/B testing within paid channels (e.g., specific campaigns, ad copy, landing pages) to uncover elements that could improve conversion.
Prioritize Mobile Experience Optimization:

Given the substantial disparity in conversion rates (Desktop 8.50% vs. Mobile 3.09%), a primary focus should be on thoroughly optimizing the mobile user experience. This is the most significant area for improvement identified.
Conduct detailed analysis of the mobile user journey to identify specific pain points or pages where users are dropping off (e.g., slow loading times, complex navigation, cumbersome checkout process).
Implement targeted A/B tests on mobile-specific design changes, call-to-action placements, and checkout flow improvements to iteratively boost conversion rates for mobile users.
Consider device-specific marketing strategies that tailor content and offers to the mobile user's context and behavior.
Leverage and Enhance Returning Customer Value:

While returning customers show a statistically significant, albeit slightly higher, Average Order Value ( 60.54vs. 59.86), this indicates their inherent value.
Future strategies should explore how to further increase the AOV for returning customers through targeted initiatives such as personalized product recommendations, exclusive loyalty programs, tiered discounts, or bundle offers.
Focus on customer retention strategies to increase the frequency of purchases from returning customers, as they contribute more revenue per transaction over time.
Summary:
Q&A
The comprehensive report was successfully generated, summarizing the hackathon's objective, detailed analyses, key findings, and actionable business recommendations.

Data Analysis Key Findings
Paid vs. Other Marketing Channels Conversion Rate: Paid channels had a conversion rate of 6.85%, slightly higher than 'Other' channels at 6.70%. However, a two-sample proportion z-test (p-value = 0.0900) indicated no statistically significant difference, meaning the observed difference could be due to random chance.
Desktop vs. Mobile Conversion Rate: Desktop users demonstrated a significantly higher conversion rate of 8.50% compared to mobile users at 3.09%. A two-sample proportion z-test (p-value = 0.0000) confirmed this difference as statistically significant.
New vs. Returning Customer Average Order Value (AOV): Returning customers had a statistically significantly higher Average Order Value (AOV) of $60.54, compared to new customers at $59.86. An independent two-sample t-test (p-value = 0.0044) supported this finding.
Insights or Next Steps
Refine Paid Marketing Strategy: Avoid increasing investment in paid channels solely based on conversion rate, as no significant advantage was found. Instead, investigate other metrics like Cost Per Acquisition (CPA) or Return on Ad Spend (ROAS), and explore optimization within 'other' channels.
Prioritize Mobile Experience Optimization: The substantial difference in conversion rates between desktop and mobile (8.50% vs. 3.09%) highlights an urgent need to optimize the mobile user experience, focusing on identifying pain points and implementing targeted A/B tests.
