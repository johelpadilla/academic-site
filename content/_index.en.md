---
title: ''
summary: ''
date: 2022-10-24
type: landing

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

  - block: stats
    id: impact
    content:
      title: ''
      text: ''
      items:
        - statistic: "20+"
          description: Publications and preprints
          icon: hero/document-text
        - statistic: "3"
          description: Open software products
          icon: hero/code-bracket
        - statistic: "2"
          description: Monographs (2026)
          icon: hero/book-open
        - statistic: "ES · EN · FR"
          description: Multilingual pedagogy
          icon: hero/language
    design:
      layout: minimal

  - block: features
    id: pillars
    content:
      title: 'Program lines'
      subtitle: ''
      text: ''
      items:
        - name: 'Systemic Tau (τ_s)'
          description: 'Ordinal observable of reorganization in complex series; relational coupling beyond univariate amplitude.'
          icon: hero/chart-bar
        - name: 'RECD'
          description: 'Discrete Extramental Clock: nested levels Φ₁–Φ₃ and intrinsic process timing.'
          icon: hero/clock
        - name: 'excess³ / Φ₃'
          description: 'Pre-specified proxy for order-3 dependence, with nulls and synthetic validation.'
          icon: hero/cube-transparent
        - name: 'Applications and teaching'
          description: 'Early warning (dengue), open software, and monographs in dialogue with philosophy of physics.'
          icon: hero/academic-cap
    design:
      layout: grid

  - block: markdown
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        Work on **Systemic Tau (τ_s)** and the **Discrete Extramental Clock (RECD)**: ordinal metrics, discrete extramental time, and models for complex systems, with applications to early warning and **excess³**. In philosophy, I continue Polo’s project with *El acto de ser relacional-discreto*. The program synthesis is *Systemic Tau and the Discrete Architecture of Time* (2nd ed., ISBN 979-8-18776-367-2).

        [Publications](publications/) · [BibTeX](uploads/BibTeX_Clean_2026.bib) · [CV](uploads/resume.pdf) · [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22)

        Contact: [joel.padilla2@upr.edu](mailto:joel.padilla2@upr.edu)
    design:
      columns: '1'

  - block: markdown
    id: software
    content:
      title: 'Software'
      subtitle: ''
      text: |-
        <div class="tau-product-grid">
          <div class="tau-product-card">
            <span class="tau-kicker">Web · teaching</span>
            <h3>Academy Learning Tau</h3>
            <p>Streamlit platform (v1.1) for τ_s, RECD, EWS, and a reproducible laboratory. ES · EN · FR.</p>
            <div class="tau-links">
              <a href="https://academylearningtau.streamlit.app">App</a>
              <a href="https://doi.org/10.5281/zenodo.21301571">DOI</a>
              <a href="https://github.com/johelpadilla/academy-learning-tau">Code</a>
            </div>
          </div>
          <div class="tau-product-card">
            <span class="tau-kicker">macOS</span>
            <h3>Systemic Tau</h3>
            <p>Desktop app for analysis, reporting, and an academic-format kernel.</p>
            <div class="tau-links">
              <a href="https://github.com/johelpadilla/systemictau/releases">Downloads</a>
              <a href="https://github.com/johelpadilla/systemictau">Code</a>
            </div>
          </div>
          <div class="tau-product-card">
            <span class="tau-kicker">Methods</span>
            <h3>excess³</h3>
            <p>Order-3 proxy: methods, Spanish introduction, and cross-disciplinary guide.</p>
            <div class="tau-links">
              <a href="https://doi.org/10.5281/zenodo.21385937">DOI</a>
              <a href="https://github.com/johelpadilla/excess3">Code</a>
            </div>
          </div>
        </div>
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: 'Featured publications'
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: 'Catalog'
      text: ''
      filters:
        folders:
          - publications
    design:
      view: citation
---
