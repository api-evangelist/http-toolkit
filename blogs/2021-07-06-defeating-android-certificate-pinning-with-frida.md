---
title: "Defeating Android Certificate Pinning with Frida"
url: "https://httptoolkit.com/blog/frida-certificate-pinning/"
date: "2021-07-06"
feed_url: "https://httptoolkit.com/rss.xml"
---
Some Android apps go to astounding lengths to ensure that even the owner of a device can never see the content of the app's HTTPS requests. This is problematic for security research, privacy analysis and debugging, and for control over your own device in general. It's not a purely theoretical problem either - protections like this attempt to directly block HTTPS inspection tools like HTTP Toolkit , which allow you to automatically intercept HTTPS from Android devices for inspection, testing & mocking, like so: This depends on the target application(s) trusting the debugging proxy's certificate
