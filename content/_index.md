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
      title: '📚 Mi Investigación'
      subtitle: ''
      text: |-
        Desarrollo marcos conceptuales en Systemic Tau (τ_s) y el Reloj Extramental Discreto (RECD). Integro análisis de dimensión fractal (D ≈ 1.98), permeabilidad ontológica y modelos discretos para sistemas complejos. La implementación de referencia está disponible como el paquete Python `systemictau` v2.0.1.

        Mis publicaciones recientes (2026) están disponibles en [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22). El BibTeX completo y los PDFs organizados se encuentran en mi carpeta de OneDrive.

        [Ver todas las publicaciones](/publications/) • [Descargar BibTeX](/uploads/BibTeX_Clean_2026.bib) • [Descargar CV (PDF)](/uploads/resume.pdf)

        Contacto para colaboración: joel.padilla2@upr.edu / johelpadilla@gmail.com
    design:
      columns: '1'
  - block: markdown
    id: software
    content:
      title: '💻 Software'
      subtitle: 'systemictau v2.0.1'
      text: |-
        Implementación de referencia del paradigma **Tau Sistémico (τ_s)** y de la **Ley del Reloj Extramental Discreto (RECD)**.

        El paquete Python de código abierto **`systemictau`** (v2.0.1) proporciona las herramientas computacionales para simular, analizar y visualizar estos marcos teóricos.

        **Instalación:**
        ```bash
        pip install systemictau
        ```

        **Enlaces:**
        - [GitHub](https://github.com/johelpadilla/systemictau) — Código fuente, documentación y ejemplos
        - [PyPI](https://pypi.org/project/systemictau/) — Versión 2.0.1
        - [Zenodo](https://doi.org/10.5281/zenodo.20902148) — DOI permanente para citación

        Diseñado para investigación reproducible en sistemas complejos, dinámica no lineal y aplicaciones científicas.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publicaciones Destacadas
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Publicaciones
      text: ''
      filters:
        folders:
          - publications
    design:
      view: citation
---
