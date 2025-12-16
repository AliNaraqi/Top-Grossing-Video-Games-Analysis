Top Grossing Video Games Analysis

Project Overview

This project provides a comprehensive analysis of the most popular video games in history based on units sold worldwide. The dataset includes over 50 video games that have each sold millions of copies, representing a wide range of platforms including PlayStation, Nintendo, Xbox, and PC.

Dataset Description

The dataset contains information about top-selling video games with the following features:

- Game Title: Name of the video game
- Units Sold (millions): Total number of units sold worldwide
- Series: The game series or franchise the game belongs to
- Platform(s): Gaming platform(s) where the game is available
- Initial release date: When the game was first released
- Developer(s): Company or team that developed the game
- Publisher(s): Company that published and distributed the game

Some of the most iconic franchises featured include Mario, Call of Duty, Grand Theft Auto, Pokémon, The Legend of Zelda, and Minecraft. The analysis shows how certain games and series have maintained popularity over the years and how different platforms have contributed to global game sales.



The notebook includes step-by-step analysis covering:

1. Data Loading and Exploration
   - Import necessary libraries (pandas, numpy, matplotlib, seaborn)
   - Load and examine the dataset structure
   - Check for missing values and data quality

2. Basic Statistics
   - Summary statistics for units sold
   - Total, average, median, maximum, and minimum sales figures

3. Top Games Analysis
   - Top 10 best-selling games
   - Visualizations with horizontal bar charts

4. Series Analysis
   - Total sales by game series
   - Top performing franchises
   - Series comparison visualizations

5. Platform Analysis
   - Games distribution across platforms
   - Total sales by platform
   - Platform performance comparison

6. Publisher Analysis
   - Top publishers by total sales
   - Publisher performance metrics

7. Time-Based Analysis
   - Release year trends
   - Sales patterns over time
   - Decade comparisons

8. Advanced Enhancements
   - Average sales per year calculations
   - Market share analysis
   - Distribution and correlation analysis

File Structure

Top Grossing Video Games/
├── Top.ipynb                    
├── Top_Selling_Games.csv        
└── README.md                    

Key Insights

The analysis reveals several interesting patterns:

- Minecraft leads with 350 million units sold, making it the best-selling game of all time
- Multi-platform games dominate the top sellers, showing the importance of broad platform availability
- Nintendo franchises like Mario, Pokémon, and Zelda show strong performance across multiple entries
- Call of Duty series demonstrates consistent success with multiple titles in the top 50
- The gaming industry has seen significant growth, with many top sellers released in the 2010s and 2020s

Analysis Sections

Step 1: Import Libraries
Sets up the environment with necessary data science libraries and visualization settings.

Step 2: Load Dataset
Loads the CSV file and displays basic information about the dataset structure.

Step 3: Data Exploration
Provides an initial look at the data with head() function to see the first few rows.

Step 4: Dataset Information
Shows detailed information about columns, data types, and dataset structure.

Step 5: Missing Values Check
Verifies data quality by checking for any missing or null values.

Step 6: Basic Statistics
Calculates and displays summary statistics including mean, median, min, max, and quartiles.

Step 7: Top 10 Games
Identifies and displays the top 10 best-selling games with their sales figures.

Step 8: Top Games Visualization
Creates a horizontal bar chart visualizing the top 10 games.

Step 9: Series Analysis
Groups games by series and calculates total sales per franchise.

Step 10: Platform Analysis
Analyzes game distribution and sales across different gaming platforms.

Step 11: Platform Visualizations
Creates side-by-side charts showing game count and sales by platform.

Step 12: Publisher Analysis
Examines publisher performance and identifies top publishers by total sales.

Step 13: Release Year Analysis
Extracts release years from dates and analyzes trends over time.

Step 14: Time Trends Visualization
Creates line and bar charts showing sales trends by release year.

Step 15: Summary Statistics
Generates a comprehensive summary with key metrics and top performers.

Enhancement 1: Annual Sales Rate
Calculates average sales per year for each game, accounting for how long each game has been on the market.

Enhancement 2: Market Share
Calculates market share percentages for series and platforms, with pie chart visualizations.
