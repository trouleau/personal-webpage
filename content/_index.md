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
      columns: '1'
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
  - block: markdown
    id: honors
    content:
      title: Honors
      text: >
        - Winner of the <a href="https://www.kit.nl/project/tuberculosis-hackathon/" itemprop="name">KIT Tuberculosis Hackathon</a> as part of the <a href="http://www.idmod.org/" itemprop="name">IDM</a> team (2019)
        
        - Teaching Assistant Award, EPFL (2019)
        
        - ACM SIGKDD Student Travel Award (2016)
        
        - EDIC Fellowship, EPFL (2015)
    design:
      columns: '2'
---
