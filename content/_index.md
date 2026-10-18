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
    id: medios
    content:
      title: 'Medios de comunicación'
      subtitle: ''
      text: |-
        Antes de llegar a la universidad trabajé en la radio. Estuve en Panorama Stéreo, en Gigante (Huila), entre 2004 y 2007, y en Colmundo Radio, en Ibagué, entre 2012 y 2014. En 2011 me formé como técnica laboral en locución para radio, presentación de televisión y periodismo en el Instituto Nacional de Telecomunicaciones (INSTEL).

        De ese oficio vienen el Micrófono de Oro de la Asociación Tolimense de Locutores y la medalla de la Policía Metropolitana de Ibagué por labor periodística. También viene de ahí lo que hoy enseño en Narrativas Radiofónicas y Periodismo Cultural, y la idea de que la voz de la gente merece guardarse.
    design:
      columns: '1'

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

  - block: markdown
    id: reconocimientos
    content:
      title: 'Reconocimientos'
      subtitle: ''
      text: |-
        - Reconocimiento como mejor docente catedrática de la Universidad del Tolima.
        - Micrófono de Oro, Asociación Tolimense de Locutores.
        - Medalla de la Policía Metropolitana de Ibagué por labor periodística.
        - Exaltación de la Asamblea Departamental del Tolima.
    design:
      columns: '1'
---
