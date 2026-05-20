---
title: "Solving the Mystery: Why Java RSS Grows in Docker on M1 Macs"
url: "https://dzone.com/articles/java-rss-growth-docker-m1"
date: "Tue, 12 May 2026 19:00:00 GMT"
author: "Sumeet Sharma"
feed_url: "https://feeds.dzone.com/java"
---
The Problem You're running a Java application in a Docker container on your M1 Mac. Everything works fine, but you notice something strange: The resident set size (RSS) keeps growing, even though your heap usage is stable. After hours of investigation, you find mysterious rwxp memory regions, each exactly 128 MB, accumulating in your process memory map.
