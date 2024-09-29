**Spotify Dashboard Project**


**Project Description**:

This project provides a detailed analysis of Spotify music data using both Python for data processing and Power BI for dashboard visualization. The project focuses on various metrics like popularity, loudness, and danceability of tracks and artists. By analyzing these metrics, the dashboard aims to deliver insights for music enthusiasts and stakeholders looking to understand trends in music.


**Project Goal**:

The goal of this project is to analyze key metrics from Spotify’s music dataset and visualize these insights through an interactive Power BI dashboard. The analysis covers artist popularity, track loudness, instrumental albums, and other metrics, offering a comprehensive understanding of the Spotify music landscape.


**Methodology**:

**Python**:

1. Data Importing:
   - Imported the dataset using `read_csv` to load Spotify music data.
   
2. Data Cleaning:
   - Checked for null values in the dataset and handled missing or incorrect data using appropriate techniques such as filling missing values or dropping irrelevant columns.

3. Key Data Analysis:

   - **Top 5 Artists by Popularity**: Ranked the top 5 artists based on their popularity score.

   - **Top 5 Loudest Tracks**: Identified the loudest tracks using loudness data.

   - **Artist with Most Danceability Tracks**: Highlighted the artist whose tracks have the highest danceability scores.

   - **Top 5 Instrumental Albums and Tracks**: Analyzed albums and tracks with the highest instrumentalness scores.


**Power BI**:

1. Dashboard Creation:
   - Used Power BI to create a visually appealing and interactive dashboard that allows users to explore various aspects of the Spotify dataset.
   
2. Visualizations:

   - **Top 5 Famous Tracks**: Visualized the top tracks based on the number of plays.

   - **Top 5 Most Popular Artists**: Displayed the most popular artists.

   - **Top 5 Most Loudest Tracks**: Ranked the loudest tracks.

   - **Top 5 Instrumental Albums**: Showed the top instrumental albums.

   - **Most Energetic Album**: Identified albums with the highest energy scores.


**Technologies Used**:

- Python: For data import, cleaning, and analysis.

  - Libraries: `pandas` (for data handling), `numpy` (for numerical operations).

- Power BI: For creating an interactive and insightful dashboard.


**Visualizations in Dashboard**:

1. **Total Artists, Albums, and Genres**: Summary statistics on the dataset.

2. **Top 5 Famous Tracks**: Bar chart showing the most famous tracks by number of plays.

3. **Top 5 Loudest Artists and Tracks**: Visualizes the loudest artists and tracks.

4. **Top 5 Most Popular Artists**: Displays the most popular artists based on a popularity metric.

5. **Top 5 Most Energetic Albums**: Analyzes albums based on their energy score.

6. **Top 5 Instrumental Albums**: Shows the albums with the highest instrumentalness.


**Screenshot of the Report**:
![image](https://github.com/user-attachments/assets/cee91957-e106-441d-b134-e86050f06d72)


**Key Insights**:

- **Top Artists**: Artists like Drake, Taylor Swift, and Rihanna consistently rank in the top for popularity.

- **Loudness**: Tracks like "In For The Kill" and "Gold Dust" are among the loudest in the dataset.

- **Danceability**: Some artists produce tracks with higher danceability scores, making them popular in energetic playlists.


**Conclusion**:

This project successfully combines Python and Power BI to analyze and visualize Spotify music data. The insights obtained from this analysis can help music analysts, marketers, and enthusiasts make data-driven decisions about music trends and preferences.
