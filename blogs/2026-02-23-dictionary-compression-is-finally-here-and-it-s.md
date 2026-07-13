---
title: "Dictionary Compression is finally here, and it's ridiculously good"
url: "https://httptoolkit.com/blog/dictionary-compression-performance-zstd-brotli/"
date: "2026-02-23"
feed_url: "https://httptoolkit.com/rss.xml"
---
Dictionary compression could completely change how applications send data over the web. It's recently gained broad support, and offers absurd real-world traffic reductions: initial testing shows YouTube JS download size for returning desktop users shrinking up to 90% (!!!) compared to existing best-practice compression, while the Google search results HTML (arguably the most optimized content on the internet) shrinks nearly 50% . This works by initializing the (de)compression algorithm with a dictionary of data known in advance to both compressor & decompressor, so that the compressed data can
