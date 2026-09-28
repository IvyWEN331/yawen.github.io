---
title: ''
summary: ''
date: 2026-09-24
type: landing

sections:
  - block: resume-biography-3
    id: profile
    content:
      username: me
      text: |-
        I am a Research Associate at the University of Cambridge, working at the intersection of architecture, digital twins, knowledge systems, and AI for the built environment.

        Digital systems should help buildings and infrastructure deliver services more efficiently and intelligently. I explore how geometric, semantic, and dynamic operational information can be structured into shared knowledge that supports decision-making in digital systems across the built asset lifecycle and enables collaboration between people and AI.

        **Beyond academia, I am passionate about turning research into real-world impact.** I have worked closely with industry, government bodies, and asset owners on projects spanning digital construction, building operations, and smart infrastructure, particularly in Hong Kong, the UK, and Europe. I enjoy bringing research beyond papers and prototypes—translating ideas into methods, systems, and solutions that can make a tangible difference in practice. **I am always open to collaborations that connect ambitious research with real challenges in the built environment.**
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

  - block: work-experience
    id: work-experience
    content:
      username: me

  - block: markdown
    id: research
    content:
      title: 'Research Profile'
      subtitle: ''
      text: |-
        I interpret Digital Twin modelling through three complementary dimensions: **Maturity of Digital Twin**, **Scope of Digital Twin**, and **Temporal Dimension**. The framework below summarises how I structure this understanding across modelling intent, system scale, and time.

        ![Digital Twin modelling framework](media/digital-twin-dimensions.png)

        My research explores how **physical buildings and digital representations can remain connected across the building lifecycle**. A central theme is moving from a Digital Twin as a geometric model toward a **shared semantic world model** that can support people, building systems, and heterogeneous embodied agents. Current interests include Scan-to-BIM, ontology- and knowledge-graph-driven reasoning, multi-agent coordination, and the use of digital building information to support operation and maintenance.
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
