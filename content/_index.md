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
      text: '
        Marco Bertini is Associate Professor in Computer Science at the University of Florence, Italy. He is working at the [Media Integration and Communication Center (MICC)](https://www.micc.unifi.it) at the [University of Florence](https://www.unifi.it/), where he serves as Director of the center since 2020.  

        MICC is a research and transfer center where innovative solutions for the application of computer vision, AI, multimedia and information technologies are studied, including computer vision, 3D acquisition and modeling, automatic recognition techniques, solutions for natural human-machine interaction, multimedia installations.  

        He has been involved in 10 EU research projects as WP coordinator and researcher, among which IM3I, euTV, ORUSSI, UMETECH, and more recently AI4Media and ReInHerit. He is currently P.I. of 4 national and regional technology transfer projects. He is a co-founder of [Small Pixels](https://smallpixels.ai), an academic spin-off that has developed innovative GenAI solutions for video quality improvement and enhanced video compression.
'
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
