---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: collection
    id: Postings
    content:
      title: My Postings
      filters:
        folders:
          - posts
    design:
      view: article-grid
      columns: 3
---
