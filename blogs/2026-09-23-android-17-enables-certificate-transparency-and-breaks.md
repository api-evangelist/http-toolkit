---
title: "Android 17 enables certificate transparency, and breaks custom CAs"
url: "https://httptoolkit.com/blog/android-17-certificate-transparency/"
date: "2026-09-23"
feed_url: "https://httptoolkit.com/rss.xml"
---
Do you want to know what your phone is sending & receiving? Nowadays, that means you need to control who it trusts. In modern connections everything sent & received is encrypted by TLS, and the only practical way to intercept traffic on Android is to generate a certificate, make the phone or app trust it as a certificate authority (CA), and then use this to act as a fully trusted proxy to the real server.
