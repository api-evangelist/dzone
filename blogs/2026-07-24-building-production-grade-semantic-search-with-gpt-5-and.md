---
title: "Building Production-Grade Semantic Search With GPT-5 and Microsoft Foundry, From Scratch"
url: "https://dzone.com/articles/production-semantic-search-gpt5-foundry"
date: "2026-07-24"
author: "Jubin Abhishek Soni"
feed_url: "https://feeds.dzone.com/home"
---
Most "RAG tutorials" stop at a single embedding query against a single index. That works for a demo and falls over the moment a real user asks something like "compare our Q3 and Q4 vendor contracts and flag anything that changed" — a question that needs multiple sub-queries, reasoning about what's still missing, and synthesis across documents. Microsoft Foundry's answer to this is Foundry IQ : an agentic retrieval layer built on Azure AI Search that treats retrieval as a reasoning task rather than a single keyword or vector lookup.
