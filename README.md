Project : Netflix Data Visualization

This project focuses on cleaning and visualizing the Netflix dataset using Python, Pandas,
 Matplotlib, and Seaborn. The goal is to understand patterns in Netflix content by exploring ratings,
 duration, release years, and country-wise contributions.
 Dataset- Source: Netflix Titles Dataset- File Used: netflix_titles.csv- Contains details of Movies & TV Shows such as:
 • Title, Director, Cast
 • Country
 • Release Year
 • Content Rating
 • Duration
 
 Data Cleaning- Removed missing values (e.g., country, director where possible)- Standardized content ratings- Converted duration into numeric values for analysis- Extracted year information from date fields
 Visualizations
 1. Percentage of Content Rating - ContenT_rating.png
 2. Distribution of Movie Duration - Movies_duration_histogram.png
 3. Comparison of Movies vs TV Shows released over years - Movies_tv_shows_comparison.png
 4. Number of Movies vs TV Shows - movies_vs_tvshows.png
 5. Release Year vs Number of Shows - Release_scatter.png
 6. Top 10 Contributing Countries - Top_10_countries.png
 7. 
 How to Run
 1. Clone this repository:
 git clone https://github.com/nikhil9370/Netflix-Data-Visualization.git
 2. Install required libraries:
 pip install pandas matplotlib seaborn jupyter
 3. Open the notebook:
 jupyter notebook Netflix_data_visulazation.ipynb
 4. Run all cells to reproduce the analysis.
 Insights- Netflix mostly contains TV-MA and TV-14 content- Most movies are between 90–120 minutes long- Content production on Netflix rapidly increased after 2010- United States leads in content, followed by India- TV Shows have been rising faster than Movies in recent year
