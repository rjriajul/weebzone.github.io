---
weight: 100
title: "Introduction"
description: "Introduction to WZML-X: Simplifying Telegram Automation and File Management."
author: "SilentDemonSD"
icon: newspaper
draft: false
---

# WZML-X Documentation

## Introduction

**WZML-X** stands for **Weeb Zone Mirror Leech of Version X**. It is a Telegram bot designed to perform various tasks by communicating with Telegram and remote servers. WZML-X enables users to automate file transfers, manage cloud storage, and download/upload content from multiple sources such as torrents, Mega, Google Drive, Telegram, and others. 

This bot integrates seamlessly with multiple cloud services and download tools, offering a wide array of features for users who need efficient file management and automation.

### Why Choose WZML-X?

WZML-X provides an all-in-one solution for automating file management tasks. Whether you're downloading media from the internet, managing torrents, or organizing cloud storage, this bot handles it all with ease. By leveraging Telegram's capabilities, it offers users the flexibility to manage their tasks directly from the messaging platform.

## Key Features

### Core Features
- **qBittorrent**: Supports torrent downloading, file selection, and seeding options.
- **Aria2c**: Advanced downloading capabilities with file management and authentication features.
- **Telegram Upload/Download**: Seamlessly upload and download files from Telegram, including handling restricted content.
- **DDL Upload**: Upload files to direct download sites like Gofile.io, Streamtape, etc.
- **Google Drive Integration**: Upload and manage files on Google Drive, with duplicate prevention and recursive search.
- **yt-dlp Integration**: Download videos, audios, and media from various supported websites with customizable quality options.
- **Database (MongoDB)**: Stores bot settings, user preferences, and other critical data for efficient management.
- **Torrent Management**: Comprehensive features for torrent downloads, including file handling and control.
- **Archives**: Compress, extract, and manage multiple archive formats, including password-protected archives.
- **RSS Feed**: Automate downloads from RSS feeds with filtering and customization.
- **RClone Support**: Directly interact with cloud services like Google Drive, Dropbox, etc., for easy file management.

### Additional Features
- **Docker Image Support**: Available for Linux architectures: amd64, arm64/v8, and arm/v7.
- **Asynchronous Operations**: Switch from synchronous to asynchronous processing for faster and more efficient task handling.
- **Bot Framework Upgrade**: Transitioned from python-telegram-bot to pyrogram for improved performance and responsiveness.
- **Configuration Overwrite**: Edit bot variables and overwrite private files while the bot is running, ensuring flexibility.
- **Auto Updates**: Automatically updates the bot at startup and with the `restart` command using the `UPSTREAM_REPO` variable.
- **Enhanced Telegraph**: Built upon the Sreeraj's loaderX-bot to provide better functionality.
- **Multi-Link/Task Handling**: Leech, mirror, clone, count, or delete multiple links/files with a single command.
- **Custom Link Naming**: Customize link names (for all links except torrents) by adding extensions or other specifications.
- **File Extensions Filter**: Filter files based on extensions before uploading or cloning, giving you better control.
- **Link View Button**: Includes an extra button to open the index link in a browser, instead of a direct download.
- **Queueing System**: Efficiently manage and prioritize multiple tasks with an advanced queue system.
- **Bulk Download**: Download multiple files from Telegram by reading links from a `.txt` file or text message with links separated by new lines.
- **File Joining**: Rejoin split files (such as those split by Linux packages) to restore them to their original form.
- **Repository Improvements**: Several improvements and bug fixes have been implemented across the repository for better stability and performance.
- **User Limits**: Control and set limits on bot usage for each user, ensuring fair use across the system.

### Additional Resources:
- **Telegram Channel**: For updates and discussions, visit the [WZML_X Telegram Channel](https://t.me/WZML_X).
- **GitHub Repository**: You can access the full code and contribute to the project on the [GitHub repository](https://github.com/SilentDemonSD/WZML-X).
