---
title: "Removing Random \restrict Lines from PostgreSQL Structure Dumps"
url: "https://docspring.com/blog/posts/removing-random-restrict-lines-from-postgresql-structure-dumps/"
date: "2025-10-09"
author: "Nathan Broadbent"
feed_url: "https://docspring.com/blog/feed/"
---
When upgrading to a newer version of PostgreSQL, I started noticing random merge conflicts in db/structure.sql whenever I ran rails db:migrate . This happens in any Ruby on Rails app that uses SQL schema format instead of the default Ruby-based schema. The culprit?
