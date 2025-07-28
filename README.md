# Temporal Genre Popularity Trends Dashboard

## Project Overview

This project is a single-page web application developed to provide a clear and interactive dashboard for analyzing music genre trends. The main goal is to help users visualize the rise and fall of music genres over decades and compare these historical patterns with real-time data on what's currently popular.

By combining a rich historical dataset with live data from the Spotify API, this dashboard empowers users to explore the evolution of music, discover new tracks, and gain insights into the cultural shifts reflected in genre popularity.

## Data Source & Preparation

The analysis is based on two primary data sources:

1.  **Live Data (Spotify Web API):** The "Current Trends" and "New Releases" sections are powered by real-time data fetched directly from the Spotify API. All API calls and data transformation are handled in the browser using JavaScript.
2.  **Historical Data (Simulated Kaggle Dataset):** The "Historical Perspective" chart is populated by a large, detailed JavaScript object that simulates the structure of a typical `.csv` dataset found on platforms like Kaggle. This data was curated to represent genre popularity from 1960 to 2025.

## Key Analysis & Views

The dashboard provides a quick overview of essential music trends, broken down across three main views accessible via the sidebar navigation:

### 1. Historical Perspective

This view focuses on long-term trends, allowing users to:
* Visualize the rise and fall of numerous genres from 1960 to 2025.
* Filter the genres displayed on the chart to simplify the view and compare specific trends.
* Drill down into any year on the chart to see a simulated month-by-month breakdown of genre popularity.

### 2. Current Trends

This page provides a snapshot of what's popular right now, featuring:
* A list of the top tracks from a popular Spotify playlist (e.g., "Top 50 - India").
* A dynamic bar chart showing the distribution of genres within those top tracks.
* Clickable links for each song to listen directly on Spotify.

### 3. New Releases

This view helps with music discovery by displaying:
* A grid of the latest album and single releases for a specific region, fetched from Spotify.

## Dashboard Snapshots

**View 1 - Historical Perspective:**
<img width="1883" height="919" alt="Image" src="https://github.com/user-attachments/assets/8264b360-78e3-446f-96e7-86fe5abd5a28" />

**View 2 - Current Trends:**
<img width="1874" height="909" alt="Image" src="https://github.com/user-attachments/assets/7b7e6aa9-76cb-4dc1-9a6a-4431e1c47eb8" />

**View 3 - New Releases:**
<img width="1877" height="916" alt="Image" src="https://github.com/user-attachments/assets/2c3bbf4a-bf56-414c-a219-4c97dba4f6b6" />

## Value & Insights

This dashboard enables critical exploration of music data by:
* Providing immediate visibility into today's most popular genres and tracks.
* Allowing for direct comparison between modern music trends and historical patterns.
* Helping users understand the lifecycle and evolution of different music genres over 60+ years.
* Supporting music discovery through the "New Releases" feature.

## Technologies Used

* **Frontend:** HTML, CSS, Vanilla JavaScript
* **Styling:** Tailwind CSS
* **Data Visualization:** Chart.js
* **Icons:** Lucide Icons
* **Data Source:** Spotify Web API

---

**Final Checklist for You Before Uploading to GitHub:**

1.  **Add Your Spotify API Keys:** Open the `index.html` file and replace the placeholder `YOUR_CLIENT_ID_HERE` and `YOUR_CLIENT_SECRET_HERE` variables with your actual credentials from the Spotify Developer Dashboard.
2.  **Capture and Replace Image Placeholders:** Add your actual dashboard screenshots to an `images` folder and update the paths in this `README.md` file.
3.  **Upload Project Files:**
    * Upload your `index.html` file to the root of your repository.
    * Upload the `images/` folder containing your screenshots.
