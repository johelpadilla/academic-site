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
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I develop conceptual frameworks in Systemic Tau (τ_s) and the Discrete Extramental Clock Law (RECD). I integrate fractal dimension analysis (D ≈ 1.98), ontological permeability, ordinal metrics, and discrete models for complex systems, with applications to early warning (dengue) and higher-order dependence proxies (excess³).

        Open software in this program includes the educational platform **[Academy Learning Tau](https://academylearningtau.streamlit.app)** (Streamlit; [DOI 10.5281/zenodo.21301571](https://doi.org/10.5281/zenodo.21301571)) and the **Systemic Tau** desktop application for macOS.

        Recent publications (2026) are available on [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Padilla-Villanueva%2C+Johel%22).

        [See all publications](publications/) · [Download BibTeX](uploads/BibTeX_Clean_2026.bib) · [Download CV (PDF)](uploads/resume.pdf)

        Contact for collaboration: [joel.padilla2@upr.edu](mailto:joel.padilla2@upr.edu) · [johelpadilla@gmail.com](mailto:johelpadilla@gmail.com)
    design:
      columns: '1'
  - block: markdown
    id: software
    content:
      title: '💻 Software'
      subtitle: 'Academy Learning Tau · Systemic Tau · excess³'
      text: |-
        Open implementations of the **Systemic Tau (τ_s)** paradigm and the **Discrete Extramental Clock Law (RECD)**.

        ---

        ### 1. Academy Learning Tau v1.1.0 — educational platform (web)

        Open **teaching and exploratory research** platform (Streamlit) for ordinal τ_s metrics, nested RECD levels, classical early-warning signals, surrogate nulls, and a multipage laboratory with reproducible exports. Languages: **Spanish · English · French**.

        **Cite / DOI:** [10.5281/zenodo.21301571](https://doi.org/10.5281/zenodo.21301571)

        | Resource | Link |
        |----------|------|
        | Live app | [academylearningtau.streamlit.app](https://academylearningtau.streamlit.app) |
        | Repository | [github.com/johelpadilla/academy-learning-tau](https://github.com/johelpadilla/academy-learning-tau) |
        | Release v1.1.0 | [GitHub Releases](https://github.com/johelpadilla/academy-learning-tau/releases/tag/v1.1.0) |
        | Zenodo | [doi.org/10.5281/zenodo.21301571](https://doi.org/10.5281/zenodo.21301571) |

        **Modules:** Foundations · Mathematics · Domains · Laboratory · Learning path · Evidence · Teaching · Assessments · Library.

        ---

        ### 2. Systemic Tau — desktop application (macOS)

        Native app for analysis with pre-processing, data-health layer (NaNs), signal smoothing, deterministic reports, and an academic-format kernel. Install from the `.dmg` on GitHub Releases.

        | Resource | Link |
        |----------|------|
        | Releases (.dmg + source) | [github.com/johelpadilla/systemictau/releases](https://github.com/johelpadilla/systemictau/releases) |
        | Repository | [github.com/johelpadilla/systemictau](https://github.com/johelpadilla/systemictau) |
        | User guide | [USER_GUIDE.md](https://github.com/johelpadilla/systemictau/blob/main/USER_GUIDE.md) |

        *macOS install:* open the `.dmg` → drag the app to Applications → on first launch, right-click → “Open” if the system warns about an unsigned developer.

        ---

        ### 3. excess³ — continuous proxy for order-3 dependence

        Document family and code for a pre-specified proxy of order-3 synergistic surplus (methods + synthetic validation, Spanish introduction, cross-disciplinary guide).

        | Resource | Link |
        |----------|------|
        | Repository | [github.com/johelpadilla/excess3](https://github.com/johelpadilla/excess3) |
        | DOI | [10.5281/zenodo.21385937](https://doi.org/10.5281/zenodo.21385937) |
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
    design:
      view: citation
---