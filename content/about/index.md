---
title: 'Sobre mí · About'
date: 2026-07-17
type: landing
summary: 'Perfil académico, líneas de investigación y contacto.'
aliases:
  - /about/
  - /sobre/
  - /perfil/

design:
  spacing: '3rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Descargar CV (PDF)
        url: uploads/resume.pdf
      headings:
        about: 'Perfil'
        education: 'Formación'
        interests: 'Líneas de trabajo'
    design:
      background:
        gradient_mesh:
          enable: true
          style: orbs
          animation: none
          intensity: subtle
          orb_count: 2
          colors:
            - "primary-500/10"
            - "secondary-500/8"
      name:
        size: md
      avatar:
        size: large
        shape: circle

  - block: markdown
    id: about-detail
    content:
      title: 'Programa de investigación'
      text: |-
        El trabajo se organiza en torno a **Systemic Tau (τ_s)** y el **Reloj Extramental Discreto (RECD)**: métricas ordinales multivariadas, tiempo extramental discreto y dependencia de orden superior (**excess³ / Φ₃**), con aplicaciones a alerta temprana (dengue) y software abierto.

        En filosofía de la física, continúo el proyecto poliano con *El acto de ser relacional-discreto*. La síntesis de programa está en *Systemic Tau and the Discrete Architecture of Time* (2.ª ed., ISBN 979-8-18776-367-2).

        ### Enlaces rápidos
        - [Perfil de autor](/academic-site/authors/me/) · [Publicaciones](/academic-site/publications/) · [Proyectos](/academic-site/project/)
        - [ORCID](https://orcid.org/0000-0002-5797-6931) · [Google Scholar](https://scholar.google.com/citations?user=y5sLFVkAAAAJ&hl=en) · [GitHub](https://github.com/johelpadilla)
        - [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22) · [BibTeX](/academic-site/uploads/BibTeX_Clean_2026.bib) · [CV PDF](/academic-site/uploads/resume.pdf)
        - Contacto: [joel.padilla2@upr.edu](mailto:joel.padilla2@upr.edu)
    design:
      columns: '1'

  - block: resume-experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: false

  - block: resume-skills
    content:
      title: Skills
      username: me

  - block: resume-languages
    content:
      title: Idiomas · Languages
      username: me
---
