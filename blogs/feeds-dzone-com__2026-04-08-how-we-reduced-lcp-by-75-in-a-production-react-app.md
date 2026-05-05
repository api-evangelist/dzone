---
title: "How We Reduced LCP by 75% in a Production React App"
url: "https://feeds.dzone.com/link/23564/17315828/reducing-lcp-by-75-in-a-production-react"
date: "Wed, 08 Apr 2026 13:00:04 GMT"
author: "Satyam Nikhra"
feed_url: "https://feeds.dzone.com/javascript"
---
<p>We recently launched a brand new customer-facing <a href="https://dzone.com/articles/top-8-real-life-react-apps-examples">React application</a> when we started receiving customer complaints. Pages were loading slowly and users were frustrated. Customers were churning. As we dug into our internal metrics, it became clear that things were even worse than we realized. Our app fell in the bottom five of 27 apps for our organization. Our performance metrics reflected the same story. Our LCP for the 75th percentile was 7.7 seconds. Most users were staring at a loading screen for multiple seconds before they could interact with a page. &nbsp;</p>
<h2>What is LCP (Largest Contentful Paint) ?</h2>
<p><a href="https://dzone.com/articles/5-super-fast-ways-to-improve-core-web-vitals">Largest Contentful Paint (LCP)</a> is a Core Web Vitals metric that measures how long it takes for the main content of a page to become visible to the user. By this, it signifies the time that users assume that the page has fully loaded.</p><img height="1" src="https://feeds.dzone.com/link/23564/17315828.gif" width="1" />
