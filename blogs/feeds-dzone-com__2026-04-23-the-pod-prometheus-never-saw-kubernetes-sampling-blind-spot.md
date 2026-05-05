---
title: "The Pod Prometheus Never Saw: Kubernetes' Sampling Blind Spot"
url: "https://dzone.com/articles/k8s-sampling-blind-spot"
date: "Thu, 23 Apr 2026 13:30:01 GMT"
author: "Shamsher Khan"
feed_url: "https://feeds.dzone.com/containers"
---
<h2>The Fix That Doesn't Fix It</h2>
<p>Reducing your Prometheus scrape interval from 15 seconds to 5 seconds does not fix the sampling blind spot. It moves it. Any pod whose entire lifetime falls within one 5-second scrape gap is still structurally invisible — not because of misconfiguration, not because of missing rules, but because poll-based collection has an irreducible sampling gap that no interval setting eliminates.</p>
<p>This article explains exactly why that is, what it costs in production, and what actually fixes it.</p>
