---
title: "22 years later, YAML now has a media type"
url: "https://httptoolkit.com/blog/yaml-media-type-rfc/"
date: "2024-02-20"
feed_url: "https://httptoolkit.com/rss.xml"
---
As of February 14th 2024, RFC 9512 formally registers application/yaml as the media type for all YAML content, and adds +yaml as a standard structured suffix for all YAML-based more specific media types. With this registration, it's now included in the official media types list maintained by the IANA. Media types like this (also known as the MIME types, from their original invention for email attachment metadata) are heavily used particularly in HTTP Content-Type headers for both requests & responses, and in all sorts of file metadata and processing logic elsewhere.
