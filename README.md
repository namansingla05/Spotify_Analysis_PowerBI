# Spotify Listening Analytics Dashboard

This project showcases an interactive **Spotify Listening Analytics Dashboard** built using **Power BI**, designed to deliver comprehensive insights into a user's music streaming behavior. The dashboard leverages visual storytelling to help users explore their favorite artists, tracks, listening patterns, and preferences.

---

## Project Files

- **PBIX File**: Contains the complete Power BI dashboard with all visualizations.
- **Three Main Dashboard Views**:
  - **Summary Page**
  - **Listening Pattern Page**
  - **Details Page**

---

## Project Overview

The dashboard analyzes personal Spotify listening data collected over a period, revealing trends and patterns based on albums, artists, tracks, listening duration, and more.

### Key KPIs Tracked:
- Number of Albums Played
- Number of Artists Played
- Number of Tracks Played
- Milliseconds Played
- Average Listening Time

It also allows filtering by:
- **Platform** (e.g., Android)
- **Shuffle or Not**
- **Skipped or Not**
- **Year of Listening**

---

## Dashboard Snapshots

### 1. Summary Page

![Summary Dashboard](https://github.com/namansingla05/Spotify_Analysis_PowerBI/blob/main/Summary_DashBoard.png)

- **Visualizes Key Metrics** such as:
  - Total Albums Played
  - Total Artists
  - Total Tracks
  - Total Listening Duration (in milliseconds)
  - Average Listening Time per Track

- **Bar Charts** for:
  - Top Artists by Play Count
  - Top Albums by Play Count
  - Top Tracks by Play Count

- **Line Chart** showing the number of tracks played year-over-year—helpful for tracking changes in music engagement over time.

- Allows filtering by:
  - **Platform**
  - **Shuffle** (Shuffled/Not Shuffled)
  - **Skipped** (Skipped/Not Skipped)

- This summary view is a powerful tool for understanding the big picture of one’s listening habits and top choices over time.

---

### 2. Listening Pattern Page

![Listening Pattern Dashboard](https://github.com/namansingla05/Spotify_Analysis_PowerBI/blob/main/Listening_Pattern_DashBoard.png)

- **Heatmap Visualization**: Displays listening activity by **hour of the day** vs **day of the week**, enabling the identification of peak listening periods and trends.

- **Quadrant Analysis Chart**:
  - A scatter plot with a quadrant layout used to assess songs based on:
    - **X-Axis**: Play Frequency
    - **Y-Axis**: Average Listening Duration
  - Divides tracks into 4 zones:
    - **High Frequency, High Duration** → Fan Favorites
    - **High Frequency, Low Duration** → Often Skipped
    - **Low Frequency, High Duration** → Hidden Gems
    - **Low Frequency, Low Duration** → Least Engaging
  - This helps analyze which songs truly engage vs those played frequently but not enjoyed thoroughly.

- Ideal for identifying:
  - Skipped songs
  - Overrated vs underrated tracks
  - Personal favorite listening zones

- Filterable by:
  - Year
  - Shuffle Mode
  - Skipped or Not Skipped


---

### 3. Details Page

![Details Dashboard](https://github.com/namansingla05/Spotify_Analysis_PowerBI/blob/main/GridView_DashBoard.png)

#### Tabular View with Hierarchical Grouping

- The table is structured in a **hierarchical drill-down format**:
  - **Album Name** ⮕ **Artist Name** ⮕ **Track Name** ⮕ **Platform** ⮕ **Track Played Time**
- This allows users to expand or collapse levels for easy navigation and summarization.
- Other Tabular fields
  - Number of Artists
  - Number of Tracks
  - Total Milliseconds Played
  - Average Listening Time

- **Drillthrough Feature**:
  - Users can **right-click on a track, artist, or album** in summary or overview pages and drill through to this detail page.
  - Enables granular analysis of specific entities without disrupting the main exploration flow.
  - Provides a contextual deep-dive into selected data points.

- Enables:
  - Spot-checking high/low-performing tracks or albums
  - Exploring playback stats for specific artists or playlists

---

## Data Insights

- The user listens the most during evening hours on weekdays.
- The majority of tracks are fully played, indicating strong listening engagement.
- Some top tracks have high frequency but lower average listening time, possibly due to partial plays or skips.
- Certain albums consistently maintain a high average listening time, showing strong track quality.

---

## How to Use

1. Open the `.pbix` file in **Power BI Desktop**.
2. Use filters to customize your view:
   - Platform
   - Shuffle On/Off
   - Skipped/Not Skipped
   - Year of Listening
3. Interact with visuals to explore your listening history and patterns in detail.

---

## Tags

`Spotify` `Dashboard` `Data Visualization` `Power BI` `Music Analytics` `Listening Behavior` `Data Analytics`
