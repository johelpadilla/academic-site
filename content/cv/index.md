---
title: 'CV'
date: 2026-07-17
type: landing
summary: 'Curriculum vitae — trayectoria, skills y premios.'
aliases:
  - /resume/
  - /curriculum/

design:
  spacing: '3rem'

sections:
  - block: markdown
    content:
      title: 'Curriculum vitae'
      text: |-
        Versión PDF: **[Descargar CV](../uploads/resume.pdf)** · Word: [Resume](../uploads/Johel_Padilla_Resume.docx)

        Perfil ampliado: [Sobre mí](../about/) · [Autor](../authors/me/)
    design:
      columns: '1'

  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: PDF
        url: uploads/resume.pdf
      headings:
        about: 'Resumen'
        education: 'Formación'
        interests: 'Líneas'
    design:
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: resume-experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: true

  - block: resume-skills
    content:
      title: Competencias
      username: me

  - block: resume-awards
    content:
      title: Premios y servicio
      username: me

  - block: resume-languages
    content:
      title: Idiomas
      username: me
---
