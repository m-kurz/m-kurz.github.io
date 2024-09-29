---
# Leave the homepage title empty to use the site title
title: "Marius Kurz"
date: 2024-09-29
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: marius
      text: ""
      ## Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: turbine.jpg
          filters:
            brightness: 0.3
          size: cover
          position: bottom
          parallax: true

  - block: resume-experience
    id: experience
    draft: true
    content:
      username: marius
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false

  #- block: markdown
  #  content:
  #    title: 'Hey there 👋'
  #    subtitle: ''
  #    text: |-
  #      🔭   I’ve always been driven by a blend of scientific curiosity and technical challenges.

  #      🌟   I thrive on the synergy between science and number crunching—whether it's optimizing algorithms for novel HPC systems, implementing cutting-edge numerical methods or using machine learning to rethink traditional simulations.

  #      🚀   In recent years, I've applied HPC to enable large-scale CFD simulations of turbulent flows and explored how machine learning can be used to develop smarter, data-driven turbulence models for large eddy simulation.

  #      📝   Along the way, I’ve contributed to several open-source projects both inside and outside these fields.

  #      💬   If you're into CFD, HPC, or the fusion of machine learning and simulation, feel free to reach out!
  #  design:
  #    columns: '1'
  #    css_class: dark
  #    spacing:
  #      padding: [25px, 25px, 25px, 25px]
  #    background:
  #      color: black
  #      image:
  #        filename: turbine.jpg
  #        filters:
  #          brightness: 0.3
  #        size: cover
  #        position: bottom
  #        parallax: true

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 3
      css_class: dark
      background:
        color: black
        image:
          filename: turbine.jpg
          filters:
            brightness: 0.35
          size: cover
          position: bottom
          parallax: true

  - block: collection
    content:
      title:
      count: 6
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: [0, 25px, 0, 25px]
---
