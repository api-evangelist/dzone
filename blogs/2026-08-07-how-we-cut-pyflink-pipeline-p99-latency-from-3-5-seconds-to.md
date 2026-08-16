---
title: "How We Cut PyFlink Pipeline p99 Latency from 3-5 Seconds to ~500ms"
url: "https://dzone.com/articles/how-we-got-pyflink-under-half-a-second-of-end-to-e"
date: "2026-08-07"
author: "Arjun Shah"
feed_url: "https://feeds.dzone.com/java"
---
The Problem: Our p99 Was 3-5 Seconds Our PyFlink pipeline was missing its latency SLO by seconds. The pipeline itself was straightforward: consume events from Kafka, transform them, serialize them as Protobuf, and write the results to downstream systems. Yet under production load, p99 end-to-end latency was consistently in the 3-5 second range.
