---
title: "How to Interpret the Number of Spring ApplicationContexts in Integration Tests"
url: "https://dzone.com/articles/spring-applicationcontext-integration-tests"
date: "2026-06-08"
author: "Constantin Kwiatkowski"
feed_url: "https://feeds.dzone.com/integration"
---
When optimizing Spring Boot integration tests, developers often focus on obvious metrics: total build time, test execution time, CPU usage, memory consumption, or the number of failed tests. These metrics are useful, but they do not always explain why an integration test suite is slow. One of the most important hidden metrics in Spring Boot integration testing is the number of distinct ApplicationContext instances created during the test run, check out my other article .
