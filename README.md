# Flippr - MP3

A local web application for converting YouTube videos to MP3 format.

## ⚠️ Important Notice

**This application is for personal use and educational purposes only.** 

This project was created as a practice exercise to learn web development with Flask and yt-dlp. It is NOT intended for commercial use, redistribution, or any activity that violates YouTube's Terms of Service. Users are responsible for ensuring their usage complies with all applicable laws and terms of service.

## Requirements

- Python 3.8+
- FFmpeg (required for audio conversion)

## Setup

1. **Install FFmpeg** (if not already installed):
   - **Windows**: Download from https://ffmpeg.org/download.html or use `winget install ffmpeg`
   - **Mac**: `brew install ffmpeg`
   - **Linux**: `sudo apt install ffmpeg` or `sudo yum install ffmpeg`

2. **Install Python dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Start the server**:
   ```bash
   python app.py
   ```

2. **Open your browser** and navigate to:
   ```
   http://localhost:5000
   ```

3. **Download audio**:
   - **Search Mode**: Enter a song name or artist and select from results
   - **URL Mode**: Paste a YouTube URL directly
   - Optionally specify a download location (defaults to Downloads folder)
   - Click "Download MP3"
   - The MP3 file will be saved to your specified location

## Features

- Clean, modern interface with dark/light theme switching
- Search YouTube by song name or artist
- Direct URL input with video preview
- Custom download location selector
- High-quality MP3 conversion (192kbps)
- Real-time progress indicator
- Responsive status messages

## Notes

- Default download location is your system's Downloads folder
- Files are saved with the video title as the filename
- Requires active internet connection to download videos
- This tool is for personal, non-commercial use only
