# Birthday Playlist Generator

This Python project automatically generates a playlist based on the Billboard Hot 100 chart from a specific date and adds it to your Spotify account.

## How It Works

1. Enter a date in `YYYY-MM-DD` format to specify the date of the Billboard Hot 100 chart.
2. The script scrapes the song names from the Billboard website for that date.
3. It searches for the songs on Spotify by title and adds them to a new private playlist.

## Requirements

- Python 3.x
- Libraries: `requests`, `beautifulsoup4`, `spotipy`, and others that listed in `requirements.txt`

## How to Run

1. Clone this repository to your local machine.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt

![Uploading ChatGPT Image Apr 28, 2025, 04_50_15 PM.png…]()
