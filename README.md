# dropbox-offline-backup
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)
[![PyPI version](https://img.shields.io/pypi/v/dropbox-offline-backup.svg)](https://pypi.python.org/pypi/dropbox-offline-backup/0.0.5)
[![Python version](https://img.shields.io/badge/python-3-green.svg)](https://www.python.org)

A software which makes offline backup of your whole Dropbox.

## Introduction

Have you ever concerned about the risk if your Dropbox went wrong, i.e. some files are missing or even the whole Dropbox is destroyed?

I have, so I developed this program to make offline backups of Dropbox in case there is something wrong with Dropbox.

You can use `cron` to make the backup automatic.

## Usage

1. Install Python 3 and pip
2. pip install dropbox-offline-backup
3. run `dropboxbackup`
4. edit config file at `/etc/dropboxofflinebackup.conf(Linux)` or `~/.dropboxofflinebackup.conf(macOS)`. At least input the access token.

## Instructions on getting access token

1. Create a Dropbox application at [https://www.dropbox.com/developers/apps](https://www.dropbox.com/developers/apps).

   Note: You have to choose `Full Dropbox` to allow the program to backup your dropbox.

2. Generate an access token and put it into the config file.

## Server recommendation

If you don't know where to put the large backup files, you can check out [time4vps](https://billing.time4vps.eu/?affid=851). They provide virtual private servers with 512GB storage at just 23.88EUR per two years.
