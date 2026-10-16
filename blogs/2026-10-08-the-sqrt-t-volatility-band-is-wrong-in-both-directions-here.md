---
title: "The Sqrt(t) Volatility Band Is Wrong in Both Directions; Here's What to Compute Instead"
url: "https://dzone.com/articles/address-sqrtt-volatility-band"
date: "2026-10-08"
author: "Alex Malinowski"
feed_url: "https://feeds.dzone.com/home"
---
If you have ever drawn a forecast band around a price series, you have probably reached for the same formula everyone reaches for: take a volatility estimate, multiply by the square root of the horizon, and call the result your interval. sigma * sqrt(t) is the closed-form move; it is one line of code, and for fat-tailed financial series it is wrong in a way that is worth understanding precisely, because the error does not even keep the same sign as you change the horizon. This is a short engineering write-up on what breaks, how we measured it, and the handful of things you actually have to com
