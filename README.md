# 🎵 cliamp - Simple Terminal Music Player

[![Download cliamp](https://img.shields.io/badge/Download-cliamp-brightgreen?style=for-the-badge)](https://github.com/KevRocha/cliamp/releases)

---

cliamp is a music player that works in the Windows command line. It plays streaming radio, podcasts, music files, and internet streams right from your terminal. It supports popular services and formats like Spotify, SoundCloud, YouTube, Icecast, and more. You don’t need a separate music app or a web browser. Just open your terminal and enjoy music.

---

## 🎯 What is cliamp?

cliamp is a terminal-based music player for Windows. It lets you listen to many kinds of audio without leaving the command line window. 

- Play internet radio and podcasts.
- Stream from services such as Spotify and SoundCloud.
- Use playlists in M3U format.
- Listen to YouTube videos and audio using yt-dlp.
- Supports Navidrome server for personal music libraries.
- Work with Icecast streaming servers.
  
This app is designed for people who prefer to control music with simple commands in the terminal. It uses a classic Winamp style but works fully in command line.

---

## 💻 System Requirements

To run cliamp on your Windows PC, your system should meet these requirements:

- Windows 10 or newer (64-bit recommended)
- At least 2 GB of RAM
- Internet connection for streaming music and podcasts
- A terminal or command prompt app (Windows Terminal, PowerShell, or Command Prompt)
- Optional: VLC media player or similar installed for better audio codec support (recommended but not required)

---

## 🚀 Getting Started

Follow these steps to set up and run cliamp on your Windows PC. No special technical skills needed.

### Step 1: Visit the Download Page

Go to the official cliamp release page here:

[![Download cliamp](https://img.shields.io/badge/Download-cliamp-blue?style=for-the-badge)](https://github.com/KevRocha/cliamp/releases)

This link takes you to all available versions and files for Windows.

### Step 2: Choose the Latest Version

On the release page, look for the latest version. Versions are usually listed as `vX.X.X` with the newest at the top.

### Step 3: Download the Correct File

Find the file for Windows. Typically, it will be named something like:

- `cliamp-windows.zip`
- or `cliamp-windows.exe`

Click the file name to download it to your computer.

### Step 4: Extract or Run the File

- If you downloaded a `.zip` file, right-click it and choose “Extract All.” Choose a folder you can find easily.
- If you downloaded an `.exe` file, double-click to run the program.

### Step 5: Open Terminal or Command Prompt

- Press Windows + R keys, type `cmd` or `powershell` and press Enter.
- Navigate to where you extracted or installed cliamp by typing:  
  `cd path\to\cliamp-folder`  
  Replace `path\to\cliamp-folder` with your actual folder path.

### Step 6: Start cliamp

Type the command below and press Enter to start listening:

```
cliamp
```

---

## 🔧 Basic Usage and Commands

After you start cliamp, use simple commands to control playback. Here are some basic ones:

- `play [url or playlist]` – Start playing a stream or a local music file.
- `pause` – Pause the playback.
- `stop` – Stop the music.
- `next` – Skip to the next track.
- `prev` – Go back to the previous track.
- `volume [0-100]` – Set volume level.
- `list` – Show current playlist.
- `add [url or file]` – Add a track to the playlist.
- `exit` – Close cliamp.

You can load playlists in M3U format or provide streaming URLs. For example:

```
play https://your-podcast-url.com/feed.m3u
```

---

## 🎙 Streaming Sources Supported

cliamp can play many types of streaming audio, including:

- Icecast internet radios
- Spotify streams (requires login with Navidrome)
- SoundCloud tracks
- YouTube videos and playlists (using yt-dlp)
- Podcasts from RSS feeds
- Personal music libraries through Navidrome server connection

The app supports all common audio formats like MP3, AAC, OGG, and FLAC.

---

## 🎛 Advanced Tips

- To link cliamp with a Navidrome server, set your server address in the config file for access to your music library.
- Use `yt-dlp` integration to stream YouTube audio without downloading files.
- Use `cliamp add [url]` to build your playlist while listening.
- Press arrow keys in the terminal to navigate menus and playlists if supported.
- Save your current playlist for playback later using `save playlist.m3u`

---

## 🔄 Updating cliamp

To update cliamp:

1. Go back to the [release page](https://github.com/KevRocha/cliamp/releases).
2. Download the latest Windows version.
3. Extract or replace the old files with the new ones.
4. Run the new version from your terminal.

---

## ⚙ Configuration Files

You can customize cliamp by editing its configuration file usually called `config.json` or `settings.ini` in the installation folder.

Settings you can change:

- Default volume level
- Preferred streaming quality
- Default audio output device
- Navidrome server address and API key
- Playlist save path

Use a text editor like Notepad to edit these files. Changes take effect when you restart cliamp.

---

## 🛠 Troubleshooting

If cliamp does not start or play audio:

- Make sure your system meets the requirements.
- Check your internet connection.
- Confirm you downloaded the Windows version.
- Run the terminal as Administrator.
- Check the volume and audio output settings on your PC.
- If you get errors about missing codecs, install VLC media player or similar.

For streaming errors, verify the URLs or server settings.

---

## 📂 Where to Find More Help

For detailed FAQs and help, check issues and discussions on the [GitHub cliamp page](https://github.com/KevRocha/cliamp).  

You can also find tips from other users or report problems there.  

---

[![Download cliamp](https://img.shields.io/badge/Download-cliamp-brightgreen?style=for-the-badge)](https://github.com/KevRocha/cliamp/releases)