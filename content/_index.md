---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: pub
    content:
      title: Publications
      text: |-
      count: 5
      filters:
        folders:
          - publication
        exclude_featured: true
      offset: 0
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: tjw@henu.edu.cn
      directions: John M. Keynes, 1-11, 08034, Barcelona.
    design:
      columns: '2'
---
