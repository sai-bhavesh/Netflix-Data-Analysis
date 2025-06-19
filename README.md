# Netflix-Data-Analysis


📊 Netflix Dataset Analysis – Summary
✅ Dataset Info
Dataset: Netflix Titles (nt)
Key columns: title, type, country, release_year, duration, listed_in, date_added
📌 Key Analyses Performed
1. Content Types
Counted Movie vs TV Show
Bar plot showing their distribution
2. Top Countries
Grouped content by country and type
Identified top 10 content-producing countries
Visualized as stacked bar charts
3. Genre Analysis
listed_in column exploded and cleaned
Top 10 genres for movies and shows
Separate bar plots for each type
4. Yearly Trend
Number of titles added each release_year
Line chart shows growth trend of content over time
5. Monthly Trend
Extracted month_name from date_added
Grouped by year_added and month_added
Heatmap or bar charts showing content addition seasonality
6. Duration Analysis
Filtered for Movie type
Extracted numeric duration from duration
Averaged per country and plotted
7. Popular Words in Titles
Converted title to lowercase, split into words
Removed punctuation, numbers, and stopwords
Bar chart of most frequent words in titles
8. Keyword Trend
Filtered titles with words like 'love'
Grouped by release_year
Line chart showing title keyword popularity over time
🧼 Data Cleaning
Dropped nulls in critical columns
Converted date_added to datetime
Used .explode() on multi-label fields (listed_in)
Extracted year/month from date fields
Cleaned strings and filtered stopwords for text analysis
📈 Visualizations Used
Bar charts (horizontal/vertical)
Line plots (trends)
Grouped and stacked plots
Word frequency bar charts
✅ Final Outcome
You have:

Performed a full exploratory data analysis (EDA)
Cleaned and transformed real-world data
Extracted valuable insights
Built solid visual storytelling with matplotlib
Great work completing this project! 🔥
