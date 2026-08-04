---
title: "React 19 Killed Half My Performance Optimization Code, and I'm Grateful"
url: "https://dzone.com/articles/react-19-optimization"
date: "2026-07-22"
author: "Rohit G"
feed_url: "https://feeds.dzone.com/home"
---
I maintain a React admin dashboard codebase that had — at last count before upgrading to React 19 — 34 instances of useMemo , 28 instances of useCallback , and 19 components wrapped in memo() . I spent a nontrivial amount of time over two years adding those optimizations, debugging cases where I'd gotten the dependency arrays wrong, and explaining to junior developers why the table re-rendered on every keystroke. React 19 with the compiler deleted most of that work.
