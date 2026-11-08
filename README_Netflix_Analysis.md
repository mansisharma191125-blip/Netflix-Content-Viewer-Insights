# 🎬 Netflix Content & Viewer Insights \| Power BI Dashboard

An interactive **Power BI dashboard** designed to explore Netflix
content, popularity, audience engagement indicators, ratings, runtime
patterns, and age-certification insights.

The report is organized into five pages, moving from a visual landing
page to focused analysis of content popularity, ratings, runtime,
certifications, and a global Top 10 view.

> **Important:** The dashboard analyzes the data loaded into the PBIX
> file. It should not be described as a live Netflix data feed unless
> the underlying source is connected to a verified live source and
> refreshed accordingly.

------------------------------------------------------------------------

## 📌 Project Objective

The objective of this project is to explore Netflix movie and TV show
data and make content-related patterns easier to understand through
interactive visualizations.

The dashboard helps explore questions such as:

-   Which movies or TV shows rank highest by popularity in the available
    dataset?
-   How do vote counts vary over time?
-   How has the number of movies launched changed over time?
-   How do IMDb ratings relate to vote counts?
-   How has movie and TV show duration changed over time?
-   How do age certifications compare with average IMDb ratings?
-   Which titles appear in the Top 10 view, and how are weekly views
    distributed by category in the loaded data?
    
------------------------------------------------------------------------

## 📂 Data Sources

This dashboard combines two data sources to provide a broader view of Netflix content and weekly global rankings.

### 1. Netflix Content Dataset
Used for content-level analysis, including:
- Movie and TV show popularity
- IMDb ratings and vote counts
- Runtime and duration trends
- Release year
- Age certifications

### 2. Netflix Global Top 10 – Weekly Data (https://www.netflix.com/tudum/top10)
An additional web-connected data source used to bring weekly Global Top 10 information into the dashboard.

Used for:
- Weekly global views
- Content category comparisons
- Top 10 title analysis
- Runtime versus weekly views
<img width="1892" height="971" alt="image" src="https://github.com/user-attachments/assets/d7cd0540-8d0a-4dec-bac8-3fafd3028070" />


### Data Preparation
- Connected and imported source data using Power Query.
- Prepared the content dataset for analysis.
- Connected the weekly Global Top 10 data through the web source.
- Used the resulting data in the dashboard's Global Top 10 page.

**Note:** Weekly data reflects the latest successful refresh of the web connection. It is not necessarily a real-time feed.

------------------------------------------------------------------------

## 🧭 Dashboard Pages

### 1. Home

A visual landing page that provides navigation to the report's analysis
sections.
<img width="1160" height="647" alt="image" src="https://github.com/user-attachments/assets/91cbbdff-1974-49f6-99e3-6f24d9412d0e" />


### 2. Content & Popularity

Explores: - Top 5 movies and TV shows based on popularity - Vote-count
insights over time - Movies launched over time - Interactive slicers for
filtering the analysis
<img width="1135" height="642" alt="image" src="https://github.com/user-attachments/assets/32c6081d-678d-4b1e-8711-33121075e592" />

### 3. Ratings & Runtime

Explores: - IMDb rating trends in relation to votes - Movie and TV show
duration over time - Interactive filtering to investigate rating and
runtime patterns
<img width="1138" height="637" alt="image" src="https://github.com/user-attachments/assets/199df82d-2c89-40f6-b657-280b1b669cac" />


### 4. Age Certifications & Rating Insights

Explores: - The relationship between age certification and average IMDb
ratings - A viewer-choice leaderboard presented through a scrolling-text
visual - Interactive slicers for focused analysis
<img width="1132" height="645" alt="image" src="https://github.com/user-attachments/assets/31fa7e73-3358-45ae-8908-0a88842d0575" />


### 5. Global Top 10

Includes: - A KPI ticker titled **"Now Trending \| Netflix
Worldwide"** - Weekly views by category - Runtime versus views
analysis - A treemap of the Top 10 viewed Netflix shows

The labels and measures in this page reflect the fields and data
available in the report; they do not independently verify real-time
worldwide Netflix rankings.
<img width="1133" height="628" alt="image" src="https://github.com/user-attachments/assets/a2668129-03ac-4cce-8c6a-c3ce097d61df" />

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

-   **Microsoft Power BI Desktop** -- Report development and interactive
    visualizations
-   **Power Query** -- Data preparation and transformation
-   **DAX** -- Measures and analytical calculations
-   **Power BI Custom Visuals** -- KPI ticker and scrolling-text visual
    elements

## ⚙️ Development Approach

The report was developed around a multi-page analytical structure:

1.  Organize the report into clear analysis sections.
2.  Prepare the available content data for reporting.
3.  Use charts suited to rankings, trends, comparisons, and category
    breakdowns.
4.  Add slicers and page navigation to support exploration.
5.  Use custom visuals for the scrolling leaderboard and KPI ticker.
6.  Apply a consistent Netflix-inspired visual theme across the report.

## 🚀 How to Run the Project

1.  Download or clone this repository.
2.  Open the `.pbix` file in [Microsoft Power BI
    Desktop](https://powerbi.microsoft.com/desktop/).
3.  If Power BI prompts for a data-source location, update it to the
    location of your dataset.
4.  Refresh the data if the source is available and you want to update
    the report.
5.  Navigate through the five report pages and use the slicers to
    explore the visuals.

## 💡 Skills Demonstrated

-   Multi-page dashboard design
-   Data preparation and transformation
-   Data visualization and analytical storytelling
-   Trend and comparative analysis
-   Interactive report navigation and filtering
-   Use of Power BI custom visuals

## 📝 Notes & Limitations

-   Findings depend on the dataset and refresh state used in the PBIX
    file.
-   A ticker or page titled "Now Trending" does not by itself mean the
    dashboard is connected to Netflix's live ranking service.
-   IMDb ratings, votes, popularity, and view-related metrics should be
    interpreted according to the definitions and coverage of the
    underlying dataset.
-   The dashboard is an independent analytical project and is not
    affiliated with or endorsed by Netflix.

## 👩‍💻 Author

**Mansi Sharma**

-   GitHub:
    [mansisharma191125-blip](https://github.com/mansisharma191125-blip)

------------------------------------------------------------------------

If you find this project useful, feel free to ⭐ the repository.
Feedback and suggestions are welcome!
