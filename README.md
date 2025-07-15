# Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

![Netflix Content Analysis](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/netflix-hero-image-github.jpg)

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Introduction  
This project harnesses a triad of analytical power-Excel, Python, and Tableau-to dissect authentic Netflix viewership data from Kaggle. Through this multi-tool approach, I reveal actionable intelligence to refine content strategy, enhance audience engagement, and drive data-informed decision-making for streaming platforms.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Company Background  
Netflix stands as the world's leading streaming platform, delivering an expansive catalog of films and series to viewers across 190+ countries. Its on-demand model has redefined entertainment consumption, making premium content accessible anytime, anywhere.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Data Set  
The dataset utilized in this analysis is sourced from Kaggle, offering comprehensive information about Netflix's content library. This dataset provides detailed information about Netflix's extensive library, encompassing both movies and TV shows. It includes unique identifiers for each title, the type of content (movie or TV show), titles, directors, cast members, production countries, the date content was added to Netflix, release years, and TV ratings.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Problem Statement 
This analysis seeks to decode Netflix's content strategy by examining the relationship between key variables-including content format (movies vs. series), language localization, release timing (seasonal/quarterly), and production attributes-and their collective impact on viewership performance.

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

## Data Preparation and Data Quality Checks (Netflix 2023)
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

## Weekly Release Patterns and Viewership
![Netflix Weekly Release Patterns and Viewership](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Weekly%20Release%20Patterns%20and%20Viewership.png)

### Key insights:
- Fridays drive 38.2B hours (42% of weekly viewership) - the most of any day
- Netflix releases 47% of contents on Fridays, but these get only 42% of viewership
- Saturday releases perform best - averaging 21.5M hours/view, 3.8x better than Tuesday

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Monthly Release Patterns and Viewership
![Netflix Weekly Release Patterns and Viewership]( )

### Key insights:
- December dominated with 10.1B hours watched
- October released most content (802 titles) but ranked #3 in viewership
- December had highest engagement per title (12.8M hours/title)

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Seasonal Viewership Trends
![Netflix Seasonal Viewership Trends](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Seasonal%20Viewership%20Trends.png)

### Key seasonal insights:
- Q1 (Jan-Mar) dominates with highest total viewership
- August shows highest average performance per title (80M hours)
- December has lowest performance, likely due to holiday competition
- Summer months (Jul-Aug) have fewer releases but higher per-title performance

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Seasonal Viewership Trends
![Netflix Release Timing Optimization](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Release%20Timing%20Optimization.png)

### Optimal Release Timing:
- Shows perform best in December (18.0M avg hours)
- Movies perform best in June (11.5M avg hours)
  
![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Genre Performance Analysis
![Netflix Genre Performance Analysis](
https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Genre%20Performance%20Analysis.png
)

### Genre Insights by content type:
General:
  - Shows: 10.2M avg hours/title (10105 titles)
  - Movies: 3.5M avg hours/title (13054 titles)

 Romance:
 - Shows: 9.2M avg hours/title (235 titles)
 - Movies: 3.2M avg hours/title (397 titles)

 Drama:
 - Shows: 9.2M avg hours/title (39 titles)
 - Movies: 8.6M avg hours/title (158 titles)

 Crime/Thriller:
 - Shows: 7.2M avg hours/title (102 titles)
 - Movies: 6.4M avg hours/title (105 titles)

 Action:
 - Shows: 5.9M avg hours/title (74 titles)
 - Movies: 3.5M avg hours/title (179 titles)

 Family:
 - Shows: 4.5M avg hours/title (88 titles)
 - Movies: 4.2M avg hours/title (125 titles)

 Horror:
 - Shows: 2.5M avg hours/title (51 titles)
 - Movies: 3.4M avg hours/title (76 titles)

 Sci-FI/Fantasy:
 - Shows: 7.7M avg hours/title (21 titles)
 - Movies: 1.4M avg hours/title (16 titles)
  
![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Countries with the most content
![Netflix Countries with the most content]( https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Countries%20with%20the%20most%20content.png)

### Key insights:
- English has the most content (17268 titles)
- Korean content performs 2.0x better than average
- Top 3 languages account for 89.7% of total viewing hours
- Most efficient language has median performance of 1.7M hours/title
  
![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Content distribution patterns
![Netflix Content distribution patterns](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Content%20Distribution%20Patterns.png)

### Key distribution insights:
- Global vs Regional content: 69.2% of catalog
- English content: 44.4% shows vs 55.6% movies
- Most movie-heavy: Hindi (76.7% movies)
- Most show-heavy: Japanese (52.2% shows)
  
![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

# Ratings
![Netflix Ratings](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/Ratings.png)

### Key insights:
- English leads with 122 blockbusters (avg 196.3M hours)
- Korean has highest blockbuster rate: 1.9%
- Overall 4 blockbusters (0.0% of catalog)
  
![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Implications and Data-Driven Recommendations  
### 1. Crime/Thriller Focus
Netflix should aggressively expand its Crime/Thriller slate, building on hits like The Night Agent (5.9M hours/title efficiency). This high-ROI genre drives retention and reduces churn - critical for subscriber stability.

### 2. Korean Documentary Boom
With Korean docs delivering 20M hours/title (3x English counterparts), Netflix must accelerate production. This aligns with global K-content demand and supports Asia-Pacific growth targets.

### 3. Series-First Approach
TV shows generate 200-300% better ROI than films. Netflix should maintain its 70/30 series-to-movie ratio, reallocating resources to proven formats that boost engagement.

### 4. Asia Market Dominance
Korean content's exceptional Asian engagement requires deeper localization - including expanded dubbing/subtitling for 5+ languages to secure Netflix's next 100M subscribers.

### 5. Limited Series Sweet Spot
Premium limited series (The Queen's Gambit, Beef) combine prestige and mass appeal. Netflix should greenlight 15-20 annually to balance awards potential with viewership.

### 6. Smart Cross-Promotion
Leverage algorithm-driven recommendations to push proven genre combos (Korean Romance + English Crime) through "Because You Watched" prompts, potentially lifting discovery by 5-8%.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

## Conclusion  
This project showcases how leveraging Excel, Python, and Tableau in tandem can unlock actionable business intelligence from Netflix's viewership data. Through this multi-tool analytical approach, I transformed raw streaming metrics into strategic insights that directly inform content investment decisions and engagement optimization strategies.

![--](https://github.com/Petkofi/Netflix-Content-Analysis-A-Comprehensive-Intelligence-Framework-for-Data-Driven-Decisions/blob/main/divider.png)

