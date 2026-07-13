---
title: "Background Work, Push Topics, and Richer Notifications"
url: "https://feeds.dzone.com/link/23567/17373836/background-work-notifications"
date: "2026-07-06"
author: "Shai Almog"
feed_url: "https://feeds.dzone.com/deployment"
---
The work that happens while your app is not in the foreground has always been the fiddly part of mobile development, and Codename One's coverage of it had gaps. PR #5142 modernizes local notifications, push, background execution, and shared content across the core, JavaSE, Android, and iOS, and importantly, it makes all of it work in the simulator so you can iterate without a device. Background Work With Constraints The new com.codename1.background package schedules work that the OS runs when its conditions are met, mapping to Android JobScheduler and iOS BGTaskScheduler underneath.
