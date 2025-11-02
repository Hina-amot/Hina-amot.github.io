---
# Homepage configuration
title: ""
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: A showcase of my analytical and business projects
      filters:
        folders:
          - project     # This will display content from content/project/
        exclude_featured: false
    design:
      columns: '3'
      view: compact

- block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: A showcase of my analytical and business projects
      filters:
        folders:
          - project     # This will display content from content/project/
        exclude_featured: false
    design:
      columns: '3'
      view: masonry
---
