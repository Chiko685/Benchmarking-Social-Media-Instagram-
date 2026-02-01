# Social Media Performance Analysis: "The Key" Competitor Project

This repository contains a comprehensive data analysis and visualization
of Instagram content performance for **The Key** and its competitors.
The analysis focuses on understanding content distribution, engagement
metrics, and posting patterns to identify best practices in the English
education sector.

## 📊 Overview

The project analyzes media data from several Instagram accounts:

-   **Target Account:** The Key\
-   **Competitors:** British Council, Wall Street English, EF (English
    First), Lister, Titik Nol, and Kampung Inggris LC

## 🛠️ Tech Stack

-   **Source:** Meta Graph API (FB-IG)\
-   **Language:** Python, Power BI\
-   **Data Manipulation:** pandas, numpy, os\
-   **Visualization:** plotly.express, seaborn, matplotlib\
-   **File Format:** JSON and Excel (.xlsx)

## 📈 Key Analysis Features

### 1. Media Product Type Distribution

Compares the usage of **FEED** vs **REELS** across different accounts.\
For instance, *The Key* shows a heavy reliance on **REELS** (48 posts)
compared to **FEED** (2 posts).\
Overall, The Key utilizes REELS most frequently, posting a significantly
higher count than all other accounts in the dataset.

### 2. Top Performing Posts

Identifies the **Top 10 posts** for each account based on **Engagement
Rate (ER %)**.

**Formula:**

    (likes + comments) / impressions * 100

-   If the result is **100%**, it means the post has the highest
    engagement score in the entire dataset.
-   **Goal:** Determine which captions and content styles resonate most
    with the audience.

### 3. Caption Length + Hashtag Based on ER

Audiences tend to prefer captions that are informative but not too
long.\
Shorter captions have a higher chance of being fully read, which often
correlates with higher engagement rates.

### 4. Hashtag Distribution per Competitor

Most competitors (EF, WSE, BC) follow best practices by placing hashtags
at the **end of captions** to keep the main text visually clean,
especially for long captions.

-   **Lister** stands out as an outlier with a different strategy.
-   **The Key** shows the most varied results, indicating either
    experimentation or a lack of consistency in hashtag placement.

### 5. Time-Based Analysis

-   **Posting Frequency:** Weekly posting patterns analysis (focused on
    **October 2025**).
-   **Best Time to Post:** Correlates posting hours with total likes to
    identify optimal "golden hours" for engagement.

### 6. Dashboard Using Power BI

Key insights from the dashboard: - **Best time to post:** Monday at
**2:00 PM** - **Highest engagement media type:** **Video Reels** -
**Hashtag strategy recommendation:** Use consistent and familiar
hashtags.

Example insight: - Other platforms using **#Scholarship** achieved a
total of **64K likes** - The Key using
**#Scholarshipinterviewenglishclass** achieved only **74 likes**

This highlights the importance of using widely recognized hashtags.

## 📁 Project Structure

    ├── Visualization The Key.ipynb   # Main Jupyter Notebook
    ├── file XLSX/                   # Raw Excel data outputs (external dependency)
    └── README.md

## 🚀 How to Use

1.  Install the required libraries:

``` bash
pip install pandas numpy plotly seaborn matplotlib openpyxl
```

2.  Update the **path variable** in the notebook to point to your local
    directory containing the `.xlsx` files.

3.  Run the notebook cells sequentially to generate interactive charts
    and dataframes.

------------------------------------------------------------------------

✨ This project provides actionable insights into Instagram content
strategies within the English education industry.
