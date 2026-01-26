# YouTube to MP3 Converter

A local web application for converting YouTube videos to MP3 format.

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
   - Paste a YouTube URL
   - Optionally specify a download location (defaults to Downloads folder)
   - Click "Extract Audio"
   - The MP3 file will be saved to your specified location

## Features

- Clean, terminal-inspired interface
- Real-time video info preview
- Custom download location
- High-quality MP3 conversion (192kbps)
- Progress status updates

## Notes

- Default download location is your system's Downloads folder
- Files are saved with the video title as the filename
- Requires active internet connection to download videos
