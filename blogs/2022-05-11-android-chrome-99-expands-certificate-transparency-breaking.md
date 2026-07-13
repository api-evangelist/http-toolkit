---
title: "Android Chrome 99 expands Certificate Transparency, breaking all MitM dev tools"
url: "https://httptoolkit.com/blog/chrome-android-certificate-transparency/"
date: "2022-05-11"
feed_url: "https://httptoolkit.com/rss.xml"
---
Certificate transparency is superb improvement to HTTPS certificate security on the web that's great for users and businesses, but on Android it creates a huge problem for the many developer tools like HTTP Toolkit which install trusted system certificates into Android to intercept & debug app traffic. This doesn't appear in the main announcements anywhere, but buried deep in the enterprise release notes for Chrome v99 there's a small note that says: Certificate transparency is already enforced on desktop platforms, and for some Android users. Chrome 99 expands certificate transparency to all 
