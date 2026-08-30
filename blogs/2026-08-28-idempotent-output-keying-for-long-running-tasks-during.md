---
title: "Idempotent Output Keying for Long-Running Tasks During Rolling Deployments"
url: "https://dzone.com/articles/idempotent-output-keying-rolling-deployments"
date: "2026-08-28"
author: "Kiran Kumar Manku"
feed_url: "https://feeds.dzone.com/home"
---
A scheduled job that needs ninety to one hundred eighty seconds to produce a single output file looks harmless until the day you ship a new build while it is still running. The deployment controller drains the old task and starts a replacement. For a window of two or three minutes, both replicas are alive, both read the same input snapshot, and both intend to write the same logical output.
