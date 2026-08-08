---
title: "Calling GCP From AWS Without Static Keys Using Open-Source MultiCloudJ"
url: "https://dzone.com/articles/cross-cloud-aws-to-gcp"
date: "2026-08-03"
author: "Sandeep Pal"
feed_url: "https://feeds.dzone.com/home"
---
In Part 1 , we solved one direction of the multi-cloud connectivity problem: a workload running in Google Cloud interacting with an AWS cloud resource. A GKE pod read a Google-issued OIDC token from the metadata server, handed it to AWS STS via AssumeRoleWithWebIdentity, and received short-lived AWS credentials, with no static access keys stored anywhere. MultiCloudJ wrapped the token dance behind a portable client so the application code never touched a provider SDK directly.
