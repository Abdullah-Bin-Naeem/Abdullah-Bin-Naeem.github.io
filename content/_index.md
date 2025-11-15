---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Abdullah-Bin-Naeem-CV.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '🤖 About My Work'
      subtitle: ''
      text: |-
        I am an Artificial Intelligence graduate from FAST-NUCES in Islamabad, currently building Generative AI and computer vision systems at Automotive AI GmbH. I focus on perception for autonomous platforms, reinforcement learning for embodied agents, and multimodal pipelines that blend language, vision, and geospatial context.

        **Primary interests:** Computer Vision · Generative AI · Robotics · Reinforcement Learning · Embedded Systems.

        **What I'm working on:**

        - Scaling perception and planning stacks for autonomous mobility and smart-city robotics.
        - Deploying multimodal models (vision, language, telemetry) that explain predictions and automate reporting.
        - Translating research—like FACT++ hand keypoint fusion—into reproducible baselines and production-ready code.

        I'm always excited to collaborate on impactful computer vision, robotics, and AI-for-good initiatives. Reach out via email or LinkedIn if you'd like to jam on an idea.
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
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: '🎓 Teaching Experience'
      text: |-
        I am curating a teaching portfolio that highlights the mentorship and instructional roles I've taken on at FAST-NUCES and partner programs. If you're reviewing my profile ahead of a teaching or TA engagement, feel free to copy the template below and share the specifics you'd like me to highlight.

        **Template**

        - `[Course Name]`, `[Role — e.g., Teaching Assistant or Lab Demonstrator]`
        - `University: [Name]`
        - `Dates: [e.g., Fall 2024]`
        - `Responsibilities: [Graded assignments, led labs, held office hours, etc.]`

        I'm happy to provide detailed syllabi support, lab material reviews, or guest lectures upon request.
    design:
      columns: '1'
---
