# Social_Media
  Project status(Active)

# Project objective
  Embarking on an exploration of the dynamic world of social media influence, this project aims to dissect and understand the key characteristics and performance metrics of leading social media channels across Instagram, TikTok, and YouTube. Leveraging diverse datasets that provide insights into top influencers, the objective is to identify patterns, correlations, and comparative trends in success within the digital landscape. By cleaning, processing, and analyzing data encompassing metrics like subscriber counts, normalized engagement rates, and content categories, this project seeks to provide a comprehensive overview of the top echelon of social media, ultimately revealing valuable insights into platform-specific audience engagement dynamics and the anatomy of online influence. Leveraging datasets that provide insights into top influencers across various platforms, such as the one available on Kaggle (https://www.kaggle.com/datasets/ramjasmaurya/top-1000-social-media-channels).

# Methods
  List with methods:
  - Filtering:
    - Selecting influencers based on a minimum number of subscribers.
    - Isolating data for specific audience countries.
    - Focusing on particular content categories.
    - Examining influencers within a specific range of engagement rates.
  - Grouping:
    - Calculating average engagement rates by content category.
    - Determining the median subscriber count for influencers in different countries.
    - Summarizing key statistics (mean, median, max, min) for engagement metrics per platform.
    - Grouping by influencer name to identify potential duplicates across different datasets (though you've already addressed this).
  - Sorting:
    - Ranking influencers by subscriber count (overall and per platform).
    - Listing top-performing content categories based on average engagement.
    - Identifying countries with the highest average engagement rates.
  - Aggregation:
    - Calculating total subscriber counts for each platform.
    - Finding the average engagement rate across all influencers.
    - Determining the number of unique influencers in each dataset.
  - Visualization:
    - Histograms to show the distribution of subscriber counts or engagement rates.
    - Bar charts to compare average engagement across categories or platforms.
    - Scatter plots to explore the relationship between subscribers and engagement.
    - Pie charts to illustrate the proportion of influencers from different audience countries.
    - Box plots to visualize the spread and central tendency of numerical metrics across different groups.
  - Calculating New Metrics:
    - Engagement Ratio: (Total Engagements / Number of Followers) * 100
    - Normalized Engagement: Scaling engagement metrics to a common range for comparison.
    - Subscriber Growth Rate (if temporal data is available within a merged file).
  - Basic Statistical Analysis:
    - Calculating correlations between different numerical variables (e.g., subscribers and views).
    - Performing t-tests or ANOVA to compare the means of engagement metrics across different groups (e.g., categories).

# Technologies 
  List with used technologies:
  - Python: This is the core programming language we've used for every step—from loading your data to performing complex analyses and generating stunning visualizations.
  - Pandas: Absolutely crucial for handling your .csv files. We've relied heavily on Pandas DataFrames to read, clean, combine, and manipulate all your influencer data.
  - Matplotlib: The foundational Python library for creating all the static plots and charts. We've used it for precise control over elements like log scales and axis formatting (especially with ScalarFormatter).
  - Seaborn: Built on top of Matplotlib, Seaborn has been key for creating more aesthetically pleasing and informative statistical graphics. We've used it for box plots, violin plots, bar plots, histograms, and scatter plots with regression lines to visualize distributions, comparisons, and correlations.

# Project Description
  This project leverages a rich collection of publicly available datasets to dissect and understand prominent social media channels and influencers. Our primary data sources include aggregations of leading profiles across Instagram, TikTok, and YouTube, notably incorporating information similar to what's found in datasets like Kaggle's "Top 1000 Social Media Channels."

  These datasets provide a multifaceted view of the contemporary social media landscape, characterized by a diverse array of features:
  - Quantitative Metrics: We analyze key performance indicators such as subscriber/follower counts, average views, likes, comments, and shares. These metrics offer crucial insights into audience scale and engagement levels. We further process these to calculate Engagement Rates, providing a normalized view of audience interaction.
  - Qualitative Attributes: To add context, we utilize features like content categories, which shed light on the types of content being produced. Additionally, audience demographics, particularly country-specific audience distribution, offer insights into the geographical reach of influencers.
  
  By integrating and analyzing these diverse yet related datasets, this project aims to construct a holistic understanding of what defines success and influence within the dynamic social media ecosystem. Our analysis includes tier segmentation of influencers based on follower size, correlation analysis between various metrics, and cross-platform comparisons to highlight unique dynamics of each social media giant.

# Steps
  - Handling Data Heterogeneity: Right from the start, we noticed significant inconsistencies in column names across your Instagram, TikTok, and YouTube files. Things like different casing, spaces versus underscores, and varied terminology (e.g., 'subscribers count' vs. 'followers') made it clear that a robust and consistent cleaning process was crucial. This meticulous mapping of columns has been foundational for any meaningful analysis.
  - Navigating Platform-Specific Metrics: While core metrics like subscriber counts and engagement indicators (likes, comments, views) are common, their specific naming and availability often differ between platforms. This highlighted the need for platform-specific data preparation and flexible column mapping to allow for both individual platform insights and careful cross-platform comparisons. We've built our functions to adapt to these variations.
  - Ensuring Data Type Consistency: We've continually emphasized the importance of explicitly converting metrics like subscriber counts and average engagement figures to numeric data types. Data imported from CSVs often comes in as text, which prevents mathematical operations and accurate visualizations. Our cleaning steps ensure that these columns are ready for analysis.
  - Leveraging Visual Exploration: Throughout the process, visual exploration has been a key first step. Using visualizations like histograms, bar plots, box plots, violin plots, and scatter plots has allowed us to quickly understand data distributions, identify potential outliers, and grasp the relationships between variables within and across platforms. This visual intuition guided our deeper analyses.
  - Modular Approach for Scalability: We've adopted a modular approach by creating separate, focused code blocks and functions for distinct analytical tasks (like subscriber distribution, content categories, tier segmentation, correlation analysis, and engagement rate calculation). This structure makes the project more organized, easier to debug, and highly adaptable for future expansions.
  - Focusing on Engagement Rate: A significant step has been the development of a dedicated Engagement Rate Analysis. This critical metric normalizes interactions by audience size, providing a powerful way to assess the true impact and audience loyalty of influencers, beyond just their follower count. We've implemented specific calculations and visualizations to compare engagement across platforms and tiers.

# Conclusion
  This project analyzed social media influencer data from Instagram, TikTok, and YouTube to understand the dynamics of online influence. We focused on key areas including audience scale (subscriber distribution and influencer tiers), engagement rates, content categories, and audience geography.

  Through data cleaning, comprehensive analysis, and targeted visualizations (like scatter plots and tiered breakdowns), we've gained a holistic understanding of what defines success on each platform and how they compare. The insights gathered provide a strong foundation for understanding the diverse landscape of social media influence.
    
# Contact
  linkedin, github, medium, etc 