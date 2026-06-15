---
title: "A Spring Boot App With Half the Startup Time"
url: "https://dzone.com/articles/spring-boot-startup-time"
date: "2026-06-12"
author: "Sven Loesekann"
feed_url: "https://feeds.dzone.com/home"
---
The MovieManager project has been updated to use JDK 25 and the AOT cache from project Leyden . Project Leyden is part of the OpenJDK project and provides cached linking and cached performance statistics. That means the time spent linking at startup is moved to build time, and the statistics are created during a test run at build time as well.
