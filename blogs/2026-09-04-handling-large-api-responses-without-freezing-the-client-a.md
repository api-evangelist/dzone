---
title: "Handling Large API Responses Without Freezing the Client: A Practical Architecture With Temporal, Kafka, and RAG"
url: "https://dzone.com/articles/large-api-responses-client"
date: "2026-09-04"
author: "Uthej Mopathi"
feed_url: "https://feeds.dzone.com/home"
---
A large API response becomes a client problem long before it becomes a network problem. A browser can receive hundreds of megabytes and still become unresponsive while buffering bytes, parsing one enormous JSON document, retaining duplicate object graphs, and rendering too much state on the main thread. The reliable solution is not a larger timeout.
