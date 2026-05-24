---
title: ""
summary: ""
date: 2026-05-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ""
      button:
        text: Download CV
        url: uploads/cv.pdf
      headings:
        about: About
        education: Education
        interests: Interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: "What I work on"
      subtitle: ""
      text: |-
        I spend my time turning messy real-world data into useful information and actionable initiatives.

        Lately that's looked like building **agentic AI** for marketplace
        platforms, designing **fraud and data-leakage** detection across
        sensitive channels, and shipping **causal and time-series** models
        that ground business choices in something more than intuition.

        Before tech, I led growth analytics for Latin America's largest
        wholesale bank and ran economic research for São Paulo state.

        I write occasional notes on this site. Reach out if any of that
        overlaps with what you're working on.
    design:
      columns: "1"

  - block: collection
    id: blog
    content:
      title: Recent writing
      subtitle: ""
      text: ""
      page_type: blog
      count: 5
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
