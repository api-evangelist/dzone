---
title: "How We Diagnosed a Hidden Scheduler Failure in a Docker Swarm Cluster Serving 2 Million Users"
url: "https://feeds.dzone.com/link/23561/17334869/docker-swarm-scheduler-failure"
date: "2026-05-05"
author: "Denis Tiumentsev"
feed_url: "https://feeds.dzone.com/cloud-architecture"
---
Context: 120 Nodes, Strict SLAs, and Legacy Infrastructure Our team is responsible for the mobile backend infrastructure serving over 2 million registered users. The Docker Swarm cluster consists of 120 nodes: 5 manager nodes, 40 worker nodes, and the rest are infrastructure servers. The cluster runs about 50 services, totaling hundreds of replicas. We inherited Swarm from the previous contractor. The client is not yet ready to migrate to Kubernetes, and Swarm is currently sufficient for the current scale.
