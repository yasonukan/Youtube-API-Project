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

## Future Improvements

- Extract more detailed video information
- Implement sentiment analysis of video comments
- Integrate with machine learning algorithms for predictions

Feel free to work on this repository and contribute your own improvements.

