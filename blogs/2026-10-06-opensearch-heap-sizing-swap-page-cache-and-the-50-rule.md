---
title: "OpenSearch Heap Sizing: Swap, Page Cache, and the 50% Rule"
url: "https://dzone.com/articles/opensearch-heap-sizing"
date: "2026-10-06"
author: "Maxim Muzafarov"
feed_url: "https://feeds.dzone.com/java"
---
OpenSearch is an open-source, distributed search and analytics suite derived as a fork of Elasticsearch and maintained under the Apache 2.0 license. When it comes to memory configuration, the guidance is often reduced to a few rules of thumb: swapoff -a , vm.swappiness=1 , or bootstrap.memory_lock , and allocating 50% of available memory to the JVM heap while leaving the rest for Lucene and the filesystem page cache, OpenSearch off-heap caches, network buffers, and other system needs. These recommendations are repeated throughout documentation, blog posts, and operational guides, yet their ori
