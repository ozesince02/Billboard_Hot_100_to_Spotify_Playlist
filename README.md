Billboard Hot 100 to Spotify Playlist
Overview

This Python script allows you to create a Spotify playlist based on the Billboard Hot 100 chart for a specific date. It fetches the top songs from Billboard for the given date and searches for them on Spotify, adding them to a new private playlist.

Prerequisites

Before you can use this script, you'll need the following:

    Python 3: Make sure you have Python 3 installed on your system.

    Required Python Libraries: You can install the necessary Python libraries using pip:

    bash

    pip install requests spotipy beautifulsoup4

    Spotify API Credentials:
        You'll need a Spotify developer account and create an application to obtain the following credentials:
            SPOTIFY_CLIENT_ID: Your Spotify client ID.
            SPOTIFY_CLIENT_SECRET: Your Spotify client secret.
        You can create a Spotify developer application at the Spotify Developer Dashboard.

    Redirect URI: Set a redirect URI for your Spotify application in the Spotify Developer Dashboard. This URI should match the REDIRECT_URI specified in the script.

Usage

    Clone the repository or download the script to your local machine.

    Set up the required environment variables:
        SPOTIFY_CLIENT_ID: Your Spotify client ID.
        SPOTIFY_CLIENT_SECRET: Your Spotify client secret.
        REDIRECT_URI: The redirect URI you specified for your Spotify application.

    You can set these environment variables in your system or use a tool like python-dotenv to load them from a .env file.

    Run the script using Python:

    bash

    python billboard_to_spotify.py

    The script will prompt you to enter a date in the "YYYY-MM-DD" format for the Billboard Hot 100 chart you want to use.

    The script will then create a new private Spotify playlist with the Billboard chart's date and add the corresponding tracks to the playlist.

    Sit back and enjoy your personalized Billboard Hot 100 playlist on Spotify!

Important Notes

    Please be aware that the script relies on the structure of the Billboard website to scrape data. Any changes to the website's structure may break the scraping functionality.

    The Spotify API and its usage may change over time. Refer to the latest Spotify API documentation for updates or changes.

    This script was last tested and known to work as of 12th March 2023.
