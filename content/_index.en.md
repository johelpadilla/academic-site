---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV (PDF)
        url: uploads/resume.pdf
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
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I develop conceptual frameworks in Systemic Tau (τ_s) and the Discrete Extramental Clock Law (RECD). I integrate fractal dimension analysis (D ≈ 1.98), ontological permeability, and discrete models for complex systems.

        My recent publications (2026) are available on [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22). The complete BibTeX files and organized PDFs can be found in my OneDrive folder.

        [See all publications](/publications/) • [Download BibTeX](/uploads/BibTeX_Clean_2026.bib) • [Download CV (PDF)](/uploads/resume.pdf)

        Contact for collaboration: joel.padilla2@upr.edu / johelpadilla@gmail.com
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
    design:
      view: citation
---