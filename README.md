# YouTube API: Analysis of Channels and Videos

This project provides an analysis of YouTube channels and videos using the YouTube Data API.

## Features

- Retrieves channel statistics
- Retrieves video IDs
- Extracts video details and statistics

## Setup

1. First, install the necessary Python packages using pip:

- pip install pandas pip install google-api-python-client
- pip install ipywidgets
  

2. Obtain an API key from the Google Cloud Console by following the instructions [here](https://developers.google.com/youtube/v3/getting-started).

3. Set the environment variable `YOUTUBE_API_KEY` to the obtained API key.

4. Clone this repository:
- git clone https://github.com/user/youtube-api-project.git
  

5. Run the script `api_methods.py`:


This script demonstrates the use of the API by retrieving and displaying channel statistics and video details.

## API Methods

- `get_channel_stats(channel_id)`: Retrieves the statistics of a specified channel.

- `get_video_ids(channel_id, max_results)`: Retrieves a list of video IDs uploaded by a specified channel.

These methods utilize the YouTube Data API's channels and search endpoints, respectively.
## Project Analysis
![image](https://github.com/yasonukan/Youtube-API-Project/assets/73828987/52f4e60b-f591-4c77-8012-f75425a9212a)1
![image](https://github.com/yasonukan/Youtube-API-Project/assets/73828987/32ae413e-aa51-4485-9ade-8a67d2f363ea)
![image](https://github.com/yasonukan/Youtube-API-Project/assets/73828987/6b403d9b-0c25-44ae-94a9-029ac8e3ad46)


### Sentiment Analysis

![image](https://github.com/yasonukan/Youtube-API-Project/assets/73828987/1d842e0f-7678-4d24-b7e9-6309f14b5237)
![image](https://github.com/yasonukan/Youtube-API-Project/assets/73828987/48939f6e-b34b-4f0b-a183-fe5007a2c3a2)






## Future Improvements

- Extract more detailed video information
- Implement sentiment analysis of video comments
- Integrate with machine learning algorithms for predictions

Feel free to work on this repository and contribute your own improvements.

