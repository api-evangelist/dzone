---
title: "When an iOS Retry Executes an Agent Twice: Building Effectively-Once Tool Workflows With LangGraph, MCP Tasks, Kafka, and App Attest"
url: "https://dzone.com/articles/prevent-duplicate-agents"
date: "2026-09-21"
author: "Uthej Mopathi"
feed_url: "https://feeds.dzone.com/integration"
---
A mobile request can fail without the server-side work failing. An iOS app may time out, lose the response after a POST has reached the service, or retry after connectivity changes while the original execution is still progressing. Apple explicitly distinguishes safe retry behavior by HTTP method and notes that URLSession can retry requests in some connection-loss cases, waitsForConnectivity can also cause the system to continue a request when connectivity returns.
