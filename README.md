# Explored-Netflix-s-movie-and-TV-show-catalog
- Source Used: You downloaded a dataset containing over 5,000 entries, each representing a movie or TV show available on Netflix. The dataset included attributes like title, type, genre, country, rating, date added, release year, and description.
Worksheet 1: Top Ratings Distribution
- Visualization Type: Bar chart or tree map showing frequency of content ratings (e.g., TV-MA, PG-13, R).
- Purpose: To understand audience targeting trends.
- Filters Added: Type (Movie/TV Show), Genre, Country.
🎭 Worksheet 2: Genre Analysis
- Visualization Type: Word cloud or stacked bar chart.
- Purpose: To highlight the most represented genres on Netflix globally.
- Insights: Found dominance of genres like Drama, Comedy, Action across different countries.
📅 Worksheet 3: Year of Release
- Visualization Type: Line chart showing content releases over the last 15 years.
- Purpose: To detect if Netflix releases peaked in certain years or genres evolved over time.
- Calculated Field Used: DATEDIFF(Year, [Release Year], NOW) to explore trend aging.
📥 Worksheet 4: Year Added to Netflix
- Visualization Type: Heatmap or histogram by year added.
- Purpose: To analyze Netflix's content acquisition strategy—when most content was added.
- Interactivity: Filter by content type and genre.
🌍 Worksheet 5: Geographic Content Distribution
- Visualization Type: Filled map of the world with bubble or density overlay.
- Purpose: To visualize country-specific content volumes.
- Data Formatting: Standardized country names enabled seamless integration with Tableau’s geospatial layer.
📌 Worksheet 6: Viewer Ratings Trends 
- Visualization Type: Scatter plot by genre and rating.
- Purpose: To explore if highly-rated content clustered around specific themes or countries.

🔄 3. Dashboard Integration & Interactivity
- All worksheets were consolidated into a single interactive dashboard, allowing dynamic exploration via drop-down filters and hover tooltips.
- Filters Enabled: Type, Country, Genre, Year.
- Actions Added:
- Clickable map to drill into country-specific stats.
- Tooltip with title, release year, rating, and genre.
- Highlight actions to cross-filter across sheets (e.g., clicking a genre filters release trends).

🎨 4. Storytelling & Performance Optimization
- You crafted a story flow across the dashboard, starting from high-level metrics (ratings/genres) to temporal trends (release/year added) to geographic distribution.
- Tableau Tip Used: Optimized load speed by limiting the number of marks displayed and using context filters.
- Outcome: Increased dashboard delivery speed by ~50% during peer reviews and boosted clarity of insights during presentations.

📌 Outcome & Value
- You translated raw data into a compelling visual narrative about Netflix’s global content strategy.
- Your dashboard not only revealed trends but empowered stakeholders to make data-driven decisions regarding regional preferences and historical release timelines.
- The blend of visual design, interactivity, and analytical depth positioned you as a budding data storyteller.


