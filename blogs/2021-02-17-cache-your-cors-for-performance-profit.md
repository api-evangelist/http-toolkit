---
title: "Cache your CORS, for performance & profit"
url: "https://httptoolkit.com/blog/cache-your-cors/"
date: "2021-02-17"
feed_url: "https://httptoolkit.com/rss.xml"
---
CORS is a necessity for many APIs, but basic configurations can create a huge number of extra requests, slowing down every browser API client, and sending unnecessary traffic to your backend. This can be a problem with a traditional API, but becomes a much larger issue with serverless platforms, where your billing is often directly tied to the number of requests received, so this can easily double your API costs. All of this is unnecessary: it's happening because you don't know how caching works for CORS requests.
