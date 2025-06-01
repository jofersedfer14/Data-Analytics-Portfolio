**Project Overview**
The “Beyond Demographics” project applies clustering techniques to retail customer data in order to uncover meaningful segments based on lifestyle and purchasing behavior. Using a comprehensive Customer Personality Analysis dataset from Kaggle, I performed data cleaning, feature engineering (including RFM-style metrics), and unsupervised learning to identify groups of customers with distinct income levels, product‐category spending, recency of engagement, and web activity. Visualizations—such as radar charts and PCA scatterplots—highlight the differences among these segments and reveal actionable patterns for targeted marketing.

**Project Goals**
• Discover distinct customer segments that go beyond basic demographic splits.
• Illuminate how behavioral factors (e.g., total spend, recency, tenure) drive customer value.
• Provide retailers with clear, data-driven personas and strategic recommendations for personalized outreach.

**Methods & Tools**
• **Data Preparation:** Python (pandas, NumPy) for cleaning missing income values, engineering Age and Customer\_Tenure features, and one-hot encoding of education and marital status.
• **Clustering Analysis:** Scikit-learn’s K-Means algorithm to partition customers into four clusters, with the Elbow Method determining the optimal k.
• **Visualization:** Matplotlib and seaborn for radar charts; scikit-learn’s PCA and matplotlib for two-dimensional cluster plots.
• **Evaluation:** Silhouette Scores and cluster summary statistics to validate cohesion and interpret each group’s characteristics.

**Key Findings**
• Four clear segments emerged: a high-income/high-spend cohort, a younger/low-engagement group, a moderate-income/steady buyer segment, and an older/moderate-spend cluster.
• Cluster 2 (high-value spenders) showed average incomes 30% above the dataset mean and campaign response rates over 25%.
• Cluster 1 (low-engagement) had incomes 20% below average, minimal campaign responses, and represented an opportunity for reactivation.
• Radar charts and PCA plots confirmed that each segment occupies distinct behavioral profiles, enabling the business to tailor marketing messages and loyalty programs.
• Actionable insights include deploying exclusive perks to high-value customers, re-engagement offers for low-activity segments, and milestone rewards for long-tenure, moderate-spend customers.

