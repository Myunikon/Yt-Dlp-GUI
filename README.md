# YT DLP GUI**

**YT-DLP**  
*A feature-rich command-line audio/video downloader*

[![Download](https://img.shields.io/badge/DOWNLOAD-v2025.04.30-brightgreen)](#)
[![PyPI](https://img.shields.io/pypi/v/yt-dlp)](https://pypi.org/project/yt-dlp/)
[![Donate](https://img.shields.io/badge/Donate-%E2%9D%A4-red)](#)
[![Discord](https://img.shields.io/badge/Discord-3.2K%20ONLINE-blue)](#)
[![Supported Sites](https://img.shields.io/badge/Supported%20Sites-Click-green)](#)
[![License: Unlicense](https://img.shields.io/badge/license-MIT_License-blue.svg)](#)

---

`yt-dlp` is a feature-rich command-line audio/video downloader with support for [thousands of sites](#).  
The project is a fork of [youtube-dl](https://github.com/ytdl-org/youtube-dl) based on the now inactive [youtube-dlc](https://github.com/blackjack4494/yt-dlc).

---

# **Features**
- ✅ Download from multiple platforms: YouTube, Vimeo, TikTok, Instagram, Facebook, and more
- ✅ Intuitive user interface: Easy to use even for beginners
- ✅ Concurrent download: Download multiple videos in parallel
- ✅ Format support: Choose the desired video and audio format
- ✅ Subtitle support: Download subtitles in multiple languages
- ✅ Playlist download: Download the entire playlist or select specific videos
- ✅ Performance monitoring: Monitor system resource usage
- ✅ Error handling: User-friendly error messages

# **System Requirements**
- Python 3.8 or later
- Operating system: Windows, macOS, or Linux
- Stable internet connection
- Minimum 100MB of free disk space

# **Instalation**

Method 1: Installation from Source
1. Make sure Python and pip are installed on your system
2. Clone this repository:
 ```bash
git clone https://github.com/Myunikon/Yt-Dlp-GUI.git
cd Yt-Dlp-GUI
```
3. Install required dependencies
 ```bash
pip install -r requirements.txt
```
4. Run the application
 ```bash
python -m src.main
```
Method 2: Installation with Executable (Windows)
1. Download the latest installer file from the releases page
2. Run the installer and follow the on-screen instructions
3. Once the installation is complete, run Ytt_dlp from the Start menu or desktop shortcut

## How to Use
1. Enter URL : Paste the URL of the video or playlist you want to download
2. Select Format : Select the desired video/audio format (mp4, webm, mp3, etc.)
3. Select Directory : Specify the location where the downloaded file will be saved
4. Additional Options : Adjust subtitle settings, quality, etc. (optional)
5. Start Download : Click the "Download" button to start the process
## Configuration
Ytt_dlp stores its configuration in the default location of your operating system:

- Windows: %APPDATA%\YtdlpGUI\config.json
- macOS: ~/Library/Application Support/YtdlpGUI/config.json
- Linux: ~/.config/YtdlpGUI/config.json
Configurable settings:

- Default download directory
- Maximum number of concurrent downloads
- Application theme (light/dark)
- Interface language
- Download history storage
- Default download quality
## Supported Domains
Ytt_dlp supports downloads from a variety of platforms, including:

- YouTube (youtube.com, youtu.be)
- Vimeo (vimeo.com)
- Dailymotion (dailymotion.com)
- Twitch (twitch.tv)
- TikTok (tiktok.com)
- Instagram (instagram.com)
- Facebook (facebook.com, fb.watch)
For a complete list of supported domains, see the config/allowed_domains.txt file.

## Troubleshooting
### Common Issues
1. yt-dlp not found

- Make sure yt-dlp is installed correctly: pip install yt-dlp
- Make sure yt-dlp is in the system PATH
2. Download fails with HTTP error

- Check your internet connection
- Make sure the video URL is valid and accessible
- Some videos may be geo-restricted or require login
3. The app is running slowly

- Reduce the number of concurrent downloads in settings
- Close other resource-intensive apps
### Error Logs
The app logs are stored in the logs/ytdlp_studio.log directory. Include this log file when reporting an issue

### Contributions
Contributions are very welcome! Please follow these steps:

1. Fork this repository
2. Create a new feature branch ( git checkout -b new-feature )
3. Commit your changes ( git commit -m 'Adding new feature' )
4. Push to the branch ( git push origin new-feature )
5. Create a Pull Request
## License
This project is licensed under the MIT License .

## Credits
- Built on yt-dlp
- User interface using Kivy
- Icons and visual assets from Material Design Icons
Made with ❤️ by Myunikon
