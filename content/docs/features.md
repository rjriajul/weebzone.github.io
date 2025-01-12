---
weight: 200
title: "Features"
description: "Introduction to Telegram, WZML-X Features & Usage."
author: "SilentDemonSD"
icon: auto_awesome
draft: false
---

# WZML-X Features  

WZML-X offers a comprehensive range of features, enabling users to efficiently manage downloads, uploads, and cloud integrations, all via Telegram commands. Below is a detailed guide to the available commands categorized by functionality.

---

## ⌬ Basic Commands  

### Mirror Commands  
Use these commands to download files or URLs and upload them to your Cloud Drive:  
- **`/mirror` or `/m`**: Download via file, URL, or media to upload to Cloud Drive.  
- **`/ctsel`**: Select a custom category to upload to Cloud Drive from User TDS or Bot Categories.  

### Torrent Commands (qBittorrent Only)  
Handle torrents effectively with the following commands:  
- **`/qbmirror` or `/qm`**: Download torrents using qBittorrent and upload to Cloud Drive.  
- **`/btsel`**: Select specific files from torrents using `btsel_gid` or by replying to the torrent message.  

### yt-dlp Commands  
Download media from YouTube or other yt-dlp-supported sites:  
- **`/ytdl` or `/y`**: Mirror links supported by yt-dlp.  

### Leech Commands  
Upload files directly to Telegram:  
- **`/leech` or `/l`**: Upload files to Telegram.  
- **`/qbleech` or `/ql`**: Download using qBittorrent and upload to Telegram (for torrents only).  
- **`/ytdlleech` or `/yl`**: Download using yt-dlp and upload to Telegram.  

### Google Drive Commands  
Manage Google Drive files with ease:  
- **`/clone`**: Copy files or folders to Cloud Drive.  
- **`/count [drive_url]`**: Count files or folders and calculate their size in Google Drive.  
- **`/del [drive_url]`**: Delete files or folders from Google Drive (Owner & Sudo only).  

### Task Management  
Manage ongoing tasks:  
- **`/cancel`**: Cancel a task using `cancel_gid` or by replying to a message.  

---

## ⌬ Users Commands  

### Bot Settings  
- **`/usetting` or `/us [query]`**: Open user-specific settings (can also be used in private messages).  

### Authentication  
- **`/login`**: Login to the bot for access without the temporary pass system (Private only).  

### Bot Stats  
- **`/status` or `/s`**: View a status page of all active tasks.  
- **`/stats` or `/st`**: View detailed server statistics.  
- **`/ping` or `/p`**: Check the bot's responsiveness.  

### RSS Feed  
- **`/rss`**: Open the RSS menu to subscribe, unsubscribe, start, or pause feeds.  

---

### Extras  
- **`/speedtest` or `/sp`**: Check server speed.  
- **`/mediainfo` or `/mi [url/media]`**: Generate media info for files or downloadable URLs.  

### Search Tools  
- **`/list [query]`**: Search for files in Google Drive.  
- **`/search [query]`**: Search for torrents using an API.  

### Entertainment Search  
- **`/imdb [query]`**: Search for movies or TV shows on IMDb.  
- **`/anime [query]`**: Search for anime on AniList.  
- **`/mdl [query]`**: Search for dramas on MyDramaList.  
- **`/animehelp`**: Access a guide for using anime-related features.  

---

## ⌬ Owner or Sudo Commands  

### Bot Settings  
- **`/bsetting` or `/bs [query]`**: Open bot-specific settings (Owner & Sudo only).  
- **`/users`**: Show user statistics (Owner & Sudo only).  

### Authentication  
- **`/authorize` or `/a`**: Authorize a user or chat to use the bot (Owner & Sudo only).  
- **`/unauthorize` or `/ua`**: Revoke authorization for a user or chat (Owner & Sudo only).  
- **`/addsudo`**: Add a Sudo user (Owner only).  
- **`/rmsudo`**: Remove a Sudo user (Owner only).  
- **`/blacklist` or `/bl`**: Blacklist a user from accessing the bot (Owner & Sudo only).  
- **`/rmblacklist` or `/rbl`**: Remove a user from the blacklist (Owner & Sudo only).  

### Bot Stats and Logs  
- **`/broadcast` or `/bc [reply_msg]`**: Send a broadcast message to all users.  
- **`/log`**: Retrieve bot logs for debugging (Owner & Sudo only).  

### Maintenance  
- **`/restart` or `/r`**: Restart and update the bot (Owner & Sudo only).  
- **`/restartall`**: Restart and update all bots (Owner only).  
- **`/clearlocals`**: Clear locals for eval or exec commands (Owner only).  

### Executors  
- **`/shell`**: Run shell commands (Owner only).  
- **`/eval`**: Execute Python code lines (Owner only).  
- **`/exec`**: Run commands in Exec mode (Owner only).  
- **`/exportsession`**: Generate a string session for the bot (Owner only).  

### Google Drive Maintenance  
- **`/gdclean` or `/gc [drive_id]`**: Clean a specific folder in Google Drive (Owner & Sudo only).  

