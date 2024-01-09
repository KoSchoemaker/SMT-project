dataset_collection: use the excel files to generate mp3 files of the songs
lyric_extraction: use the excel files to generate text files with lyrics (not particularly tested or anything)

to be done
feature_extraction: use mp3 files to extract relevant musical features or other musical information

## Sentiment Analysis of Spotify Playlist

` sentiment_analysis.ipynb` analyzes the sentiment of songs in a Spotify playlist by fetching lyrics and using sentiment analysis.

### Prerequisites

- Python 3.x
- Install required packages using `pip install -r requirements.txt`

### Setup

1. Obtain Spotify API credentials and Genius API access token.
2. Set up environment variables for API credentials.
   1. Find the `sample.env` file in the repository.
   2. Copy this file to a file named `.env`
3. Install required dependencies: `pip install -r requirements.txt`

### Usage

1. Replace 'playlist_uri' in the script with the URI of your Spotify playlist. (Bottom of the notebook)
2. Run the `analyze_playlist` function.
3. Use the last code cell to save the results to a .csv

### Interpretation
The sentiment scores can be interpreted as follows:
- $<0$: Negative
- $0$: Neutral
- $>0$: Positive