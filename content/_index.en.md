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
          animation: pulse
          intensity: medium
          orb_count: 3
          colors:
            - "primary-500/25"
            - "secondary-500/20"
            - "primary-400/15"
      name:
        size: lg
      avatar:
        size: large
        shape: circle

  - block: stats
    id: impact
    content:
      title: 'Research program'
      text: 'Open metrics from the 2022–2026 corpus'
      items:
        - statistic: "20+"
          description: Publications and preprints on Zenodo / site
          sub_metric: Open access · citable DOIs
          icon: hero/document-text
        - statistic: "3"
          description: Open software products
          sub_metric: Academy · Systemic Tau · excess³
          icon: hero/code-bracket
        - statistic: "2"
          description: Synthesis monographs (2026)
          sub_metric: Tau 2nd ed. · Act of being
          icon: hero/book-open
        - statistic: "ES · EN · FR"
          description: Multilingual pedagogy
          sub_metric: Academy Learning Tau
          icon: hero/language
    design:
      layout: cards

  - block: features
    id: pillars
    content:
      title: 'Program pillars'
      subtitle: 'Theory · software · teaching · philosophy'
      text: 'One thread: extramental time, ordinal metrics, and open science.'
      items:
        - name: 'Systemic Tau (τ_s)'
          description: 'Ordinal observable of reorganization in complex series; relational coupling beyond univariate amplitude.'
          icon: hero/chart-bar
        - name: 'RECD'
          description: 'Discrete Extramental Clock: nested levels Φ₁–Φ₃, conjunctions, and intrinsic process timing.'
          icon: hero/clock
        - name: 'excess³ / Φ₃'
          description: 'Pre-specified proxy for order-3 synergistic surplus, with nulls and synthetic validation.'
          icon: hero/cube-transparent
        - name: 'Early warning'
          description: 'Applications to dengue and public-health phenomena with dual reading (τ_s + classical EWS).'
          icon: hero/shield-check
        - name: 'Open software'
          description: 'Academy Learning Tau (web), Systemic Tau (macOS), and citable repositories with DOI.'
          icon: hero/command-line
        - name: 'Polian philosophy'
          description: 'Relational-discrete act of being: persisting, physis, and void in continuity with Leonardo Polo.'
          icon: hero/academic-cap
    design:
      layout: bento

  - block: markdown
    id: research
    content:
      title: 'Research'
      subtitle: 'Frameworks, synthesis, and open access'
      text: |-
        I develop conceptual frameworks in **Systemic Tau (τ_s)** and the **Discrete Extramental Clock (RECD)**. I integrate fractal dimension (D ≈ 1.98), ontological permeability, ordinal metrics, and discrete models for complex systems — with applications to early warning (dengue) and higher-order dependence proxies (**excess³**).

        In philosophy, I continue Polo’s project with *El acto de ser relacional-discreto*. The program synthesis is *Systemic Tau and the Discrete Architecture of Time* (2nd ed., ISBN 979-8-18776-367-2).

        [Publications](publications/) · [BibTeX](uploads/BibTeX_Clean_2026.bib) · [CV (PDF)](uploads/resume.pdf) · [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22)

        **Collaboration:** [joel.padilla2@upr.edu](mailto:joel.padilla2@upr.edu) · [johelpadilla@gmail.com](mailto:johelpadilla@gmail.com)
    design:
      columns: '1'

  - block: markdown
    id: software
    content:
      title: 'Software'
      subtitle: 'Open implementations of the paradigm'
      text: |-
        <div class="tau-product-grid">
          <div class="tau-product-card">
            <span class="tau-kicker">Education · Web</span>
            <h3>Academy Learning Tau v1.1</h3>
            <p>Streamlit platform for teaching and exploratory research: τ_s, RECD, EWS, surrogates, assessments, and library. ES · EN · FR.</p>
            <div class="tau-links">
              <a href="https://academylearningtau.streamlit.app">Live app</a>
              <a href="https://doi.org/10.5281/zenodo.21301571">DOI</a>
              <a href="https://github.com/johelpadilla/academy-learning-tau">GitHub</a>
            </div>
          </div>
          <div class="tau-product-card">
            <span class="tau-kicker">Desktop · macOS</span>
            <h3>Systemic Tau</h3>
            <p>Native app for analysis, data-health layer, smoothing, deterministic reports, and academic-format kernel.</p>
            <div class="tau-links">
              <a href="https://github.com/johelpadilla/systemictau/releases">Releases</a>
              <a href="https://github.com/johelpadilla/systemictau">Repository</a>
              <a href="https://github.com/johelpadilla/systemictau/blob/main/USER_GUIDE.md">Guide</a>
            </div>
          </div>
          <div class="tau-product-card">
            <span class="tau-kicker">Methods · Zenodo</span>
            <h3>excess³</h3>
            <p>Continuous proxy for order-3 dependence: methods, Spanish intro, and cross-disciplinary guide with synthetic validation.</p>
            <div class="tau-links">
              <a href="https://doi.org/10.5281/zenodo.21385937">DOI</a>
              <a href="https://github.com/johelpadilla/excess3">GitHub</a>
            </div>
          </div>
        </div>
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: 'Featured'
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: 'Publication catalog'
      text: 'Full list in citation format.'
      filters:
        folders:
          - publications
    design:
      view: citation
---
