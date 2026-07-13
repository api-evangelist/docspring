---
title: "Automatically update Docker gem versions from Gemfile.lock"
url: "https://docspring.com/blog/posts/update-docker-gem-versions-from-gemfile-lock/"
date: "2022-06-07"
author: "Nathan Broadbent"
feed_url: "https://docspring.com/blog/feed/"
---
UPDATE: We've come up with a potentially better way to achieve the same goal, by using a new Gemfile.initial file. See the new post here. I wrote a small script that can sync _VERSION environment variables in a Dockerfile with versions from Gemfile.lock
