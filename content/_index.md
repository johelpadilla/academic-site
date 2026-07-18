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
        size: medium
        shape: circle

  - block: stats
    id: impact
    content:
      title: ''
      text: ''
      items:
        - statistic: "20+"
          description: Publicaciones y preprints
          icon: hero/document-text
        - statistic: "3"
          description: Software abierto
          icon: hero/code-bracket
        - statistic: "2"
          description: Monografías 2026
          icon: hero/book-open
        - statistic: "ES · EN · FR"
          description: Pedagogía multilingüe
          icon: hero/language
    design:
      layout: minimal

  - block: features
    id: pillars
    content:
      title: 'Líneas del programa'
      subtitle: ''
      text: ''
      items:
        - name: 'Systemic Tau (τ_s)'
          description: 'Observable ordinal de reorganización en series complejas; acoplamiento relacional más allá de la amplitud univariada.'
          icon: hero/chart-bar
        - name: 'RECD'
          description: 'Reloj extramental discreto: niveles anidados Φ₁–Φ₃ y relojería intrínseca del proceso.'
          icon: hero/clock
        - name: 'excess³ / Φ₃'
          description: 'Proxy preespecificado de dependencia de orden 3, con nulos y validación sintética.'
          icon: hero/cube-transparent
        - name: 'Aplicaciones y docencia'
          description: 'Alerta temprana (dengue), software abierto y monografías en diálogo con la física filosófica.'
          icon: hero/academic-cap
    design:
      layout: grid

  - block: markdown
    id: research
    content:
      title: 'Investigación'
      subtitle: ''
      text: |-
        Trabajo en **Systemic Tau (τ_s)** y el **Reloj Extramental Discreto (RECD)**: métricas ordinales, tiempo extramental discreto y modelos para sistemas complejos, con aplicaciones a alerta temprana y a **excess³**. En filosofía, continúo el proyecto poliano con *El acto de ser relacional-discreto*. La síntesis de programa está en *Systemic Tau and the Discrete Architecture of Time* (2.ª ed., ISBN 979-8-18776-367-2).

        [Publicaciones](publications/) · [BibTeX](uploads/BibTeX_Clean_2026.bib) · [CV](uploads/resume.pdf) · [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22)

        Contacto: [joel.padilla2@upr.edu](mailto:joel.padilla2@upr.edu)
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
            <span class="tau-kicker">Web · docencia</span>
            <h3>Academy Learning Tau</h3>
            <p>Plataforma Streamlit (v1.1) para τ_s, RECD, EWS y laboratorio reproducible. ES · EN · FR.</p>
            <div class="tau-links">
              <a href="https://academylearningtau.streamlit.app">App</a>
              <a href="https://doi.org/10.5281/zenodo.21301571">DOI</a>
              <a href="https://github.com/johelpadilla/academy-learning-tau">Código</a>
            </div>
          </div>
          <div class="tau-product-card">
            <span class="tau-kicker">macOS</span>
            <h3>Systemic Tau</h3>
            <p>Aplicación de escritorio para análisis, reportes y núcleo en formato académico.</p>
            <div class="tau-links">
              <a href="https://github.com/johelpadilla/systemictau/releases">Descargas</a>
              <a href="https://github.com/johelpadilla/systemictau">Código</a>
            </div>
          </div>
          <div class="tau-product-card">
            <span class="tau-kicker">Métodos</span>
            <h3>excess³</h3>
            <p>Proxy de orden 3: métodos, intro en español y guía interdisciplinaria.</p>
            <div class="tau-links">
              <a href="https://doi.org/10.5281/zenodo.21385937">DOI</a>
              <a href="https://github.com/johelpadilla/excess3">Código</a>
            </div>
          </div>
        </div>
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: 'Publicaciones destacadas'
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: 'Catálogo'
      text: ''
      filters:
        folders:
          - publications
    design:
      view: citation
---
