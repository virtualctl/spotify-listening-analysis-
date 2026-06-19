# spotify-listening-analysis-
Personal Spotify Streaming Analysis via Last.fm export 


This project analyzes my personal Last.fm listening history from 2023–2026 using Python and pandas.

The goal was to transform raw scrobble data into a synthesized list showing listening habits, favorite artists, albums, and tracks over time!

The project includes:
  - Data cleaning and preprocessing
  - Datetime feature engineering
  - Exploratory data analysis
  - Interactive command-line menu
  - Top artist, album, and song analysis
  
Tools used:
  - Python
  - Pandas
  - Jupyter Notebook
  - VS Code

The dataset contains 92,700+ scrobbles exported from my Last.fm.
  
Original fields included:
  - Unix timestamps
  - Artist metadata
  - Album metadata
  - Track metadata

After cleaning, the fields became:
  - datetime
  - year
  - month
  - day
  - track
  - artist
  - album

What I learned:
  - Data cleaning with pandas
  - Datetime manipulation
  - Aggregation using groupby() and value_counts()
  - Building reusable functions
  - Exception handling
  - Structuring a complete analytics workflow

Future Improvements:
  - Visualize listening trends with matplotlib
  - Add yearly comparison dashboards
  - Integrate Last.fm API for live data retrieval
  - Identify artist discovery patterns over time
  - Build a web interface using Flask
