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
  - Python: The primary programming language used for data manipulation, analysis, and visualization.
  - Pandas: A powerful Python library essential for data manipulation and analysis, providing DataFrames for structured data.
  - Matplotlib: A fundamental Python library for creating static, interactive, and animated visualizations in Python.
  - Seaborn: A Python data visualization library built on top of Matplotlib, providing a higher-level interface for creating informative and attractive statistical graphics.

# Project Description
  The foundation of this project lies in a rich collection of datasets focused on prominent social media channels and influencers. The primary source for this analysis includes publicly available data, such as the "Top 1000 Social Media Channels" dataset from Kaggle, which aggregates information on leading profiles across various platforms like Instagram, TikTok, and YouTube. These datasets offer a multifaceted view of the social media landscape, characterized by a diverse array of features. Key characteristics include quantitative metrics such as subscriber counts, average views, likes, comments, and shares, providing insights into audience size and engagement levels. Furthermore, qualitative attributes like content categories and audience demographics (e.g., country) offer context into the type of content being produced and the geographical distribution of the audience. The datasets vary in their specific columns and level of detail, reflecting the unique data points tracked by different platforms and data aggregators. By integrating and analyzing these diverse yet related datasets, this project aims to construct a holistic understanding of what defines success and influence in the contemporary social media ecosystem.

# Steps
  - Data Heterogeneity: The initial examination of column names across the different files revealed significant inconsistencies in naming conventions (e.g., different casing, use of spaces vs. underscores, abbreviations, slight variations in terminology like 'subscribers count' vs. 'followers'). This highlighted the crucial need for a robust and consistent cleaning process to enable effective merging and analysis.
  - Platform-Specific Metrics: While there are common metrics like subscriber counts and engagement indicators (likes, comments, views), the specific naming and availability of these metrics can vary between platforms (Instagram, TikTok, YouTube) and even across different datasets for the same platform. This suggests that platform-specific analyses might yield more nuanced insights initially, followed by careful mapping for cross-platform comparisons.
  - Potential for Redundancy: The presence of columns with seemingly similar information but different names (e.g., multiple variations of 'subscribers' or average engagement metrics) within the merged DataFrames indicates the importance of identifying and potentially handling these redundant columns to avoid skewing analyses.
  - Importance of Data Type Consistency: The need to explicitly convert subscriber counts and average metrics to numeric data types underscores the fact that data read from CSV files might not always have the correct type for numerical operations and visualizations.
  - Visual Exploration as a Key First Step: The code examples for basic descriptive statistics and visualizations (histograms, bar plots, scatter plots) demonstrate the value of visually exploring the data early on to understand distributions, identify potential outliers, and get a feel for the relationships between variables within each platform.
  - Modular Approach for Cleaning and Analysis: The structure of creating separate code blocks (or functions, as in the more comprehensive example) for cleaning and analysis makes the project more organized and easier to manage, especially with multiple datasets involved.

# Conclusion
  So far, we've been working on analyzing social media influencer data from Instagram, TikTok, and YouTube. We've cleaned and merged the data, and started to explore things like engagement rates across these platforms. Initial looks suggest there might be some interesting differences in how engaging content is on each. For example, TikTok seems to have higher average engagement in our initial calculations or Instagram has a wider range of subscriber counts in our top influencers.

  We also took a peek at the distribution of subscribers. This gave us a first glimpse into the kind of content and creators present on each platform.

  This is just a starting point, and there's still a lot more to dig into with this data to really understand the dynamics of influencers on each platform and how they compare.
    
# Contact
  linkedin, github, medium, etc 