# Netflix Dataset Analysis Project

## Project Overview
This project aims to analyze a Netflix dataset to uncover trends, patterns, and insights related to content types, genres, countries, ratings, and more. Using tools like Power BI and advanced data cleaning techniques, the analysis explores the evolution of Netflix's content library and provides valuable visualizations to understand its dynamics better.

## Dataset Details

### Source
- The dataset contains information about Netflix Movies and TV Shows, including attributes like title, director, cast, genres, release year, and more.

### Tables
1. **Netflix Titles**
   - Includes detailed attributes of Netflix content such as show ID, type (Movie/TV Show), title, director, cast, date added, release year, rating, duration, and calculated fields.

2. **Country**
   - Contains information on countries producing Netflix content along with associated ratings.

3. **Genre**
   - Includes genre details for each title along with release year and a unique genre ID.

## Data Cleaning Steps

### General Steps
- Divided the dataset into three separate tables: Netflix Titles, Country, and Genre.
- Removed unnecessary columns like `description`.
- Split multi-valued fields (e.g., genres) into separate rows.

### Netflix Titles
- Added calculated columns:
  - **Actor Count:** Number of actors in the cast.
  - **Added Year:** Extracted year from the `date_added` field.
  - **Content Age:** Calculated age of the content.
  - **Count of Genre:** Number of genres associated with each title.
  - **Number of Seasons:** Extracted from the `duration` field.
  - **Minutes:** Calculated total minutes for movies and TV shows.
  - **Duration Category:** Categorized duration into short, medium, and long.
  - **Actor Count Range:** Grouped actor counts into ranges.

### Country
- Extracted unique countries associated with each show ID.
- Assigned a unique `country_id` to each country.

### Genre
- Extracted genres listed for each title.
- Assigned unique `genre_id` for each genre.
- Established relationships with the Netflix Titles table.

## Problem Statements

### Key Questions
1. **Early Trend for Content Addition:** What are the earliest trends in content additions?
2. **Movies vs TV Shows Added Each Year:** Compare the addition trends.
3. **Top 10 Most Popular Genres Over Time:** Identify the most frequently added genres.
4. **Distribution of Titles Across Countries:** Understand content spread globally.
5. **Trends in Titles Released Per Year:** Analyze yearly additions.
6. **Movie Duration Distribution Across Age Ratings:** Group durations by age ratings.
7. **Ratings Distribution Across Genres and Top 10 Countries:** Compare ratings.
8. **Top Country Producing Documentaries:** Find the leader in the documentaries genre.
9. **Count of TV Shows and Movies:** Total availability of each type.
10. **Top Directors by Number of Titles:** Recognize the most prolific directors.
11. **Content Age Categories:** Categorize titles based on content age.
12. **Average Duration of Movies and TV Shows:** Calculate and compare averages.
13. **Popular Genres in Different Countries:** Regional genre preferences.
14. **Distribution by Actor Count:** Analyze actor count variations.
15. **Monthly Content Additions:** Understand trends by month.

## Tools and Technologies Used
- **Power BI:** Data analysis and visualization.
- **Excel:** Initial cleaning and exploration.
- **DAX:** For creating calculated fields and advanced analysis.
- **GitHub:** Version control and project hosting.

## Setup Instructions

### Prerequisites
- Power BI Desktop (latest version)
- Basic knowledge of data analysis and visualization

### Steps to Set Up
1. Clone the repository:
   ```bash
   git clone https://github.com/Swarakaranjawane/Netflix-Dataset-Analysis.git 
   ```
2. Open the Power BI file (`Netflix_Dataset.pbix`) for interactive visualizations.
3. Review the cleaned dataset files and documentation.

## Visualizations

### Types of Visualizations
- Line charts for trends over time.
- Pie and bar charts for distributions.
- Heatmaps and treemaps for content popularity.
- Slicers for interactive filtering.

## Screenshots/Demo Links
- **Demo Link:**
  [https://drive.google.com/drive/u/0/folders/10l7e7sj44XzkHaYRE4KqBb9r1JedfPHy]

## Conclusions
The analysis provides insights into:
- Trends in content addition over time.
- Genre and rating distributions.
- Regional content production patterns.
- Differences in movie and TV show characteristics.

## Future Work
- Expand analysis to include predictive modeling for ratings and popularity.
- Integrate new datasets for comparison with other streaming platforms.


## Acknowledgments
- Dataset inspiration from Kaggle.
- Support from peers and mentors in data science.

**For questions or contributions, feel free to contact me at [swarakaranjawane@gmail.com].**

