---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: markdown
    id: hero
    content:
      title: ''
      text: |-
        <div class="tau-hero">
          <p class="tau-hero-kicker">Open research · UPR</p>
          <h1 class="tau-hero-title">Systemic Tau (τ<sub>s</sub>) · RECD · excess³</h1>
          <p class="tau-hero-lede">
            Ordinal frameworks for complex systems, discrete extramental time, and higher-order dependence — with open software and monographs.
          </p>
          <div class="tau-hero-actions">
            <a class="tau-btn tau-btn-primary" href="publications/">Publications</a>
            <a class="tau-btn tau-btn-ghost" href="project/">Projects</a>
            <a class="tau-btn tau-btn-ghost" href="#software">Software</a>
            <a class="tau-btn tau-btn-ghost" href="about/">About</a>
          </div>
        </div>
    design:
      columns: '1'

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
        size: large
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
      subtitle: 'Core identity'
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

  - block: collection
    id: papers
    content:
      title: 'Featured publications'
      text: 'DOI, PDF, and code on each card. Full catalog at [Publications](publications/).'
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: card
      columns: 2

  - block: collection
    id: projects
    content:
      title: 'Projects'
      text: ''
      filters:
        folders:
          - project
        featured_only: true
    design:
      view: card
      columns: 2

  - block: markdown
    id: software
    content:
      title: 'Software'
      subtitle: 'Open tools from the program'
      text: |-
        <div class="tau-product-grid">
          <div class="tau-product-card">
            <span class="tau-kicker">Web · teaching</span>
            <h3>Academy Learning Tau</h3>
            <p>Streamlit platform (v1.1) for τ_s, RECD, EWS, and a reproducible lab. ES · EN · FR.</p>
            <div class="tau-links">
              <a href="https://academylearningtau.streamlit.app">App</a>
              <a href="https://doi.org/10.5281/zenodo.21301571">DOI</a>
              <a href="https://github.com/johelpadilla/academy-learning-tau">Code</a>
            </div>
          </div>
          <div class="tau-product-card">
            <span class="tau-kicker">macOS</span>
            <h3>Systemic Tau</h3>
            <p>Desktop app for analysis, reporting, and an academic-format core.</p>
            <div class="tau-links">
              <a href="https://github.com/johelpadilla/systemictau/releases">Downloads</a>
              <a href="https://github.com/johelpadilla/systemictau">Code</a>
            </div>
          </div>
          <div class="tau-product-card">
            <span class="tau-kicker">Methods</span>
            <h3>excess³</h3>
            <p>Order-3 proxy: methods paper, Spanish intro, and cross-disciplinary guide.</p>
            <div class="tau-links">
              <a href="https://doi.org/10.5281/zenodo.21385937">DOI</a>
              <a href="https://github.com/johelpadilla/excess3">Code</a>
            </div>
          </div>
        </div>
    design:
      columns: '1'

  - block: collection
    content:
      title: 'Recent catalog'
      text: 'Full list at [Publications](publications/).'
      filters:
        folders:
          - publications
    design:
      view: citation

  - block: markdown
    id: contact
    content:
      title: 'Contact'
      text: |-
        **Email:** [joel.padilla2@upr.edu](mailto:joel.padilla2@upr.edu)

        **Profiles:** [ORCID](https://orcid.org/0000-0002-5797-6931) · [Google Scholar](https://scholar.google.com/citations?user=y5sLFVkAAAAJ&hl=en) · [GitHub](https://github.com/johelpadilla) · [X](https://x.com/mrjohelpadilla) · [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22)

        **More:** [About](/academic-site/en/about/) · [CV](/academic-site/cv/) · [Author profile](/academic-site/authors/me/)
    design:
      columns: '1'
---
