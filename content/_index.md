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
        Desarrollo marcos conceptuales en Systemic Tau (τ_s) y el Reloj Extramental Discreto (RECD). Integro análisis de dimensión fractal (D ≈ 1.98), permeabilidad ontológica, métricas ordinales y modelos discretos para sistemas complejos, con aplicaciones a alerta temprana (dengue) y a proxies de dependencia de orden superior (excess³).

        El software abierto del programa incluye la plataforma educativa **[Academy Learning Tau](https://academylearningtau.streamlit.app)** (Streamlit; [DOI 10.5281/zenodo.21301571](https://doi.org/10.5281/zenodo.21301571)) y la aplicación de escritorio **Systemic Tau** para macOS.

        Mis publicaciones recientes (2026) están disponibles en [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22).

        [Ver todas las publicaciones](publications/) · [Descargar BibTeX](uploads/BibTeX_Clean_2026.bib) · [Descargar CV (PDF)](uploads/resume.pdf)

        Contacto para colaboración: [joel.padilla2@upr.edu](mailto:joel.padilla2@upr.edu) · [johelpadilla@gmail.com](mailto:johelpadilla@gmail.com)
    design:
      columns: '1'
  - block: markdown
    id: software
    content:
      title: '💻 Software'
      subtitle: 'Academy Learning Tau · Systemic Tau · excess³'
      text: |-
        Implementaciones abiertas del paradigma **Tau Sistémico (τ_s)** y de la **Ley del Reloj Extramental Discreto (RECD)**.

        ---

        ### 1. Academy Learning Tau v1.1.0 — plataforma educativa (web)

        Plataforma abierta de **docencia e investigación exploratoria** (Streamlit) para métricas ordinales τ_s, niveles RECD anidados, señales clásicas de alerta temprana, nulos por surrogados y laboratorio multipágina con exportaciones reproducibles. Idiomas: **español · inglés · francés**.

        **Citar / DOI:** [10.5281/zenodo.21301571](https://doi.org/10.5281/zenodo.21301571)

        | Recurso | Enlace |
        |---------|--------|
        | App en vivo | [academylearningtau.streamlit.app](https://academylearningtau.streamlit.app) |
        | Repositorio | [github.com/johelpadilla/academy-learning-tau](https://github.com/johelpadilla/academy-learning-tau) |
        | Release v1.1.0 | [GitHub Releases](https://github.com/johelpadilla/academy-learning-tau/releases/tag/v1.1.0) |
        | Zenodo | [doi.org/10.5281/zenodo.21301571](https://doi.org/10.5281/zenodo.21301571) |

        **Módulos:** Fundamentos · Matemática · Dominios · Laboratorio · Ruta de aprendizaje · Evidencia · Docencia · Evaluaciones · Biblioteca.

        ---

        ### 2. Systemic Tau — aplicación de escritorio (macOS)

        Aplicación nativa para análisis con pre-procesamiento, capa de salud de datos (NaNs), suavizado de señales, reportes deterministas y núcleo en formato académico. Instalación desde el instalador `.dmg` en GitHub Releases.

        | Recurso | Enlace |
        |---------|--------|
        | Releases (.dmg + código) | [github.com/johelpadilla/systemictau/releases](https://github.com/johelpadilla/systemictau/releases) |
        | Repositorio | [github.com/johelpadilla/systemictau](https://github.com/johelpadilla/systemictau) |
        | Guía de usuario | [USER_GUIDE.md](https://github.com/johelpadilla/systemictau/blob/main/USER_GUIDE.md) |

        *Instalación (macOS):* abrir el `.dmg` → arrastrar la app a Aplicaciones → en el primer arranque, clic derecho → «Abrir» si el sistema advierte de desarrollador no firmado.

        ---

        ### 3. excess³ — proxy continuo de dependencia de orden 3

        Familia documental y código para un proxy preespecificado de *synergistic surplus* de orden 3 (métodos + validación sintética, intro en español, guía interdisciplinaria).

        | Recurso | Enlace |
        |---------|--------|
        | Repositorio | [github.com/johelpadilla/excess3](https://github.com/johelpadilla/excess3) |
        | DOI | [10.5281/zenodo.21385937](https://doi.org/10.5281/zenodo.21385937) |
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
