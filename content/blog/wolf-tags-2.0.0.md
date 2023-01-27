---
title: "Wolf Tags 2.0.0 Update"
date: 2023-01-26T03:50:00-05:00
featureImage: images/single-blog/wolf-tags/wolf-tags-thumb.png
postImage: images/single-blog/wolf-tags/wolf-tags.png
tags: Updates
categories: blog
toc: false
---
[Wolf Tags](https://wolf-suite.web.app/bots/wolf-tags) has received an update!

This update is more of a backend update. This is important for developers looking to use Wolf Tags.
# Dependencies Updated
- Discord.JS has been updated from `13.9.0` to `14.7.1`.
- Sapphire Framework has been updated from `3.0.0-next.72b48bb.0` to `4.0.2`
- Sapphire Plugin Logger has been updated from `2.1.3` to `3.0.1`
- Dotenv has been updated from `16.0.1` to `16.0.3`
- Firebase-Admin has been updated from `11.0.0` to `11.5.0`
- UUID has been updated from `8.3.2` to `9.0.0`

# Code Changes
- Screaming Snake Case is no longer used in favor of Pascal Case (required for DJS v14)
- Constructors have been renamed to Builders (required for DJS v14)
- Various changes for Discord.JS v14

# Docker
There is now a Dockerfile for building images of Wolf Tags! It is based off of `node:18`. Please note that it uses `pm2` for managing the process instead of `node`. 

**That's all the new content! Thanks for reading!**
