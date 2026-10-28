# Netflix Content Analysis | Excel & Power BI

## Project Overview

This project explores Netflix's content library using Excel and Power BI. The aim was to clean the dataset, understand the distribution of Movies and TV Shows, identify patterns in content ratings and release years, examine country representation, and present the findings through interactive dashboards.

I completed the initial data cleaning and analysis in Excel, then used Power BI to create visual reports and an executive overview.

## Tools Used

- **Microsoft Excel:** Data cleaning, standardisation, PivotTables and exploratory analysis.
- **Microsoft Power BI:** Data visualisation, interactive reports, summary cards and dashboard design.

## Dataset

The project uses a Netflix titles dataset containing information about Movies and TV Shows, including:

- Show ID and title
- Content type
- Director and country
- Date added to Netflix
- Release year
- Content rating
- Duration
- Listed categories

The dataset was reviewed and cleaned before analysis. One duplicate record and one broken, incomplete record were removed, leaving **8,786 titles** for analysis.

## Project Tasks

### Task 1: Content Mix Analysis

I examined the distribution of Movies and TV Shows to understand the composition of the Netflix library. I also reviewed the release years and the most common content ratings.

**Key findings:**
- Total titles analysed: 8,786
- Movies: 6,123, approximately 70%
- TV Shows: 2,663, approximately 30%
- 2018 was the most common release year, with 1,144 titles.
- TV-MA was the most common content rating, followed by TV-14.

### Task 2: Country Analysis

I explored the distribution of titles across countries to identify which countries had the highest representation in the dataset.

**Key findings:**
- The United States had the highest number of titles, with 3,239.
- India followed with 1,056 titles.
- The United Kingdom ranked third, with 638 titles.
- Country counts represent the number of titles associated with each country, not revenue, market share or audience size.

### Task 3: Content Rating Analysis

I examined content ratings and compared their distribution across Movies and TV Shows using Excel.

**Key findings:**
- TV-MA was the most common rating, with 3,205 titles.
- TV-14 followed with 2,155 titles.
- Together, TV-MA and TV-14 accounted for 5,360 titles.
- The distribution of ratings differed between Movies and TV Shows.

This analysis helped show how content ratings were represented across the two content types.

### Task 4: Netflix Content Release Trends

I moved to Power BI to explore how titles were distributed across release years.

The report includes:
- Summary cards for total titles, Movies and TV Shows.
- A chart showing the leading release years.
- A line chart comparing Movies and TV Shows by release year.
- A release-year distribution chart.
- A release-year slicer for filtering the report.
- A Key Insights section summarising the main findings.

**Key finding:** 2018 had the highest number of titles by release year in the cleaned dataset, with 1,144 titles.

The analysis focuses on original release years rather than the dates titles were added to Netflix.

### Task 5: Netflix Content Category Analysis

I created a Power BI report to examine listed categories, content types and ratings.

The report includes:
- A Top 10 listed-category chart.
- A content mix donut chart.
- Content rating charts.
- A content-type slicer.
- Summary cards and a Key Insights section.

**Key findings:**
- Movies represented approximately 70% of the titles, while TV Shows accounted for approximately 30%.
- TV-MA was the most common content rating, followed by TV-14.
- Rating distributions varied between Movies and TV Shows.

The `listed_in` field contains category combinations. Therefore, the category chart represents the listed combinations in the dataset rather than a separate count of every individual genre.

### Task 6: Executive Overview

I created an executive-level Power BI dashboard to bring the main findings together on one page.

The dashboard includes:
- Total title, Movie and TV Show summary cards.
- A donut chart showing the content mix.
- A Top 10 countries chart.
- A release-year trend chart.
- A Top 5 content ratings chart.
- A Key Insights section.

The country chart excludes records labelled "Not Given" so that the visual focuses on countries identified in the dataset.

The dashboard uses a consistent visual theme with light lavender backgrounds, white cards, blue and soft-pink accents, and clear chart titles.

## Key Project Findings

1. Movies make up approximately 70% of the Netflix titles analysed.
2. TV Shows account for approximately 30% of the library.
3. The United States has the highest number of titles by country, followed by India and the United Kingdom.
4. 2018 is the most common release year in the dataset.
5. TV-MA and TV-14 are the two most common content ratings.

## Recommendations

Based on the findings, further analysis could explore:

- Comparing content release trends with the dates titles were added to Netflix.
- Examining viewing figures for Movies and TV Shows before drawing conclusions about audience preferences.
- Comparing viewing performance across content ratings.
- Investigating country representation alongside local viewing data to better understand potential content opportunities.

These are areas for further investigation rather than conclusions established by this dataset alone.

## Conclusion

This project gave me practical experience in cleaning data, using Excel for exploratory analysis, and building reports in Power BI. It also helped me practise turning raw data into clear visuals and communicating findings without making assumptions that the data cannot support.

## Skills Demonstrated

- Data cleaning and standardisation
- Excel PivotTables and exploratory analysis
- Content distribution and rating analysis
- Country and release-year analysis
- Power BI dashboard development
- Data visualisation and report formatting
- Communicating findings and identifying areas for further analysis

## Interactive Power BI Dashboard

Explore the completed Netflix Content Analysis dashboard using the link below:

**[View the Netflix Content Analysis Dashboard on Power BI](https://app.powerbi.com/view?r=eyJrIjoiYjk1NDkxZDAtOWUzOS00Mzk2LWIwMzYtYjJiNjUwNjcwYzQwIiwidCI6IjY2ZGMxYzVhLWY4YjMtNGU1ZS1hMmZkLWQ2NThlMGJlZGJmNiJ9&pageName=7213eb957901e34c42d5)**

The dashboard presents insights into Netflix's content mix, country distribution, content ratings, release-year trends, and listed categories.
