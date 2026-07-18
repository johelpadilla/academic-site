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
      title: 'Programa de investigación'
      text: 'Métricas abiertas del corpus 2022–2026'
      items:
        - statistic: "20+"
          description: Publicaciones y preprints en Zenodo / sitio
          sub_metric: Acceso abierto · DOIs citables
          icon: hero/document-text
        - statistic: "3"
          description: Productos de software abiertos
          sub_metric: Academy · Systemic Tau · excess³
          icon: hero/code-bracket
        - statistic: "2"
          description: Monografías de síntesis 2026
          sub_metric: Tau 2.ª ed. · Acto de ser
          icon: hero/book-open
        - statistic: "ES · EN · FR"
          description: Pedagogía multilingüe
          sub_metric: Academy Learning Tau
          icon: hero/language
    design:
      layout: cards

  - block: features
    id: pillars
    content:
      title: 'Pilares del programa'
      subtitle: 'Teoría · software · docencia · filosofía'
      text: 'Un mismo hilo: tiempo extramental, métricas ordinales y ciencia abierta.'
      items:
        - name: 'Systemic Tau (τ_s)'
          description: 'Observable ordinal de reorganización en series complejas; acoplamiento relacional más allá de la amplitud univariada.'
          icon: hero/chart-bar
        - name: 'RECD'
          description: 'Reloj extramental discreto: niveles anidados Φ₁–Φ₃, conjunciones y relojería intrínseca del proceso.'
          icon: hero/clock
        - name: 'excess³ / Φ₃'
          description: 'Proxy preespecificado de *synergistic surplus* de orden 3, con nulos y validación sintética.'
          icon: hero/cube-transparent
        - name: 'Alerta temprana'
          description: 'Aplicaciones a dengue y fenómenos de salud pública con lectura dual (τ_s + EWS clásicos).'
          icon: hero/shield-check
        - name: 'Software abierto'
          description: 'Academy Learning Tau (web), Systemic Tau (macOS) y repositorios citables con DOI.'
          icon: hero/command-line
        - name: 'Filosofía poliana'
          description: 'Acto de ser relacional-discreto: persistir, physis y vacío en continuidad con Leonardo Polo.'
          icon: hero/academic-cap
    design:
      layout: bento

  - block: markdown
    id: research
    content:
      title: 'Investigación'
      subtitle: 'Marcos, síntesis y acceso abierto'
      text: |-
        Desarrollo marcos conceptuales en **Systemic Tau (τ_s)** y el **Reloj Extramental Discreto (RECD)**. Integro dimensión fractal (D ≈ 1.98), permeabilidad ontológica, métricas ordinales y modelos discretos para sistemas complejos — con aplicaciones a alerta temprana (dengue) y a proxies de dependencia de orden superior (**excess³**).

        En filosofía, continúo el proyecto poliano con *El acto de ser relacional-discreto*. La síntesis de programa está en *Systemic Tau and the Discrete Architecture of Time* (2.ª ed., ISBN 979-8-18776-367-2).

        [Publicaciones](publications/) · [BibTeX](uploads/BibTeX_Clean_2026.bib) · [CV (PDF)](uploads/resume.pdf) · [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22)

        **Colaboración:** [joel.padilla2@upr.edu](mailto:joel.padilla2@upr.edu) · [johelpadilla@gmail.com](mailto:johelpadilla@gmail.com)
    design:
      columns: '1'

  - block: markdown
    id: software
    content:
      title: 'Software'
      subtitle: 'Implementaciones abiertas del paradigma'
      text: |-
        <div class="tau-product-grid">
          <div class="tau-product-card">
            <span class="tau-kicker">Educación · Web</span>
            <h3>Academy Learning Tau v1.1</h3>
            <p>Plataforma Streamlit de docencia e investigación exploratoria: τ_s, RECD, EWS, surrogados, evaluaciones y biblioteca. ES · EN · FR.</p>
            <div class="tau-links">
              <a href="https://academylearningtau.streamlit.app">App en vivo</a>
              <a href="https://doi.org/10.5281/zenodo.21301571">DOI</a>
              <a href="https://github.com/johelpadilla/academy-learning-tau">GitHub</a>
            </div>
          </div>
          <div class="tau-product-card">
            <span class="tau-kicker">Escritorio · macOS</span>
            <h3>Systemic Tau</h3>
            <p>Aplicación nativa para análisis, salud de datos, suavizado, reportes deterministas y núcleo en formato académico.</p>
            <div class="tau-links">
              <a href="https://github.com/johelpadilla/systemictau/releases">Releases</a>
              <a href="https://github.com/johelpadilla/systemictau">Repositorio</a>
              <a href="https://github.com/johelpadilla/systemictau/blob/main/USER_GUIDE.md">Guía</a>
            </div>
          </div>
          <div class="tau-product-card">
            <span class="tau-kicker">Métodos · Zenodo</span>
            <h3>excess³</h3>
            <p>Proxy continuo de dependencia de orden 3: métodos, intro en español y guía interdisciplinaria, con validación sintética.</p>
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
      title: 'Destacadas'
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: 'Catálogo de publicaciones'
      text: 'Listado completo en formato de citación.'
      filters:
        folders:
          - publications
    design:
      view: citation
---
