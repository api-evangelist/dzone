---
title: "The Request Timed Out, But the Payment Succeeded: Building Retry-Safe Mobile APIs"
url: "https://dzone.com/articles/retry-safe-mobile-apis"
date: "2026-09-28"
author: "Uthej Mopathi"
feed_url: "https://feeds.dzone.com/integration"
---
Mobile networks are notoriously unreliable. A common scenario is when a user taps "Pay Now" in an app: the payment request reaches the server and is processed, but the network response never reaches the phone. The client assumes the request failed and retries, leading to the charge running twice.
