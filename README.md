Task-05: Traffic Accident Data Analysis – US Accident Dataset
This project analyzes U.S. traffic accident data to identify patterns based on road conditions, weather, and time of day. The goal is to uncover contributing factors and visualize accident hotspots for better understanding and decision-making.

📊 Objective
To perform exploratory data analysis on a large traffic accident dataset and create meaningful visualizations that highlight when and where accidents are most likely to occur, and under what conditions.

🔍 Dataset
Source: Kaggle – US Accident EDA

Original Dataset: US Accidents (March 2023)

File: US_Accidents_March23.csv

Size: ~3.5 GB

Records: ~7 million accident reports across the U.S.

Dataset Link: https://www.dropbox.com/scl/fi/ymzos99b2rv9io8aja5w9/US_Accidents_March23.csv?rlkey=g2qtwbxbtfj0m4u23o61heikd&st=kkiaaqd3&dl=0

🛠️ Tools Used
Python

Pandas

Matplotlib / Seaborn

Plotly

Folium (for map visualization)

Jupyter Notebook

📁 Folder Structure

Task-05/
│
├── data/
│   └── US_Accidents_March23.csv       # Original dataset
│
├── us_accidents_analysis.ipynb       # Main Jupyter Notebook
│
├── output/
│   ├── charts/                        # Time-based and condition-based charts
│   └── heatmap.html                   # Interactive accident hotspot map
│
└── README.md                          # This file
🔧 Steps Performed
Data Cleaning:

Removed missing and duplicate values

Filtered relevant columns (Time, Weather, Road Conditions, Location)

Analysis Performed:

Accidents by time of day (hourly trends)

Day-wise and month-wise accident frequency

Effect of weather conditions (rain, fog, visibility)

Road condition impact (lighting, traffic congestion)

Visualizations:

Line plots, bar graphs, and heatmaps

Accident hotspot visualization using Folium (based on latitude & longitude)

Note: Due to large dataset size (~3.5 GB), use filtered data or a machine with enough memory.

✅ Status
Project Completed ✅

🙋‍♂️ Author
  Karthikeyan Anoop

