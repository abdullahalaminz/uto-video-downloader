# Auto-video-downloader

A Node.js app for automated video downloading using [yt-dlp](https://github.com/yt-dlp/yt-dlp) and [FFmpeg](https://ffmpeg.org/).

This application allows you to download videos from various platforms automatically, convert and process them with FFmpeg, and manage your downloads efficiently.

---

## Features

- Download videos and playlists from multiple sites supported by yt-dlp.
- Automatic video format and quality selection.
- Video/audio conversion and processing using FFmpeg.
- Supports resume and retry on interrupted downloads.
- Save downloaded videos to customizable local folders.
- Simple and extensible Node.js backend.

---

## Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher recommended)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) installed and accessible in your system PATH
- [FFmpeg](https://ffmpeg.org/) installed and accessible in your system PATH

---

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/abdullahalaminz/auto-video-downloader.git
   cd auto-video-downloader


2. **Install Node.js dependencies**

   ```bash
   npm install

3. **Install yt-dlp**
   Download and install from yt-dlp releases or via package managers.
   Make sure yt-dlp is accessible from your terminal:

   ```bash
   yt-dlp --version

3. **Install FFmpeg**
   Download and install from FFmpeg official site or use your OS package manager.
   Verify FFmpeg installation:

   ```bash
   ffmpeg -version


4. ** Run the application **
   For development mode with auto-reload (requires nodemon):

   ```bash
   npm run dev

5. **Or run normally with:**

   ```bash
   node index.js

6. **Note: If you don’t have nodemon installed, you can install it globally:**
   ```bash
   npm install -g nodemon
