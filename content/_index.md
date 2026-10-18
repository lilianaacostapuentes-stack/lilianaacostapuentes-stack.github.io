---
title: ''
summary: ''
date: 2026-10-18
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: 'Sobre mí'
        education: 'Formación'
        interests: 'Intereses'
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Mi trabajo'
      subtitle: ''
      text: |-
        Trabajo con comunidades rurales en ejercicios de mapeo colectivo, círculos de palabra y archivo sonoro. Me interesa que lo que la gente dice en un encuentro no se pierda: que quede en su memoria y le sirva para decidir sobre su territorio.

        Mi investigación de maestría estudió la participación ciudadana en el ordenamiento territorial de Icononzo (Tolima). De ese trabajo nacen proyectos como el Herbario sonoro, una estrategia de comunicación comunitaria con mujeres rurales.
    design:
      columns: '1'

  - block: collection
    id: proyectos
    content:
      title: Proyectos
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
      show_date: false
      show_read_time: false

  - block: collection
    id: publicaciones
    content:
      title: Publicaciones
      text: ''
      filters:
        folders:
          - publications
    design:
      view: citation

  - block: markdown
    id: ponencias
    content:
      title: 'Ponencias'
      subtitle: ''
      text: |-
        - **2025.** «Extensión universitaria en clave decolonial: del conocimiento que se lleva al conocimiento que se construye». XX Encuentro Latinoamericano FELAFACS, Palmas (Brasil).
        - **2024.** «Voces que siembran memoria: radio y archivo sonoro comunitario en territorios rurales del Tolima». Encuentro Regional FELAFACS México, área Nuevas Narrativas.
    design:
      columns: '1'
---
