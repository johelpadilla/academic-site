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
        Desarrollo marcos conceptuales en Systemic Tau (τ_s) y el Reloj Extramental Discreto (RECD). Integro análisis de dimensión fractal (D ≈ 1.98), permeabilidad ontológica y modelos discretos para sistemas complejos. La implementación de referencia actual es la aplicación de escritorio nativa **Systemic Tau v3.0** para macOS.

        Mis publicaciones recientes (2026) están disponibles en [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22). El BibTeX completo y los PDFs organizados se encuentran en mi carpeta de OneDrive.

        [Ver todas las publicaciones](/publications/) • [Descargar BibTeX](/uploads/BibTeX_Clean_2026.bib) • [Descargar CV (PDF)](/uploads/resume.pdf)

        Contacto para colaboración: joel.padilla2@upr.edu / johelpadilla@gmail.com
    design:
      columns: '1'
  - block: markdown
    id: software
    content:
      title: '💻 Software'
      subtitle: 'Systemic Tau v3.0 (macOS)'
      text: |-
        Implementación de referencia del paradigma **Tau Sistémico (τ_s)** y de la **Ley del Reloj Extramental Discreto (RECD)**.

        **Systemic Tau v3.0** es una aplicación de escritorio nativa y autónoma para macOS que integra pre-procesamiento avanzado, reportes deterministas rigurosos e insights impulsados por IA en una interfaz gráfica única.

        ### Características clave
        - Aplicación independiente para macOS (sin Python ni terminal)
        - Capa de salud de datos transparente (manejo de NaNs: aborto estricto, prompt manual o auto-interpolación)
        - Filtros de suavizado de señales: Media Móvil (n=3) y Savitzky-Golay (n=5)
        - Guardar reportes completos y función "Comparar con Archivo"
        - Núcleo matemático refactorizado en formato académico estricto de 7 secciones

        ### Instalación (macOS)
        1. Descarga `SystemicTau-Installer.dmg` desde los Assets en GitHub Releases.
        2. Abre el archivo .dmg.
        3. Arrastra `SystemicTau.app` a la carpeta Aplicaciones (o Escritorio).
        4. Ejecuta la app. En el primer lanzamiento: clic derecho → "Abrir" para saltar la advertencia de desarrollador no firmado.

        📖 Lee la **Guía de Inicio Rápido y Manual de Usuario** antes de tu primer análisis.

        **Enlaces:**
        - [GitHub Releases](https://github.com/johelpadilla/systemictau/releases) — Descargar la app (.dmg) y código fuente
        - [Repositorio](https://github.com/johelpadilla/systemictau)
        - [Documentación (USER_GUIDE)](https://github.com/johelpadilla/systemictau/blob/main/USER_GUIDE.md)
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
