# Steam Video Game Analysis with PySpark
This prokect analyzes the gloabl video game market available on Steam. Ubisoft
aims to understand current trends and foctors affecting video game popularity
and sales. 

## Goal:
Our primary goal is to identify which factors influence video game sucess. To do
so, we take a look at our data in multiple contexts:

- Macro-level: examine publisher trends, release patterns, pricing, and the
impact of different language and age availabilities
- Genres: exploring popular genres, review ratios and publisher preferences
- Platforms: identify dominant platforms and genre popularity across platforms

## Methods:
This project uses PySpark on Databricks 

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/7294029538160118/152976367992448/983894412173459/latest.html

Key methods for data manipulation include:
- Nested schema handling
- Text and data manipulation
- Segmented analysis

## Deliverables:
Published databricks notebook

## This analysis can inform Ubisoft on:
- Popular video game genres and trends
- Publisher strategies and preferences
- Factors with greatest impact on popularity and sales

## Key Findings:

### Publisher Landscape:
Independent Publishers Dominate: Indie developers account for a significant portion of Steam games, showcasing the platform's accessibility for smaller studios.  
Established Publishers Contribute: Larger publishers like Ubisoft and Deadalic Entertainment maintain a presence, indicating the platform's appeal across different scales.

### Genre Preferences:
Diverse Genre Offerings: Steam boasts a wide range of genres, with Indie, Action, and Casual leading in popularity.  
Indie Dominance: Indie games consistently rank among the most popular and well-rated genres.  
Genre-Specific Ratings: While most genres have average ratings around 75%, niche genres with low ratings tend to be less popular.

### Game Pricing:
Wide Price Range: Steam offers games at various price points, from free to over $999.
Positive Skew: The price distribution leans towards higher-priced games, indicating a significant portion of premium titles.  
Limited Discounts: Discounts are infrequent on Steam, with an average of 60% for discounted games.

### Platform Support:
Windows Dominance: Windows remains the primary platform for Steam games, with over 99% support.  
Mac and Linux Support: While Mac and Linux have lower support (around 29% and 19% respectively), a significant portion of Mac games also support Linux.

### Game Popularity and Ratings:
Positive Ratings Drive Popularity: Games with higher ratings tend to have more owners, especially when considering those with significant review counts.  
Early Access Impact: Early Access games often have lower ratings, suggesting a need for caution when evaluating pre-release titles.

### Seasonal Trends:
Holiday Season Surge: Game releases and sales peak during the holiday season, indicating strategic publisher behavior.  
Year-Round Releases: While there are seasonal fluctuations, game releases occur throughout the year.

### Additional Insights:
Age Ratings: Games with age ratings tend to have higher player bases and revenue, suggesting that unrated games might be less accessible or appealing.  
Developer Locations: Analyzing developer locations could reveal regional trends and preferences.