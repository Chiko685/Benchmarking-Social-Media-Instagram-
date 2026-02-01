Social Media Performance Analysis: "The Key" Competitor Project
This repository contains a comprehensive data analysis and visualization of Instagram content performance for The Key and its competitors. The analysis focuses on understanding content distribution, engagement metrics, and posting patterns to identify best practices in the English education sector.

📊 Overview
The project analyzes media data from several Instagram accounts:

Target Account: The Key

Competitors: British Council, Wall Street English, EF (English First), Lister, Titik Nol, and Kampung Inggris LC.

🛠️ Tech Stack
Language: Python

Data Manipulation: pandas, numpy, os

Visualization: plotly.express, seaborn, matplotlib

File Format: Excel (.xlsx)

📈 Key Analysis Features
1. Media Product Type Distribution
The analysis compares the usage of FEED vs REELS across different accounts. For instance, "The Key" shows a heavy reliance on REELS (48 posts) compared to FEED (2 posts), while others like British Council favor FEED content.

2. Top Performing Posts
Identifies the top 10 posts for each account based on a calculated Engagement Rate (%).

Formula: (likes + comments) / impressions * 100.

Goal: Determine which captions and content styles resonate most with the audience.

3. Time-Based Analysis
Posting Frequency: Analyzes weekly posting patterns (specifically focused on October 2025 data) to see which competitors are most active.

Best Time to Post: Correlates the hour of posting with total like counts to find optimal "golden hours" for engagement.

4. Engagement Rate by Followers (ERF)
A specialized metric for "The Key" to measure engagement relative to a fixed follower count (assumed at 5,000 for this analysis).

📁 Project Structure
Visualization The Key.ipynb: The primary Jupyter Notebook containing data cleaning, processing, and interactive Plotly visualizations.

/file XLSX/: (External dependency) Directory containing the raw Excel data outputs for each analyzed account.

🚀 How to Use
Ensure you have Python installed with the necessary libraries:

Bash
pip install pandas numpy plotly seaborn matplotlib openpyxl
Update the path variable in the notebook to point to your local directory containing the .xlsx files.

Run the cells sequentially to generate the interactive charts and dataframes.
