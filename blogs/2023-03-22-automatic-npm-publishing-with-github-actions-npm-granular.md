---
title: "Automatic npm publishing, with GitHub Actions & npm granular tokens"
url: "https://httptoolkit.com/blog/automatic-npm-publish-gha/"
date: "2023-03-22"
feed_url: "https://httptoolkit.com/rss.xml"
---
This week, at long last, GitHub announced granular access tokens for npm . This is a big deal! It's great for security generally, but also particularly useful if you maintain any npm packages, as it removes the main downside of automating npm publishing, by allowing you to give CI jobs only a very limited token instead of full 2FA-free access to your account.
