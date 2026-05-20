---
title: "Bucket4j + Infinispan: A Deep Dive Into Implementation"
url: "https://dzone.com/articles/bucket4j-infinispan-implementation"
date: "Fri, 01 May 2026 15:00:00 GMT"
author: "Arkadii Osheev"
feed_url: "https://feeds.dzone.com/integration"
---
In distributed systems, the biggest challenge for rate limiting is state . How do you ensure that two parallel requests hitting different cluster nodes don't "double-spend" the same token? In this article, we dive into the implementation details of the integration between the Bucket4j rate-limiting framework and Embedded Infinispan (not HotRod).
