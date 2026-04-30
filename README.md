# UNTA Rescue Tracker

A lightweight tool for Elite Dangerous that tracks evacuation missions and uploads results to a live squadron leaderboard.

## Features

- Automatically detects Elite Dangerous journal files
- Tracks ALL evacuation passenger missions
- Displays live session stats
- Uploads data to a shared Google Sheet
- Simple UI – no setup required

## How to Use

1. Download the `.exe` from releases
2. Open the app while playing Elite Dangerous
3. Leave it running
4. Complete evacuation missions normally

Your rescues will be tracked automatically.

## Safety / Transparency

This tool:
- Only reads Elite Dangerous journal files locally
- Only sends mission data (passenger count, system, station)
- Does NOT access personal files or sensitive data

You can review the full source code here.

## Requirements (if running from source)

- Python 3.10+
- Install dependencies:

```bash
pip install -r requirements.txt
