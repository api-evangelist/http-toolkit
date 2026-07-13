---
title: "How do you know what's gone wrong when your API request fails?"
url: "https://httptoolkit.com/blog/http-api-problem-details/"
date: "2020-11-24"
feed_url: "https://httptoolkit.com/rss.xml"
---
When an API request doesn't work, hopefully the client receives a sensible HTTP error status, like 409 or 500, which is a good start. Unfortunately though, whilst 400 Bad Request might be enough to know who's at fault, it's rarely enough information to understand or fix the actual problem. Many APIs will give you more details in the response body, but sadly each with their own custom style, varying between APIs or even between individual endpoints, requiring custom logic or human intervention to understand.
