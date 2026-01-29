---
title: Pubblicazioni
summary: Elenco delle pubblicazioni per tipologia
type: landing

sections:
  - block: markdown
    content:
      title: ''
      text: |-
        ![Universita degli Studi di Firenze](/images/logo/Logo_Dinfo_web.png)
        ![MICC logo](/images/logo/LOGOUNIFI_DINFO_MICC_inverted.png)
        ![Small Pixels logo](/images/logo/smallpixels_logo_white.svg)
    design:
      columns: '1'
  - block: collection
    content:
      title: Articoli su rivista
      text: ''
      filters:
        folders:
          - publications
        publication_type: 'article-journal'
    design:
      view: citation
  - block: collection
    content:
      title: Atti di conferenza
      text: ''
      filters:
        folders:
          - publications
        publication_type: 'paper-conference'
    design:
      view: citation
---
