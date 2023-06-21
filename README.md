# Spark-YouTube-Video-Popularity
YouTube data collection (API), EDA and popularity prediction using Spark


## Project structure
- [`Youtube parser Git.ipynb`](/Youtube%20parser%20Git.ipynb) - notebook with code to get data about videos using Youtube API
- [`EDA.ipynb`](/EDA.ipynb) - notebook with collected data description, exploratory data analysis and creation of dataset for popularity prediction
- [`wordcloud.ipynb`](/wordcloud.ipynb) - notebook with word clouds implementation for titles of videos from different categories (themes)
- [`forecasting_dynamic_of_video_publishing.ipynb`](/forecasting_dynamic_of_video_publishing.ipynb) - notebook where different approaches to forecast number of video published each day are explored
- [`Prediction Spark.ipynb`](/Prediction%20Spark.ipynb) - notebook with prediction of video popularity
- [`Prediction (without mean_popularity).ipynb`](/Prediction%20(without%20mean_popularity).ipynb) - notebook with prediction of video popularity without using info about mean popularity of videos on the channel for the last 30 days 
