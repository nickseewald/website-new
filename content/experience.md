---
title: 'About Nick'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: hero
    id: about-hero
    content:
      title: 'About Nick'
      primary_action:
        text: 'Curriculum Vitae'
        url: 'https://raw.githubusercontent.com/nickseewald/seewaldCV/main/Seewald-Curriculum-Vitae.pdf'
        icon: 'hero/arrow-top-right-on-square'
    design:
      background:
        image:
          filename: 'nick-galton-board.jpg'
          parallax: false
          # Note: filters don't seem to work as of 1/18/26. Brightness, etc. are controlled in 'custom.css'
        text_color_light: true
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-awards
    content:
      title: Awards
      username: me
---
