---
title: "Refactoring a Huge Go File in Under 5 Minutes with AI and ast-grep"
url: "https://docspring.com/blog/posts/refactoring-a-huge-go-file-in-under-5-minutes-with-ai-and-ast-grep/"
date: "2025-10-09"
author: "Nathan Broadbent"
feed_url: "https://docspring.com/blog/feed/"
---
Large monolithic files are a common problem in software projects, especially when AI agents are involved. These files are hard to navigate, difficult to review in pull requests, and violate the single responsibility principle. We had a monster in one of our greenfield projects: internal/gateway/handlers/admin.go .
