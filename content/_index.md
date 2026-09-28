---
title: ''
summary: ''
date: 2026-09-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |-
        I am a Research Associate at the University of Cambridge, working at the intersection of architecture, digital twins, knowledge systems, and AI for the built environment.

        Digital systems should help buildings and infrastructure deliver services more efficiently and intelligently. I explore how geometric, semantic, and dynamic operational information can be structured into shared knowledge that supports decisions across the built asset lifecycle and enables collaboration between people and AI.
      button:
        text: Download CV
        url: uploads/Ya_Wen_CV.pdf
      headings:
        about: 'Hi, I am Ya Wen'
        education: Education
        interests: Research Interests
    design:
      background:
        color: "#0b0d10"
        gradient_mesh:
          enable: false
      name:
        size: xs
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: research
    content:
      title: 'Research Profile'
      subtitle: ''
      text: |-
        My research explores how **physical buildings and digital representations can remain connected across the building lifecycle**. I work across architecture, BIM/GIS, reality capture, Digital Twins, semantic knowledge representation, and AI-enabled decision support.

        A central theme is moving from a Digital Twin as a geometric model toward a **shared semantic world model** that can support people, building systems, and heterogeneous embodied agents. Current interests include Scan-to-BIM, ontology- and knowledge-graph-driven reasoning, multi-agent coordination, fire-safety inspection, and the use of digital building information to support operation and maintenance.

        ### Digital Twin Modelling: Three Dimensions

        I conceptualise Digital Twin modelling through three complementary dimensions: **maturity**, **scope**, and **time**. Select a concept below to explore how each dimension develops.

        <iframe class="dt-dimensions-frame" src="widgets/digital-twin-dimensions.html" title="Interactive Digital Twin modelling dimensions" loading="lazy"></iframe>
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: Research projects connecting architecture, digital twins, sensing, semantics, and intelligent building operation.
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: true

  - block: collection
    id: papers
    content:
      title: Publications
      text: Selected journal and conference publications. Full publication records can be added from BibTeX/DOI or my CV.
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: markdown
    id: teaching
    content:
      title: 'Teaching & Academic Engagement'
      subtitle: ''
      text: |-
        Teaching and academic activities span **digital construction, BIM, architecture, and the digital built environment**, including teaching assistance at the University of Cambridge, guest teaching at UCL, and previous teaching support at the University of Hong Kong.

        I am particularly interested in connecting **design thinking with digital building technologies**, so that students can understand not only how to model buildings, but also how digital information supports construction, operation, maintenance, safety, and emerging robotic systems.
    design:
      columns: '1'

  - block: markdown
    id: contact
    content:
      title: 'Collaboration'
      subtitle: ''
      text: |-
        I welcome conversations around **architecture technology, Digital Twins, reality capture, semantic building information, AI for the built environment, and robotics-enabled building operation**.

        Please use the professional links in the profile above.
    design:
      columns: '1'
---
