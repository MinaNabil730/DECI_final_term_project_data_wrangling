# DECI Final Term Project: Data Wrangling

## Overview

This project involves data wrangling, analysis, and visualization of the WeRateDogs Twitter archive. The dataset includes various features like tweet content, dog breed predictions, retweet and favorite counts, and dog stages. The goal is to clean the data, uncover key insights, and visualize the findings.

## Files in this Repository

- **`wrangle_act.ipynb`**: Jupyter notebook containing the complete data wrangling process including data gathering, assessment, and cleaning.
- **`act_report.pdf`**: Analysis report detailing insights and visualizations from the cleaned dataset.
- **`wrangling_report.pdf`**: Report summarizing the data wrangling process and techniques used.
- **`data/`**: Directory containing the raw data files:
    - `twitter-archive-enhanced.csv`: Basic tweet data.
    - `image-predictions.tsv`: Predictions about the breed of dogs based on images.
    - `tweet-json.txt`: Additional tweet data obtained via Twitter API.
- **`cleaned_twitter_archive.csv`**: The new cleaned dataframe saved after the data cleaning process.

## Data Wrangling Process

1. **Data Gathering**: Collected data from three main sources:
    - `twitter-archive-enhanced.csv`: Basic tweet data.
    - `image-predictions.tsv`: Predictions about the breed of dogs based on images.
    - `tweet-json.txt`: Additional tweet data.

2. **Data Assessment**: Identified and documented quality and tidiness issues.

3. **Data Cleaning**: Addressed issues to create a high-quality, tidy master dataset ready for analysis.

4. **Saved Cleaned Data**: The cleaned dataframe was saved in a file called `twitter_archive_master.csv`.

## Key Insights and Visualizations

1. **Popularity of the Golden Retriever**: The most commonly predicted dog breed, known for its versatility and friendly nature.
   
2. **Engagement by Dog Stage**: Tweets featuring "doggo" and "puppo" stages tend to receive higher engagement (retweets and favorites).

3. **Distribution of Dog Ratings**: Generally high ratings with a right-skewed distribution, highlighting a few exceptional outliers.

4. **Dog Ratings by Dog Stage**: Higher median ratings for "doggo" and "puppo" stages, indicating a preference by users.

## How to Use

1. **Clone the repository**:
    ```bash
    git clone https://github.com/MinaNabil730/DECI_final_term_project_data_wrangling.git
    ```

2. **Explore the Jupyter notebook**:
    - Open `wrangle_act.ipynb` to understand the data wrangling process.
    - Execute the cells to see the data cleaning steps and transformations.

3. **Read the reports**:
    - `act_report.pdf` for insights and visualizations.
    - `wrangling_report.pdf` for details on data wrangling techniques.

## Visualizations

1. **Popularity of the Golden Retriever**:
   
    ![image](https://github.com/user-attachments/assets/4fcf84d2-0f6d-4df1-a2f4-e755c616a706)

2. **Engagement by Dog Stage**:
 
    ![image](https://github.com/user-attachments/assets/a8e792cc-bb85-41b4-96b2-0c6f6179e6d1)

3. **Distribution of Dog Ratings**:
   
    ![image](https://github.com/user-attachments/assets/07bcda61-3996-4370-aeea-3a96b1a9da44)

4. **Dog Ratings by Dog Stage**:
   
    ![image](https://github.com/user-attachments/assets/ef515a78-554c-419b-94c9-b92bc4b454e7)
   

## Conclusion

The project successfully cleaned and analyzed the WeRateDogs dataset, providing valuable insights into user engagement and preferences. These findings can guide content creation and audience engagement strategies on social media platforms.
