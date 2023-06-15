---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hi! I'm William!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
      count: 0
    design:
      columns: '2'
      view: citation
---
