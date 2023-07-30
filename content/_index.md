---
# Leave the homepage title empty to use the site title
title: Nuo CHEN 陳諾
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: "I am a PhD student at Waseda University under the supervision of Professor [Tetsuya Sakai](http://sakailab.com/tetsuya/). My research interests include information retrieval, data mining and recommender systems. My email: pleviumtan[AT]toki.waseda.jp"
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  
---
