---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
type: landing

design:
  # Default section spacing
  spacing: '0.2rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: |-
        Hi ! I'm Marco Bertini and I'm Associate Professor in Computer Science at the University of Florence (Italy), with over 25 of experience in 
        computer vision, multimedia analysis, indexing, and retrieval, contributing to advancements in multimedia research and EU-funded projects.
        I'm working at the [Media Integration and Communication Center (MICC)](https://www.micc.unifi.it) at the [University of Florence](https://www.unifi.it/), 
        where I serve as Director of the center since 2020.

        MICC is a research and transfer center where we research innovative solutions for the application of computer vision, AI, multimedia 
        and information technologies, including computer vision, 3D acquisition and modeling, automatic recognition techniques, 
        solutions for natural human-machine interaction, multimedia installations.
        
        I've been involved in 10 EU research projects among which IM3I, euTV, ORUSSI, UMETECH, and more recently [AI4Media](https://www.ai4media.eu) 
        and [ReInHerit](https://www.reinherit.eu), in different roles. 
        I'm currently P.I. of 4 national and regional technology transfer projects. 
        
        I'm also a co-founder of [Small Pixels](https://smallpixels.ai), an academic spin-off that has developed innovative GenAI solutions 
        for video quality improvement and enhanced video compression.
        As co-founder of Small Pixels, I contribute to cutting-edge technology designed to improve video quality and reduce streaming 
        costs using deep neural networks. Over the past five years, we have focused on helping users experience high-quality visuals 
        from compressed video streams, revolutionizing video quality enhancement.
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
      title: 'Research interests'
      subtitle: ''
      text: |-
        Research activity in computer vision and multimedia systems, with a focus on retrieval,
        image and video analysis, coding and quality assessment, and human-machine interaction.
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
  - block: markdown
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        {{< contact_addresses username="me" >}}
    design:
      columns: '1'
---
