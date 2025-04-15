---
title: 'Home'
date: 2025-03-19
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Principle 1 - Perceivable
      text: Web Content Accessibility Guidelines (WCAG) Principles
      primary_action:
        text: Guidelines
        url: docs/
        icon: rocket-launch
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: "home-hero.jpg"
          focal_point: "Top"
          filters:
            brightness: 0.2
  
  - block: stats
    content:
      items:
        - statistic: "1.3B+"
          description: |
            World population  
            with disabilities  
            in 2024
        - statistic: "40k+"
          description: |
            Enterprise  
            websites
        - statistic: "3%"
          description: |
            Are accessible   
            for the disabled community
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-800"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  
  - block: features
    content:
      title: What is WCAG? 
      text: "The **Web Content Accessibility Guidelines (WCAG)** were developed with the goal of providing a single shared standard for the accessibility of web content that meets the needs of individuals, organizations and governments at an international level. WCAG helps to create web content that is more accessible to people with disabilities. This standard is composed by 4 principles: **Perceivable**, **Operable**, **Understandable** and **Robust**."
    design: 
      spacing:
        padding: ["5rem", 0, 0, 0]
  
  - block: features
    content:
      title: Principle 1 - Perceivable
      text: This is the first principle of WCAG, the goal of this is to present information and user interface components in ways users can **perceive** them. Meaning, that the information presented to users **can't be invisible to all their senses**.
      items:
        - name: Text Alternatives
          icon: document-text
          description: Provide **text alternatives** for any **non-text content** so that it can be changed into other forms people need, such as large print, braille, speech, symbols or simpler language.
        - name: Time-based Media
          icon: camera
          description: Provide **alternatives** for **time-based media**.
        - name: Adaptable
          icon: view-columns
          description: Create content that can be presented in different ways (for example simpler layout) **without losing information or structure**.
        - name: Distinguishable
          icon: speaker-wave
          description: Make it **easier** for users to see and **hear content** including separating foreground from background.
    design: 
      spacing:
        margin: [0, 0, 0, 0]
        padding: [0, 0, 0, 0]
---
