# Project 90s Classic Hits 🎵 🛼

## The Analyst Team 👓
### 📝 Bana, Flory, Johana, Mehdi 📝

# Project Overview
The "1990s Classic Hits Analysis Project" is a comprehensive data analysis initiative aimed at exploring the musical landscape of the 1990s through the lens of popular tracks from various countries. The primary objective of this project is to harness data-driven techniques to identify and analyze the most iconic 90s hits across the United States, United Kingdom, Germany, and France. By employing sophisticated data analysis methods, we sought to uncover patterns, correlations, and insights that not only highlight the musical trends of the decade but also offer actionable recommendations for curating targeted Spotify playlists. This project also emphasizes the importance of data quality, ensuring that the insights derived are both accurate and relevant.

## Questions: ❓
The project is driven by several key research questions that guided our data analysis and informed our final recommendations:

### 1. What were the top 90s hits in the US, UK, Germany, and France?
• Identification of the most popular tracks in each country based on Spotify data.

### 2. How do these hits compare across these countries in terms of popularity and artist following?
• Comparative analysis of track popularity and artist metrics across different regions.

### 3. What patterns or trends can be identified in the 1990s music era?
• Exploration of musical trends, genre dominance, and artist influence during the 1990s.

### 4. How can data quality issues be addressed to improve the accuracy of the analysis?
• Identification and resolution of data quality issues to ensure the validity of the findings.

### 5. How can we ensure that the resulting playlists are both accurate and relevant to the target audience?"
• Development of a methodology for creating playlists that resonate with the preferences of listeners in each target region.

## Dataset 📝
The dataset utilized for this project is a combination of data from multiple sources, including Spotify's API and external datasets, providing the foundation for exploring the 1990s music scene and addressing the research questions.

## Sources of Data ℹ️
### • Kaggle Dataset:
1990s Classic Hits (with Spotify Data) - A dataset containing 980 tracks by 536 artists, spanning the years 1990-1999. This dataset served as a primary source for identifying popular tracks during the 1990s.

### • Data.world Dataset:
Decay of 90s Pop Song Recognition - This dataset measures how recognizable 90's pop songs are, based on the age of the listener when the song premiered. It provided additional insights into the cultural impact and recognition of 90s hits.

### • Spotify API:
Spotify Web API - Used to retrieve metadata from Spotify content, control playback, and get track recommendations. This API was instrumental in gathering real-time data on track popularity and artist metrics across different regions.

### • Main Dataset Issues:
Throughout the analysis, several key data quality issues were identified and addressed to ensure the integrity of the findings:

### • Inconsistent Data Formats:
The initial data extracted from Spotify exhibited inconsistencies in formatting, particularly in track and artist names. This required standardization to allow for accurate comparisons and analysis.

### • Missing Values:
A significant challenge was the presence of null values, particularly in columns related to track popularity and artist follower counts. These missing values had the potential to skew the analysis if not properly handled.

### • Duplicate Entries:
The dataset contained multiple instances of the same track or artist, often due to variations in naming conventions or data retrieval inconsistencies. This redundancy needed to be resolved to prevent overrepresentation in the analysis.

### • Unnecessary Columns:
Several columns in the raw dataset were irrelevant to the analysis and were subsequently removed to streamline the data and focus on key metrics.

### • String Manipulation:
Many track and artist names required cleaning to address inconsistencies, such as variations in capitalization, special characters, and whitespace.

## Solutions for the Dataset Issues
To address the aforementioned issues, a comprehensive data cleaning and wrangling process was implemented:

### • Data Standardization:
Track and artist names were standardized through string manipulation techniques, ensuring consistency across the dataset. This involved the removal of extraneous characters, normalization of capitalization, and trimming of unnecessary whitespace.

### • Handling Missing Values:
A robust imputation strategy was developed to address missing data. This included using median or mode imputation for numeric fields and appropriate default values for categorical fields.

### • Duplicate Removal:
A systematic approach was taken to identify and remove duplicate entries, ensuring that each track and artist was uniquely represented in the analysis.

### • Column Reduction:
Non-essential columns were dropped from the dataset, focusing the analysis on the most relevant features such as track popularity, artist followers, and genre information.

### • Data Filtering Using d3:
The d3 DataFrame was used to filter the dataset, ensuring that only tracks from the 1990s that were relevant to the research questions were included in the final analysis. This filtering process was critical in refining the dataset and enhancing the accuracy of the findings. Exploratory Data Analysis (EDA) A key component of this project was the application of sophisticated Exploratory Data Analysis (EDA) techniques to uncover insights and validate hypotheses:

### • Comprehensive Data Analysis:
The EDA process involved univariate, bivariate, and multivariate analysis to explore the relationships between different variables, such as track popularity, artist followers, and genre trends. Numerical measures and graphical methods were employed to analyze data distributions, correlations, and patterns.

### • Visualizations:
High-quality visualizations were created using Python libraries such as Matplotlib, Seaborn, and Plotly. These visualizations were designed to communicate complex data insights in a clear and concise manner, making it easier to identify key trends and patterns.

### • Inferential Statistics:
Inferential statistical methods, including hypothesis testing and correlation analysis, were used to assess the significance of relationships within the data. Data transformations were applied as needed to ensure normality and improve the reliability of the analysis.

## Conclusions ☑️
The analysis yielded several important findings that have practical implications for both the music industry and Spotify playlist curation:

### • Key Trends Identified: The project successfully identified the most popular 90s tracks across the US, UK,
Germany, and France, highlighting significant differences and similarities in musical tastes across these regions.

### • Actionable Insights:
Data-driven insights from the analysis informed the creation of three targeted Spotify playlists, each tailored to the musical preferences of listeners in the respective countries. These playlists are expected to resonate strongly with the target audience and enhance user engagement on the platform.

### • Improved Data Quality:
The data cleaning and filtering processes significantly improved the quality of the dataset, ensuring that the analysis was based on accurate and reliable information. This foundation allowed for more confident decision-making and more effective playlist curation.

## Next Steps ⏭️
Building on the findings of this project, several potential next steps have been identified:

### • Expand Geographic Scope:
Future analysis could expand the geographic scope to include additional countries and regions, allowing for a broader comparison of musical trends across different cultures and markets.

### • Incorporate Additional Decades:
While this project focused on the 1990s, similar analyses could be conducted for other decades, providing a more comprehensive understanding of how musical tastes have evolved over time.

### • Integrate User Feedback:
Incorporating feedback from Spotify users on the curated playlists could provide valuable insights for further refining the playlists and enhancing user satisfaction.

• Automate Playlist Curation:
Exploring the use of machine learning algorithms to automate the playlist creation process could streamline operations and provide even more personalized recommendations to users based on their listening history and preferences.

• Continuous Improvement:
Ongoing efforts to monitor and improve data quality, coupled with regular updates to the playlists, will ensure that they remain relevant and engaging to listeners over time..
