---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Full CV
        url: /cv/
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        Research activity in computer vision and multimedia systems, with a focus on retrieval,
        image and video analysis, and human-machine interaction.
    design:
      columns: '1'
  - block: collection
    content:
      title: Journal Publications
      text: ''
      filters:
        folders:
          - publications
        publication_type: 'article-journal'
    design:
      view: citation
  - block: collection
    content:
      title: Conference Publications
      text: ''
      filters:
        folders:
          - publications
        publication_type: 'paper-conference'
    design:
      view: citation
---
