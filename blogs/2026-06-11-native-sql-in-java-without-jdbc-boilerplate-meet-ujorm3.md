---
title: "Native SQL in Java Without JDBC Boilerplate — Meet Ujorm3"
url: "https://dzone.com/articles/ujorm3-native-sql-java"
date: "2026-06-11"
author: "Pavel Ponec"
feed_url: "https://feeds.dzone.com/home"
---
If you've ever written raw JDBC, you know what's coming. Open a connection, create a PreparedStatement , set parameters by index (hope you counted right), iterate a ResultSet , close everything in a finally block, declare SQLException on every method signature… It's a lot of ceremony for "give me some rows." I've been experimenting with Ujorm3 , a new lightweight ORM library for Java 17+. Here's a realistic example — a JOIN query that maps results including a nested relation:
