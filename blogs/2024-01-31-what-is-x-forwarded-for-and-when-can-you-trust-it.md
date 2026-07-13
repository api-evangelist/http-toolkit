---
title: "What is X-Forwarded-For and when can you trust it?"
url: "https://httptoolkit.com/blog/what-is-x-forwarded-for/"
date: "2024-01-31"
feed_url: "https://httptoolkit.com/rss.xml"
---
The X-Forwarded-For (XFF) HTTP header provides crucial insight into the origin of web requests. The header works as a mechanism for conveying the original source IP addresses of clients, and not just across one hop, but through chains of multiple intermediaries. This list of IPv4 and IPv6 addresses is helpful to understand where requests have really come from in scenarios where they traverse several servers, proxies, or load balancers.
