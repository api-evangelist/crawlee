---
title: "Building a Gradcracker scraper with Crawlee: anti-bot failures and redirect bugs"
url: "https://crawlee.dev/blog/building-gradcracker-scraper-with-crawlee"
date: "2026-06-15"
author: "Shaheer Sarfaraz"
feed_url: "https://crawlee.dev/blog/rss.xml"
---
A real-world case study of building a web scraper for Gradcracker, a UK graduate job board, using Crawlee while grappling with bot detection, unstable redirect chains, and production tradeoffs. The author implements Camoufox for anti-detection evasion, manages concurrency constraints, and solves a redirect problem via polling-based URL stabilization rather than conventional navigation events, concluding that most obstacles came from the target site rather than Crawlee itself.
