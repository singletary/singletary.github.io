---
layout: post
microblog: true
date: 2017-06-15 22:01 -0500
guid: http://singletary.micro.blog/2017/06/16/redundant-backups-i.html
---
**Redundant backups**: I wanted to find a solution to securely store my Time Machine backups in an off-site location, so that they were backed up redundantly. I currently back up to a home server with a RAID setup, just for backups, and decided to sync these backups to a cloud storage provider. [Backblaze B2 Cloud Storage](https://www.backblaze.com/b2/cloud-storage.html) is cheap ($0.005/GB/m) and was easy to get set up with [rclone](https://rclone.org/b2/), so I decided to give that a shot. A simple script and crontab entry later, and I've fully automated my redundant remote backup solution. Excited to see how this works out!
