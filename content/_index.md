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
        text: Curriculum completo
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
      title: 'Ricerca'
      subtitle: ''
      text: |-
        Attivita di ricerca nel campo della computer vision e dei sistemi multimediali,
        con particolare attenzione a retrieval, analisi di immagini e video, e applicazioni
        per l'interazione uomo-macchina.
    design:
      columns: '1'
  - block: collection
    content:
      title: Pubblicazioni su rivista
      text: ''
      filters:
        folders:
          - publications
        publication_type: 'article-journal'
    design:
      view: citation
  - block: collection
    content:
      title: Pubblicazioni in conferenza
      text: ''
      filters:
        folders:
          - publications
        publication_type: 'paper-conference'
    design:
      view: citation
---
