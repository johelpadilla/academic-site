---
title: 'About'
date: 2026-07-17
type: landing
summary: 'Academic profile, research lines, and contact.'
aliases:
  - /en/about/

design:
  spacing: '3rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV (PDF)
        url: uploads/resume.pdf
      headings:
        about: 'Profile'
        education: 'Education'
        interests: 'Research lines'
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
        size: medium
        shape: circle

  - block: markdown
    id: about-detail
    content:
      title: 'Research program'
      text: |-
        Work centers on **Systemic Tau (τ_s)** and the **Discrete Extramental Clock (RECD)**: multivariate ordinal metrics, discrete extramental time, and higher-order dependence (**excess³ / Φ₃**), with applications to early warning (dengue) and open software.

        In philosophy of physics, I continue Polo’s project with *El acto de ser relacional-discreto*. The program synthesis is *Systemic Tau and the Discrete Architecture of Time* (2nd ed., ISBN 979-8-18776-367-2).

        ### Quick links
        - [Author profile](../authors/me/) · [Publications](../publications/) · [Projects](../project/)
        - [ORCID](https://orcid.org/0000-0002-5797-6931) · [Google Scholar](https://scholar.google.com/citations?user=y5sLFVkAAAAJ&hl=en) · [GitHub](https://github.com/johelpadilla)
        - [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22) · [BibTeX](../uploads/BibTeX_Clean_2026.bib) · [CV PDF](../uploads/resume.pdf)
        - Contact: [joel.padilla2@upr.edu](mailto:joel.padilla2@upr.edu)
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
      title: Languages
      username: me
---
