---
title: "Designing Rayfall: One Expression Language for a Columnar Database"
url: "https://dzone.com/articles/rayfall-columnar-database-expression-language"
date: "2026-08-25"
author: "Anton Kundenko"
feed_url: "https://feeds.dzone.com/home"
---
Columnar engines naturally organize computation around vectors to make effective use of single instruction, multiple data (SIMD) instructions. This makes vectors first-class citizens in such engines. The difficult design question appears when an engine's internal application programming interface (API) must be exposed to users: where should programming happen?
