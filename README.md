Temporal Genre Popularity Trends Dashboard
This project is a single-page web application that provides a comprehensive dashboard for analyzing music genre trends over time. It combines real-time data from the Spotify API with a historical dataset to offer a rich, interactive experience for exploring the evolution of music.

This is an excellent portfolio project for a data analyst, as it demonstrates skills in API integration, data transformation, data visualization, and building interactive dashboards.

Key Features
Sidebar Navigation: A clean, modern interface that allows users to switch between different analysis views.

Current Trends Analysis:

Fetches and displays the top tracks from a default Spotify playlist (e.g., "Top 50 - India").

Generates a dynamic bar chart showing the distribution of genres within the current top tracks.

Each track in the list is a clickable link that opens the song on Spotify.

New Releases:

Displays a grid of the latest album and single releases from Spotify for a selected region.

Historical Perspective:

Visualizes the rise and fall of various music genres from 1960 to 2025 using a large, Kaggle-style dataset.

Features a dynamic line chart with gradient fills.

Interactive Drill-Down: Click on any year in the chart to see a simulated month-by-month breakdown of genre popularity.

Genre Filtering: Use checkboxes to toggle the visibility of different genres, allowing for focused analysis.

Modern, Responsive Design: Built with Tailwind CSS for a sleek, dark-mode aesthetic that works on all devices.

Technologies Used
Frontend: HTML, CSS, Vanilla JavaScript

Styling: Tailwind CSS

Data Visualization: Chart.js

Icons: Lucide Icons

Data Source: Spotify Web API

Setup and Installation
To run this project locally, you only need a modern web browser.

Download the Code: Save the entire code as a single index.html file.

Get Spotify API Credentials:

Go to the Spotify Developer Dashboard.

Log in and create a new application.

Once your app is created, you will see your Client ID and Client Secret.

In your app settings on the dashboard, you must add a "Redirect URI". You can use http://127.0.0.1:8888/callback for local development.

Add Your Credentials:

Open the index.html file in a text editor.

Find the following lines in the <script> section:

const clientId = 'YOUR_CLIENT_ID_HERE'; // <-- Replace with your Client ID
const clientSecret = 'YOUR_CLIENT_SECRET_HERE'; // <-- Replace with your Client Secret

Replace the placeholder text with your actual Client ID and Client Secret from the Spotify dashboard.

Run the Application:

Simply open the index.html file in your web browser. The application will fetch the data and display the dashboard.