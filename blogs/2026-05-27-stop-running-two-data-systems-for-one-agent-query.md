---
title: "Stop Running Two Data Systems for One Agent Query"
url: "https://dzone.com/articles/single-data-system-agent-query"
date: "2026-05-27"
author: "Varun Srinivas"
feed_url: "https://feeds.dzone.com/home"
---
If you've deployed a retrieval-augmented generation (RAG) pipeline over enterprise data, you've probably ended up in the same place: Pinecone or Weaviate for embeddings, Delta Lake or Iceberg for structured data, and some custom middleware stitching them together that nobody fully owns. This split made sense historically. Vector databases existed before lakehouse formats efficiently supported high-dimensional arrays.
