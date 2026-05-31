# =============================================
#   M4sterC4t — GitHub Pages Configuration
# =============================================

theme: minima

# Site Identity
title: "M4sterC4t"
tagline: "Mastering the craft, one commit at a time."
description: >-
  Portfolio of M4sterC4t — Informatics Engineering student,
  AI & automation enthusiast, and aspiring developer from Jakarta, Indonesia.
author: "M4sterC4t"
email: ""

# Social Links (uncomment & fill if needed)
# twitter_username: m4sterc4t
github_username: M4sterC4t
# linkedin_username: yourname

# URL Settings
url: "https://m4sterc4t.github.io"
baseurl: "/skills-github-pages"

# Build Settings
markdown: kramdown
highlighter: rouge
permalink: pretty

# Minima Theme Settings
minima:
  skin: dark  # options: classic | dark | solarized | solarized-dark

# Plugins
plugins:
  - jekyll-feed
  - jekyll-seo-tag

# Exclude from build
exclude:
  - README.md
  - Gemfile
  - Gemfile.lock
  - node_modules
