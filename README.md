# Social_Media
  Project status(Active)

# Project objective
  This project meticulously explores social media influence across Instagram, TikTok, and YouTube, utilizing diverse datasets of top influencers. Through rigorous data cleaning, preprocessing, and standardization of metrics like subscriber counts and engagement rates, we analyze audience scale, conduct statistical outlier detection, and specifically investigate engagement dynamics across various influencer tiers. By comparing trends, content categories, and audience geography, the objective is to reveal comprehensive insights into platform-specific audience engagement and the fundamental anatomy of online influence within the digital landscape Leveraging datasets that provide insights into top influencers across various platforms, such as the one available on Kaggle (https://www.kaggle.com/datasets/ramjasmaurya/top-1000-social-media-channels).

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
  - Python: As the core programming language, Python has powered every stage of this project. It has been instrumental in writing custom functions for complex data cleaning (such as converting "K" and "M" suffixes to numeric values), standardizing influencer names for cross-platform matching, implementing analytical logic for diverse analyses including influencer tier segmentation and dynamic engagement rate calculations, statistical outlier detection, and cross-platform comparisons. Python has also been key in orchestrating the entire data preprocessing pipeline for enhanced robustness and maintainability, allowing for flexible analysis of heterogeneous datasets.
  - Pandas: This library has been absolutely indispensable for all data handling. We've heavily relied on Pandas DataFrames to efficiently read and manage diverse CSV files, perform intelligent data cleaning to address inconsistent column names and ensure data type consistency, and execute complex data manipulations. Its capabilities have been central to centralized column mapping and the creation of standardized DataFrames, facilitating seamless data flow into various analytical modules. We've used it extensively for filtering for specific content niches, grouping data for aggregation, and merging datasets for comprehensive overlap analysis.
  - Matplotlib: Serving as the foundational plotting library, Matplotlib has provided precise control over every visualization. We've leveraged it to customize elements, ensuring our charts are clear and informative, and to produce a wide array of static plots for various analytical views.
  - Seaborn: Built on top of Matplotlib, Seaborn has significantly enhanced the aesthetic appeal and statistical informativeness of our graphics. We've used it extensively for creating:
    - Histograms, Box Plots, and Violin Plots: To visualize data distributions and identify outliers in metrics like subscriber counts and engagement rates.
    - Bar Plots: For comparing averages across platforms, content categories, and influencer tiers, as well as illustrating influencer overlap.
    - Scatter Plots (with Regression Lines): To explore and visualize correlations between different quantitative metrics, such as subscribers vs. engagement.
    - Heatmaps: For a quick overview of correlations across multiple numerical features.
    
# Project Description
  This project utilizes a rich collection of publicly available datasets, notably from Instagram, TikTok, and YouTube, to dissect and understand prominent social media channels and influencers.

  Our analysis provides a multifaceted view of the contemporary social media landscape through:
  - Comprehensive Data Processing: We integrate and meticulously clean heterogeneous datasets, handling inconsistencies and converting raw metrics (e.g., "K" and "M" suffixes) to ensure data type consistency. This also includes standardizing influencer names for cross-platform comparisons.
  - Key Performance Indicators: We analyze crucial quantitative metrics like subscriber/follower counts, engagement rates (derived from views, likes, comments, and shares), and qualitative attributes such as content categories and audience geography.
  - In-depth Analysis & Insights: Our work encompasses:
    - Influencer Tier Segmentation: Categorizing influencers by audience size.
    - Correlation Analysis: Exploring relationships between various metrics.
    - Engagement Rate Deep Dive: Understanding true audience interaction.
    - Content Niche Performance: Comparing success within specific content categories across platforms.
    - Cross-Platform Presence: Identifying influencers active on multiple platforms.

  By integrating and analyzing these diverse datasets, this project aims to construct a holistic understanding of what defines success and influence within the dynamic social media ecosystem.

# Steps
  - Handling Data Heterogeneity & Column Mapping: Right from the start, we confronted significant inconsistencies in column names across the Instagram, TikTok, and YouTube datasets (e.g., different casing, use of spaces vs. underscores, varied terminology). This immediately highlighted the crucial need for meticulous column mapping and a robust, consistent cleaning process, which has been foundational for enabling any effective merging and analysis.
  - Navigating Platform-Specific Metrics: While common metrics like subscriber counts and engagement indicators (likes, comments, views) exist, their specific naming and availability often differ between platforms. This necessitated a flexible approach, building platform-specific data preparation and column mapping to allow for both individual platform insights and careful, valid cross-platform comparisons.
  - Ensuring Robust Data Type Consistency: A persistent challenge has been the need to explicitly convert various metrics (like subscriber counts, average likes, comments, and shares) to numeric data types. Data imported from CSVs frequently contained text representations (e.g., "1.2M", "50K"), which prevented numerical operations. Our implemented cleaning steps, including custom functions to convert "K" and "M" suffixes, ensure these columns are accurately prepared for all calculations and visualizations.
  - Leveraging Visual Exploration: Throughout the entire process, visual exploration has served as a critical guiding principle. Utilizing visualizations such as histograms, bar plots, box plots, violin plots, and scatter plots allowed us to quickly understand data distributions, identify potential outliers, and grasp initial relationships between variables within each platform, directly influencing subsequent deeper analyses.
  - Modular Approach for Scalability and Clarity: We've consistently adopted a modular approach by creating separate, focused code blocks and functions for distinct analytical tasks. This includes functionalities for subscriber distribution, content categories analysis, influencer tier segmentation, correlation analysis, and engagement rate calculation. This structure has significantly enhanced project organization, simplified debugging, and made the project highly adaptable for future expansions.
  - Focusing on Engagement Rate: A significant analytical step has been the development of a dedicated Engagement Rate Analysis. This critical metric normalizes audience interactions by audience size, providing a powerful and standardized way to assess the true impact and audience loyalty of influencers. We've implemented specific calculations and visualizations to compare engagement dynamics across platforms and influencer tiers.
  - Deep Diving into Content Niche Performance: We extended our analysis to perform detailed deep dives into specific content categories (niches). This involves filtering influencers by their primary content type and then comparing key performance metrics (like average subscribers and average engagement rates) for those specific niches across all platforms, offering targeted strategic insights.
  - Analyzing Influencer Overlap / Cross-Platform Presence: A key aspect of understanding the ecosystem has been to identify and quantify influencers with a presence across multiple social media platforms. This involves standardizing influencer names for accurate matching and then calculating the unique and overlapping sets of creators, revealing patterns of multi-channel influence. While currently undergoing debugging due to name inconsistencies, this analysis remains a crucial component of our holistic understanding.

# Conclusion
  This project has thoroughly analyzed social media influencer data from Instagram, TikTok, and YouTube, focusing on a multi-faceted understanding of digital influence. We've conducted in-depth explorations of audience scale through segmented subscriber tiers, normalized engagement rates, diverse content categories, and audience geography.

  Our process has involved rigorous and robust data cleaning and preparation, including handling diverse data formats and standardizing metrics through a centralized preprocessing pipeline. This allowed us to perform sophisticated analyses such as identifying high-performing outliers, comparing content niche performance across platforms, and notably, examining how engagement rates vary specifically across different influencer tiers. We have also initiated influencer overlap detection, which continues to be a point of refinement.

  Through these comprehensive analyses and targeted visualizations, we've achieved a holistic understanding of what drives success and influence on each platform, and how they compare within the dynamic social media landscape, providing valuable insights into platform-specific audience engagement dynamics.
    
# Contact
  linkedin, github, medium, etc 