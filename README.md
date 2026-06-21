# Spotify Artist Analytics Dashboard

An analytics dashboard for artists using the Spotify Web API to track performance, analyze audio features, and gain audience insights.

## Features

- 📈 **Artist Metrics**: Monthly listeners, followers, popularity trends
- 🎼 **Audio Analysis**: BPM, energy, danceability, valence per track
- 🎯 **Competitive Analysis**: Compare against similar artists
- 🗺️ **Audience Insights**: Geographic and demographic breakdowns
- 📊 **Playlist Reach**: Track playlist placements and reach
- 🤖 **AI Recommendations**: Genre-matched track suggestions

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your Spotify credentials

# Run the dashboard
python src/dashboard.py
