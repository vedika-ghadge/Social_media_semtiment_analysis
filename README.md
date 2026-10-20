 # Social_media_semtiment_analysis Dashboard 


# 1. Project Overview

This project analyzes social media posts and presents sentiment-related
insights through an interactive Power BI dashboard. The dashboard
compares positive, negative, and neutral posts across platforms and
shows sentiment distribution, engagement comparisons, and trends over
time.

Dataset note: This project uses a sample/synthetic dataset for
learning and demonstration. Results should not be treated as a
representation of all real social media users.

 # 2. Business Problem
   
Businesses receive large amounts of feedback on social media. Reviewing
every post manually can be time-consuming. This project organizes
sentiment data into clear metrics and visualizations so that users can
explore patterns, compare platforms, and identify areas that may need
further investigation.

 # 3. Project Objectives

- Explore social media data using Python.
- Check data quality, including missing values and duplicate records.
- Analyze positive, negative, and neutral sentiment categories.
- Compare post counts and engagement metrics across platforms.
- Visualize sentiment patterns over time.
- Present findings in an interactive Power BI dashboard.

 # 4. Tools and Technologies
    
- Python --- data analysis and preprocessing
- Jupyter Notebook --- running and documenting Python code
- Pandas / NumPy --- data manipulation and numerical analysis,
  where used
- Matplotlib / Seaborn --- Python visualizations, where used
- Microsoft Power BI --- dashboard, charts, KPI cards, and slicers
- CSV --- dataset format

# 5. Dataset
   
The dataset contains social media post records. Depending on the version
of the file, columns may include platform, post date, sentiment, likes,
comments, or other engagement fields.

Before running the project, check the actual CSV column names in the
notebook. The dashboard's results depend on the data loaded and any
filters applied.

# 6. Project Workflow
   
1. Load the CSV dataset into Jupyter Notebook using Pandas.
2. Inspect rows, columns, data types, and summary information.
3. Check missing values and duplicate records.
4. Clean or transform data where appropriate.
5. Perform Exploratory Data Analysis (EDA).
6. Analyze sentiment categories and platform-level metrics.
7. Load the prepared data into Power BI.
8. Create KPI cards, charts, and interactive slicers.
9. Review the dashboard and summarize the key observations.

# 7. Dashboard Features
   
- KPI Cards: Total posts, positive posts, negative posts, and
  neutral posts.
- Overall Sentiment Distribution: Donut chart showing the share of
  each sentiment category.
- Platform Engagement Comparison: Compares engagement metrics
  across platforms.
- Platform vs Likes: Compares likes by sentiment category, as
  configured in the report.
- Posts Trend Over Time: Displays sentiment trends by month.
- Platform-Wise Sentiment: Compares sentiment counts across
  platforms.
- Interactive Slicers: Filters for platform, sentiment, and post
  date.

 # 8. Current Dashboard Snapshot
     
The screenshot shared during development shows the following values: -
Total posts: 968 - Positive posts: 406 - Negative posts:
264 - Neutral posts: 298 - Positive sentiment: 41.94% -
Neutral sentiment: 30.79% - Negative sentiment: 27.27%

<img width="1345" height="772" alt="Screenshot 2026-10-20 110510" src="https://github.com/user-attachments/assets/56e5383f-4218-4e9f-bbe0-878e538c49d4" />

# 9. Business Insights
    
- Positive sentiment represents the largest category in the displayed
  dashboard snapshot.
- Negative posts can be reviewed further to identify recurring
  concerns or complaints.
- Platform comparisons help highlight differences in post volume and
  engagement.
- Monthly trends help identify changes that may deserve further
  analysis.
- Slicers let users explore results for selected platforms, sentiment
  categories, and dates.
The dashboard shows patterns in the available data; it does not, by
itself, prove why a sentiment or engagement pattern occurred.

# 10. Exploratory Data Analysis (EDA)

EDA was performed to understand the dataset, identify data quality issues, and explore sentiment patterns.

1. Dataset Overview
   
<img width="1416" height="577" alt="Screenshot 2026-10-20 115904" src="https://github.com/user-attachments/assets/ad7454dd-6f3a-46fe-ac91-8217f0be2900" />


3. Data Cleaning and Missing Values

<img width="1363" height="757" alt="Screenshot 2026-10-20 120045" src="https://github.com/user-attachments/assets/1dcebe70-4aa0-4b5b-a83f-47b38679393a" />


<img width="1268" height="732" alt="Screenshot 2026-10-20 120100" src="https://github.com/user-attachments/assets/84c95b04-8cba-446f-ba3d-443213e5afc5" />



4. Sentiment Distribution


<img width="1530" height="792" alt="Screenshot 2026-10-20 120125" src="https://github.com/user-attachments/assets/82328831-4ba0-4968-a2c5-fceb0074fb7d" />
    

# 11. Repository Structure
    
Social-Media-Sentiment-Analysis/
├── README.md

├── Sentiment_Analysis.ipynb

├── social_media_sentiment_1003_rows.csv

├── Sentiment_Analysis_Dashboard.pbix

├── dashboard.png

# 12. Future Enhancements
    
- Analyze real-world social media data with appropriate permissions.
- Apply and evaluate an NLP sentiment classifier on raw post text.
- Add keyword and hashtag analysis.
- Add more engagement metrics and platform comparisons.
- Automate data refreshes where a supported data source is available.

# Author

# Vedika Ghadge
 
email 📧 - [vedikaghadge613@gmail.com]

🔗 din - [https://www.linkedin.com/in/vedika-ghadge-827395327/?isSelfProfile=true]


