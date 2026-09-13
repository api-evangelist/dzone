---
title: "Foundry IQ Auth, Explained: Managed Identity, OBO, and Everything Between"
url: "https://dzone.com/articles/foundry-iq-auth-explained"
date: "2026-09-09"
author: "Jubin Soni, FBCS"
feed_url: "https://feeds.dzone.com/home"
---
Foundry IQ's pitch is that your agents get one endpoint for grounded, cited, multi-source context instead of a hand-rolled retrieval stack. What doesn't get talked about enough is that "one endpoint" is a bit of a simplification. Underneath it, you're actually managing four separate auth surfaces that don't share a security model: the control plane you use to provision resources, the per-knowledge-source credentials that vary by source kind, the connection auth between a knowledge base and the agent that calls it, and, the one people get wrong most often, whether the content itself respects th
