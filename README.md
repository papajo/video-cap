# Video Slide Extractor

A web-based tool that automatically extracts slides from videos. It works with both YouTube videos and local video files.

## Features

- Extract slides from YouTube videos or local video files
- Automatic frame detection to avoid duplicate or empty slides
- Adjustable capture interval and difference threshold
- Download individual slides as PNG images
- Real-time progress tracking
- Simple and intuitive interface

## How to Use

1. Load a video:
   - Enter a YouTube URL and click "Load from URL", or
   - Upload a local video file

2. Configure settings:
   - Adjust the capture interval (milliseconds between captures)
   - Set the difference threshold (determines how different frames need to be)

3. Process the video:
   - Click "Start Processing" to begin
   - Click "Stop Processing" to halt at any time

4. Download slides:
   - Hover over any captured slide
   - Click the "Download" button to save as PNG

## Technical Requirements

- Modern web browser with HTML5 support
- JavaScript enabled
- Internet connection (for YouTube videos)

## Local Development

1. Clone the repository:
   ```bash
   git clone git@github.com:papajo/video-cap.git
   cd video-cap