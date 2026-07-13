---
title: "Working with the new Idempotency Keys RFC"
url: "https://httptoolkit.com/blog/idempotency-keys/"
date: "2023-12-12"
feed_url: "https://httptoolkit.com/rss.xml"
---
Idempotency is when doing an operation multiple times is guaranteed to have the same effect as doing it just once. When working with APIs this is exceptionally helpful on slow or unreliable internet connections, or when dealing with particularly sensitive actions such as payments, because it makes retrying operations safe and reliable. This is why most payment gateways like Stripe and Adyen support 'idempotency keys' as a key feature of their APIs.
