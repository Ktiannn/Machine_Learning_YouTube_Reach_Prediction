# Machine Learning - YouTube Reach Level Prediction
This project was developed as a team collaboration. I was responsible for the data processing pipeline, which involved transforming raw datasets into a modeled-ready version and performing feature engineering to extract 14 key predictors, and then developed and executed the XGBoost model to generate the final predictive results. My teammates focused on the Random Forest model and the cross-model performance comparison.

## Project Overview
  This project is to develop and evaluate a predictive model to estimate a YouTube video's "Reach Level" within the Hong Kong and Taiwan markets prior to its publication, while identifying the key drivers that significantly influence video performance.

## Dataset Description
  The dataset from Kaggle about trending YouTube videos globally and provided a comprehensive perspective, containing **over 7.63 million video records** spanning 110 countries and regions and it was **14GB**, which is impossible to load directly into Pandas. I implemented DuckDB to interface with the massive CSV file. 
  
  By filtering the data by the ‘video_trending_country' column, isolating **Hong Kong** and **Taiwan**. This resulted in a refined subset of **24,086 records**, providing a targeted foundation for training models.
