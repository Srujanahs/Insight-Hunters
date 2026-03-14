# Insight-Hunters
# BrewIQ – Executive Summary

This project analyzes more than **1.5 million beer reviews** to understand what factors influence beer quality and consumer preferences. The dataset includes information about beer styles, sensory attributes (aroma, taste, appearance, and palate), brewery details, and reviewer ratings. The objective was to uncover patterns in beer ratings, identify highly rated styles, analyze reviewer behavior, and build predictive and recommendation models.

The datasets were first merged and cleaned to create a unified dataset. The final cleaned dataset contained **over 2.7 million rows**, with missing values handled, duplicate records removed, and inconsistent text fields standardized. This ensured reliable data for analysis.

Analysis of beer styles revealed that **specialty and complex styles** such as *Gueuze*, *American Wild Ale*, and *Quadrupel* consistently received the highest ratings, while styles such as *Low Alcohol Beer*, *Light Lager*, and *American Malt Liquor* received the lowest ratings. This suggests that beer enthusiasts tend to prefer richer and more complex flavor profiles.

A correlation analysis of sensory attributes showed that **taste is the most influential factor** in determining overall beer ratings, followed by palate and aroma. Appearance had the least influence on the final score, indicating that flavor plays a much larger role than visual appeal.

The study also examined the relationship between brewery size and beer quality. Larger breweries showed slightly higher average ratings and more consistent quality, although smaller breweries still produced some highly rated beers, indicating potential for innovation.

Reviewer behavior analysis showed that experienced reviewers tend to provide **more consistent and moderate ratings**, while reviewers with fewer reviews often give extreme scores. This suggests that experience leads to more balanced and reliable evaluations.

Finally, a machine learning model was developed to predict top-rated beers using sensory attributes. The model achieved **81% accuracy**, and feature importance analysis confirmed that **taste and palate are the strongest predictors of beer quality**.

Overall, the findings show that improving taste and palate characteristics is the most effective strategy for producing highly rated beers, and data-driven insights can help brewers design products that better match consumer preferences.
