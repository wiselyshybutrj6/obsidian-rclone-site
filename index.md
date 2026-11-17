
# Obsidian Rclone

Obsidian Rclone is a personal file synchronization workflow.

## Purpose

This application is used to maintain a backup mirror of my personal Obsidian notes in Google Drive.

## How It Works

1. Obsidian synchronizes notes between my devices and Alibaba Cloud OSS.
2. A private server runs rclone to copy changes from Alibaba Cloud OSS to Google Drive.
3. New, modified, and deleted files are mirrored in one direction.
4. Google Drive is used as a backup and document access location.

## Google Drive Access

The application requests Google Drive access to create, update, list, and delete files in the designated backup folder.

This is a personal-use application and is not offered as a public synchronization service.

## Privacy

Read the [Privacy Policy](privacy.html).
