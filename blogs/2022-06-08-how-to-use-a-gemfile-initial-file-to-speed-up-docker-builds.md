---
title: "How to use a Gemfile.initial file to speed up Docker builds with an extra cached layer"
url: "https://docspring.com/blog/posts/use-a-gemfile-initial-file-to-speed-up-docker-builds/"
date: "2022-06-08"
author: "Nathan Broadbent"
feed_url: "https://docspring.com/blog/feed/"
---
We recently wrote a blog post about a script that updates version strings in a Dockerfile . We've since identified a better way to achieve the same goals. A Rails application will have gem dependencies listed in files called Gemfile and a Gemfile.lock .
