# Powerlifting Competition Results Dashboard

## Description

This repository contains a single-file HTML dashboard designed to visualize and summarize powerlifting results from various Philippine competitions. It consolidates data from multiple events, providing insights into top performers, team strengths, category highlights, and quantitative analysis using interactive charts and tables.

The dashboard includes data from the following events/files:

*   Dewfoam Visayas Results
*   SBD PH Nationals 2025 (Raw)
*   2025 Luzon Equipped Powerlifting Championships
*   IMPACT 2.0: 2024 National Classic Bench Press Championships (Raw)
*   2024 Luzon Classic Powerlifting Championships (Raw)
*   2024 National Equipped Bench Press Championships
*   2025 National Interschool & Novice Powerlifting Cup
*   2024 Dewfoam Mindanao Results

## Features

*   **Overall Top Performers:** Highlights athletes with the highest IPF Points and Totals for both Raw and Equipped lifting across the aggregated data.
*   **Team Performance:** Identifies consistently strong teams based on placements and includes specific results like the SBD PH Nationals 2025 Best Overall Team ranking.
*   **Category Highlights:** Presents the Best Lifters for key categories (Open, Junior, Sub-Junior) from selected major events (SBD Nationals, Luzon Equipped, Dewfoam Visayas/Mindanao).
*   **Bench Press Insights:** Summarizes top performers from the dedicated National Classic (Raw) and Equipped Bench Press Championships.
*   **Quantitative Analysis:**
    *   Displays average IPF Points and Totals for Raw vs. Equipped lifting.
    *   Visualizes the distribution of IPF points using doughnut charts.
    *   Shows the average contribution of Squat, Bench Press, and Deadlift to the total (Raw) using bar charts.
    *   Compares average Open Raw IPF points across different events.
    *   Compares Junior vs. Open performance using SBD Nationals data.
*   **Interactive Charts:** Utilizes Chart.js to render visualizations for better data exploration.
*   **Responsive Design:** Basic layout adjustments for viewing on different screen sizes.
*   **Single File Deployment:** The entire dashboard is self-contained in one HTML file for easy use.

## Technology Used

*   HTML5
*   CSS3 (including Flexbox and Grid for layout)
*   JavaScript (ES6)
*   Chart.js (v4.x - loaded via CDN)

## How to Use

1.  Download the `powerlifting_dashboard.html` file (or the final filename you saved it as).
2.  Open the `.html` file directly in a modern web browser (e.g., Chrome, Firefox, Edge, Safari).
3.  No local server or special setup is required. *Note: An internet connection might be needed the first time you open it to load the Chart.js library from the CDN, but it should be cached by your browser afterward.*

## Dashboard Structure

The dashboard is organized into the following main sections:

*   **I. Overall Top Performers:** Key record holders and highest scores.
*   **II. Team Performance Highlights:** Team rankings and consistent performers.
*   **III. Key Category Best Lifters:** Winners from specific major events.
*   **IV. Bench Press Championship Highlights:** Results from bench-only events.
*   **V. Quantitative Analysis:** Charts and statistics on averages, distributions, and comparisons.

## Limitations & Disclaimer

*   **Data Scope:** This dashboard is based *solely* on the CSV data provided. It may not represent all powerlifting results in the Philippines during these periods.
*   **Data Accuracy:** The analysis relies on the accuracy and consistency of the source CSV files. Potential discrepancies in names, bodyweights, or results between files might exist.
*   **Averages:** Calculated averages (IPF, Totals) are estimates based on the available lifters with valid totals within the provided datasets and may be skewed by sample size or specific event participation.
*   **Record Claims:** Any mention of records is based on notes present within the source data files and requires official verification.
*   **Hardcoded Data:** All numerical data for charts and analysis is currently hardcoded into the HTML/JavaScript for simplicity. The dashboard does not dynamically load or process external CSV files.
