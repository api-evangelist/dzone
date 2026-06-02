---
title: "Building a Zero-Cost Approval Workflow With AWS Lambda Durable Functions"
url: "https://dzone.com/articles/zero-cost-approval-workflow"
date: "2026-05-28"
author: "Harpreet Siddhu"
feed_url: "https://feeds.dzone.com/home"
---
When AWS announced Lambda Durable Functions at re: Invent 2025, my first reaction was, "Okay, but how is this different from Step Functions?" I have been building serverless workflows on AWS for a while now, and Step Functions has always been my go-to service for orchestrating multi-step pipelines. So naturally, I wanted to put this new capability to the test. I decided to build a simple document processing workflow, an ETL pipeline with human-in-the-loop approval using both Durable Functions and Step Functions, then run 1,000 actual document processing workflows through each system.
