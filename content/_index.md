---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  # ── Hero: photo + tagline + social chips ────────────────────────────────
  - block: markdown
    id: hero
    content:
      title: ''
      text: |-
        <div class="tau-hero tau-hero-split">
          <div class="tau-hero-copy">
            <p class="tau-hero-kicker">Investigación abierta · UPR</p>
            <h1 class="tau-hero-title">Systemic Tau (τ<sub>s</sub>) · RECD · excess³</h1>
            <p class="tau-hero-lede">
              Marcos ordinales para sistemas complejos, tiempo extramental discreto y dependencia de orden superior — con software abierto y monografías.
            </p>
            <div class="tau-hero-actions">
              <a class="tau-btn tau-btn-primary" href="publications/">Publicaciones</a>
              <a class="tau-btn tau-btn-ghost" href="project/">Proyectos</a>
              <a class="tau-btn tau-btn-ghost" href="software/">Software</a>
              <a class="tau-btn tau-btn-ghost" href="about/">Sobre mí</a>
            </div>
            <div class="tau-hero-socials">
              <a class="tau-social-chip" href="https://orcid.org/0000-0002-5797-6931" target="_blank" rel="noopener">ORCID</a>
              <a class="tau-social-chip" href="https://scholar.google.com/citations?user=y5sLFVkAAAAJ&amp;hl=en" target="_blank" rel="noopener">Scholar</a>
              <a class="tau-social-chip" href="https://github.com/johelpadilla" target="_blank" rel="noopener">GitHub</a>
              <a class="tau-social-chip" href="https://x.com/mrjohelpadilla" target="_blank" rel="noopener">X</a>
              <a class="tau-social-chip" href="https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22" target="_blank" rel="noopener">Zenodo</a>
              <a class="tau-social-chip" href="mailto:joel.padilla2@upr.edu">Email</a>
            </div>
          </div>
          <div class="tau-hero-photo">
            <img src="/academic-site/media/authors/me.jpg" width="220" height="220" alt="Dr. Johel Padilla-Villanueva, DrPH" class="tau-hero-avatar" loading="eager" decoding="async">
            <p class="tau-hero-photo-caption">Dr. Johel Padilla-Villanueva, DrPH</p>
          </div>
        </div>
    design:
      columns: '1'

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
      subtitle: 'Núcleo identitario'
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

  - block: collection
    id: papers
    content:
      title: 'Publicaciones destacadas'
      text: 'Fichas con portada, DOI y PDF. Catálogo completo en [Publicaciones](publications/).'
      count: 10
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
      title: 'Proyectos'
      text: 'Software, RECD, excess³ y alerta temprana en dengue.'
      count: 6
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
      subtitle: 'Herramientas abiertas del programa'
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
        <p class="tau-section-more"><a href="software/">Ver página de Software →</a></p>
    design:
      columns: '1'

  - block: resume-biography-3
    id: profile
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
          enable: false
      name:
        size: md
      avatar:
        size: small
        shape: circle

  - block: markdown
    id: contact
    content:
      title: 'Contacto'
      text: |-
        <div class="tau-contact-block">
          <p class="tau-contact-lede">Colaboraciones, docencia y consultas sobre el programa Systemic Tau / RECD.</p>
          <div class="tau-hero-socials">
            <a class="tau-social-chip" href="mailto:joel.padilla2@upr.edu">Email</a>
            <a class="tau-social-chip" href="https://orcid.org/0000-0002-5797-6931" target="_blank" rel="noopener">ORCID</a>
            <a class="tau-social-chip" href="https://scholar.google.com/citations?user=y5sLFVkAAAAJ&amp;hl=en" target="_blank" rel="noopener">Scholar</a>
            <a class="tau-social-chip" href="https://github.com/johelpadilla" target="_blank" rel="noopener">GitHub</a>
            <a class="tau-social-chip" href="https://x.com/mrjohelpadilla" target="_blank" rel="noopener">X</a>
            <a class="tau-social-chip" href="https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22" target="_blank" rel="noopener">Zenodo</a>
          </div>
          <p class="tau-section-more">
            <a href="/academic-site/about/">Sobre mí</a> ·
            <a href="/academic-site/cv/">CV</a> ·
            <a href="/academic-site/authors/me/">Perfil de autor</a>
          </p>
        </div>
    design:
      columns: '1'
---
