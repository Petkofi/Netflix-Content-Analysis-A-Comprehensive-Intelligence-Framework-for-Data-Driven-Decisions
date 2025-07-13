# Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

![Netflix Content Analysis](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/netflix-hero-image-github.jpg)

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Introduction  
This project harnesses a triad of analytical power-Excel, Python, and Tableau-to dissect authentic Netflix viewership data from Kaggle. Through this multi-tool approach, we reveal actionable intelligence to refine content strategy, enhance audience engagement, and drive data-informed decision-making for streaming platforms.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Company Background  
Netflix stands as the world's leading streaming platform, delivering an expansive catalog of films and series to viewers across 190+ countries. Its on-demand model has redefined entertainment consumption, making premium content accessible anytime, anywhere.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Data Set  
The dataset utilized in this analysis is sourced from Kaggle, offering comprehensive information about Netflix's content library. This dataset provides detailed information about Netflix's extensive library, encompassing both movies and TV shows. It includes unique identifiers for each title, the type of content (movie or TV show), titles, directors, cast members, production countries, the date content was added to Netflix, release years, and TV ratings.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Problem Statement 
This analysis seeks to decode Netflix's content strategy by examining the relationship between key variables—including content format (movies vs. series), language localization, release timing (seasonal/quarterly), and production attributes—and their collective impact on viewership performance.

#### Core Objectives:
- Performance Benchmarking
- Identify high-engagement content traits (genres, languages, formats)
- Quantify the ROI of localization strategies

#### Temporal Analysis
- Map release cadence to viewership spikes
- Determine optimal launch windows for different content types

#### Strategic Insights
- Reverse-engineer Netflix's data-driven content decisions
- Surface actionable opportunities for inventory optimization

#### Business Impact:
The findings will empower content strategists to:
- Allocate production budgets more effectively
- Tailor regional catalogs based on proven performance drivers
- Anticipate engagement patterns through temporal analytics

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Data Preparation and Data Quality Checks
The dataset contained 24,812 records with significant quality issues requiring remediation: 67% missing release dates (16,646 nulls) and improperly formatted "Hours Viewed" values (e.g., "81,21,00,000"). Key preparation steps included converting string-based viewership metrics to numeric values, standardizing datetime formats for release dates, and filtering to 2023 content (yielding 786 analyzable records). Temporal features (seasons/quarters) were engineered, and categorical variables were validated-Language Indicator (6 unique values) and Content Type (2 values) showed complete data integrity. The cleaned dataset now supports robust analysis of 2023 viewing patterns across content types, languages, and release timing, with all numerical and temporal fields standardized for analytical operations.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Content Type Performance Analysis
![Netflix Content Type Performance Analysis](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Content%20Type%20Performance%20ANalysis.png)

### Key Findings:
- Shows lead with 21.8B total hours viewed (63.3% market share)
- Movies generated 12.6B hours viewed (36.7% market share)
- Shows average 45.4M hours per title vs Movies at 41.3M hours per title
- 480 shows vs 306 movies released in 2023
  
![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Top Content Titles by Views
![Netflix Top Content Titles by Views Analysis](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Top%20%20Content%20Titles%20by%20Views.png)

### Key Findings:
- Shows: The Night Agent (812M), Ginny & Georgia S2 (665M), ONE PIECE (542M)
- Movies: King the Land (630M), Queen Charlotte (503M), Who is Erin Carter? (286M)
- The visualization shows clear performance gaps - The Night Agent dominates shows at 812M hours, while King the Land leads movies at 630M hours. Shows generally achieve higher peak viewership than movies.
  
![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Demographic Data Analysis
![Netflix Demographic Data Analysis](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Demographic%20Data%20Analysis.png)

### Key Findings:
- English content: 72.4% of titles
- Non-English content: 27.6% of titles
- Globally available content: 87.5%
  
![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Seasonal Viewership Trends
![Netflix Seasonal Viewership Trends](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Seasonal%20Viewership%20Trends.png)

### Key seasonal insights:
- Q1 (Jan-Mar) dominates with highest total viewership
- August shows highest average performance per title (80M hours)
- December has lowest performance, likely due to holiday competition
- Summer months (Jul-Aug) have fewer releases but higher per-title performance

  
![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)


## Key Findings  

### Content Distribution  
- **Movies:** 68.42%  
- **TV Shows:** 31.58%  
- Movies dominate Netflix's library, comprising 68.42% (4,265 titles), while TV shows make up 31.58% (1,969 titles).  
- Netflix offers a diverse array of content, catering to a wide range of viewer preferences.

### Countries with the Most Content  
- **Top 5 Countries:** United States, India, United Kingdom, Japan, Canada  
- Netflix sources content globally, appealing to a diverse international audience.

### Ratings  
- **Top 5 Ratings:** TV-MA, TV-14, TV-PG, R, PG-13  
- TV-MA and TV-14 are the most common, balancing mature and family-friendly programming.

### Top Genres  
- Documentaries, Stand-Up Comedy, Dramas, International Movies, Kids' TV  
- Broad range of content for different demographics.

### Trend Over the Years  
- Consistent growth in movies and TV shows, reflecting Netflix's commitment to expanding its library.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Implications and Recommendations  
### Content Strategy  
- Invest in original TV series to complement the movie-heavy library.  
- Expand content from high-contributing countries for global appeal.

### Targeted Marketing  
- Leverage popular genres (Documentaries, Stand-Up Comedy) in campaigns.  
- Highlight region-specific content to local audiences.

### Enhanced User Experience  
- Refine recommendation algorithms using viewing habits.  
- Introduce curated playlists for better content discovery.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Conclusion  
This project demonstrates how Excel, Python, and Tableau can extract strategic insights from Netflix's data, enabling data-driven decisions about content and user engagement.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

<img src="https://raw.githubusercontent.com/BEPb/BEPb/194bc176c0b3f2ef01a883ff206499b86c5ce72f/assets/Bottom_down.svg" width="100%" />

<h4 align="left">
  <a href="https://sites.google.com/view/jagadeeshr">Show More 🔍</a>
</h4>
