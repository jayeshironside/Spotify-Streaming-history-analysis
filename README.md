# Spotify Streaming History Analysis

## Overview
This project focuses on analyzing and visualizing Spotify streaming history data to gain insights into listening habits and preferences. The dataset used for this analysis contains detailed information about the user's listening history, including the date, time, artist, track, and duration of each played song.

## Motivation
The goal of this project is to explore the patterns and trends within the user's Spotify streaming history and extract meaningful insights. By analyzing the data, we aim to answer questions such as:

- What are the user's most frequently listened to artists and tracks?
- Are there any noticeable patterns in listening habits, such as specific time periods or days of the week when the user listens to music the most?
- Can we identify any favorite genres or music styles based on the user's listening history?
- How has the user's listening behavior changed over time?

## Data Source
The data used for this analysis was obtained from the Spotify streaming history feature, which provides users with a downloadable dataset containing their listening history. The dataset is in JSON format and includes information such as track name, artist, album, and timestamp.

## Tools and Libraries Used
- Python 3.8
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## Project Structure
- `data`: This folder contains the Spotify streaming history data file (`spotify_streaming_history.json`).
- `notebooks`: This folder contains the Jupyter Notebook files used for data analysis and visualization.
  - `1_data_preprocessing.ipynb`: Notebook for preprocessing the raw data, cleaning, and transforming it into a suitable format for analysis.
  - `2_exploratory_data_analysis.ipynb`: Notebook for performing exploratory data analysis, generating visualizations, and extracting insights from the data.
- `results`: This folder contains the visualizations generated during the analysis, including charts, graphs, and plots.
- `README.md`: The main readme file for this project.

## How to Use
1. Clone this repository to your local machine.
2. Install the necessary dependencies listed in the `requirements.txt` file.
3. Place your Spotify streaming history data file (`spotify_streaming_history.json`) in the `data` folder.
4. Open and run the Jupyter Notebook files in the `notebooks` folder in sequential order to preprocess the data and perform the analysis.
5. The generated visualizations will be saved in the `results` folder.
6. Refer to the notebooks for detailed explanations and insights derived from the analysis.

## Conclusion
This project provides a comprehensive analysis of Spotify streaming history data, uncovering valuable insights into listening habits, preferences, and trends. By analyzing the data and visualizing the results, we gain a better understanding of the user's music choices and patterns, which can be useful for personalization, recommendation systems, and further research in the field of music analysis.

## Future Work
- Perform sentiment analysis on the user's listening history to determine the overall mood or emotions associated with different tracks.
- Incorporate external data sources, such as song popularity or genre classification, to enhance the analysis.
- Build a recommendation system based on the user's listening history and preferences.

## Acknowledgments
- The Spotify streaming history feature for providing users with access to their listening data.
- The Pandas, Matplotlib, and Seaborn libraries for enabling data analysis and visualization in Python.
- The open-source community for sharing valuable resources and tutorials related to data analysis and visualization.

