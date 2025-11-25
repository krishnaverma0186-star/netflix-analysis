# 🎬 Netflix Content Analysis & Visualization

## 📌 Project Overview
This project performs a detailed Exploratory Data Analysis (EDA) on the Netflix dataset. The goal is to uncover trends and patterns in content production, understanding the distribution between Movies and TV Shows, analyzing ratings, and identifying key contributors (directors, actors, and countries).

## 📊 Key Features & Workflow
1. **Data Cleaning**: 
   - Handling missing values in `director`, `cast`, and `country`.
   - Dropping duplicates and unnecessary columns.
   - Converting date formats for time-series analysis.

2. **Feature Engineering**:
   - Extracting Day, Month, and Year from `date_added`.
   - Categorizing content ratings into broader groups (Kids, Teens, Adults).
   - Exploding nested columns (Director, Cast, Genre) to analyze individual contributors.

3. **Visualizations**:
   - **Content Distribution**: Pie charts comparing the volume of Movies vs. TV Shows.
   - **Geographical Analysis**: Bar charts showing the top content-producing countries.
   - **Temporal Trends**: Analysis of content added over years, months, and specific days of the week.
   - **Duration Analysis**: Histograms showing the spread of movie lengths and TV show seasons.
   - **Rating Insights**: Breakdown of target audiences (Kids vs. Adults).

## 📈 Key Insights
- **Content Split**: Movies significantly outnumber TV Shows on the platform.
- **Top Countries**: The United States and India are the leading producers of content.
- **Release Timing**: There is a noticeable trend in the months and days when Netflix releases new content.
- **Duration**: The majority of movies fall within the 90-100 minute range, while most TV shows consist of 1-2 seasons.

## 🛠️ Libraries Used
- **Pandas**: Data manipulation and cleaning.
- **NumPy**: Numerical operations.
- **Matplotlib & Seaborn**: Static and statistical data visualization.

## 🚀 How to Run
1. Clone this repository.
2. Ensure you have the `netflix.csv` dataset in the root folder.
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
