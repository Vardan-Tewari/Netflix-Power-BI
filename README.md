# 📊 Netflix Analysis Dashboard – Power BI

📘 Project Overview

This Power BI dashboard analyzes Netflix’s complete movie and TV show catalog using structured, cleaned, and transformed data.
The goal of the project is to understand content growth, genre evolution, country-level contributions, ratings distribution, and top creators featured on Netflix.

🛠 Tools & Techniques Used
Power BI Desktop
Power Query (Data Cleaning & Transformations)
DAX (Measures & Calculations)
Custom visuals (Map, Donut Chart, Stacked Bar, Line Charts)
Data modeling & relationship building

🧹 Data Preparation & Cleaning
Before visualization, I performed full data cleanup and preparation, including:
Handling missing values in director, cast, country, rating, and duration fields
Splitting multi-valued fields (e.g., country, cast, genres)
Converting duration into numeric values
Standardizing date formats and extracting year released
Ensuring relationship-friendly structured tables for modelling
Removing duplicates and irrelevant blank entries
(All cleaning was done inside Power Query in Power BI.)

📈 Key Metrics Calculated
Total Titles: 2675
Average Duration: 1.76 hours
Minimum Duration: 1 hour
Maximum Duration: 17 hours
Total Directors Identified: 6881 + entries
Content Split: Movies vs TV Shows

📊 Dashboard Features
1. Yearly Content Addition
Line chart showing how Netflix expanded from 2010 to 2020
Significant spikes between 2018–2020
2. Content Type Distribution
Movies vs TV Shows filter
Insight: Netflix has increased focus on TV Shows post-2010
3. Popular Genres
Bar chart ranking top genres
Top categories include:
TV Shows
Classic & Nostalgic
Stand-Up Comedy
TV Thrillers
Spanish-Language TV
4. Country-wise Content Distribution
Interactive world map
US leads with ~1.8K titles
UK, South Korea, Japan, Canada also major contributors
5. Genre Evolution Over Time
Line chart showing genre growth
Anime, Crime, Docuseries and British TV content show notable increase
6. Ratings Breakdown
Donut chart of age ratings
TV-MA dominates followed by TV-14 and TV-PG
7. Top Directors
Ranking of top creators by number of titles
Includes directors like Alastair Fothergill, Justin Webster, etc.

🔍 Key Insights Derived
🇺🇸 United States contributes the largest share of titles, followed by UK & South Korea.
📺 TV Shows dominate the platform, especially after 2010.
🎭 Popular genres include Stand-Up Comedy, Thrillers, Classic & Nostalgic shows, and Anime-type content.
🔞 TV-MA is the most common rating, showing a preference for mature content.
📈 Peak content releases occurred between 2018–2020, driven by global expansion and pandemic media consumption.

💡 Conclusion
This Power BI dashboard provides a comprehensive view of Netflix’s global catalog and content strategy. It highlights the shift towards TV shows, strong adult-audience content, and growing international contributions.

The insights can help stakeholders understand content performance, market expansion, and genre preferences on Netflix over time.
