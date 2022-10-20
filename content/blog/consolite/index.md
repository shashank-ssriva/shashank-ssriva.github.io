---
author: Shashank Srivastava
title: Consolite - Flask-based UI tool to display EC2 server details with caching support
date: 2022-09-01
---

## Key features:

1. No need to login to AWS Console to get server info like IP address or hostname, etc.
2. Fast & lightweight.
3. Lets you copy the IP address & server name with a click, *just like AWS Console*.
4. Superfast, real-time search. Search for any server using its name or type.
5. Safe. Doesn't store any data in a database or file.
6. Interactive, colorful charts to summarize data.
7. Shows CPU/Memory & Cost info of each server.
8. **Caching enabled**. The table is cached for 60 minuts. Latest data can be pulled with a click of a button.

## Technologies used:

* Python3
* Flask
* Nginx
* Boto3
* Flask-Caching
* Gunicorn
* Supervisord
* Chart.js - for charts & graphs