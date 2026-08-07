---
title: "Research"
type: "landing"

sections:
- block: hero
  id: intro
  design:
    no_padding: true
    background:
      image: 
        filename: sparsh-paliwal-2PLFgAKVpe0-unsplash.jpg
        filters:
            brightness: .45
            size: cover
            position: top
    css_class: dark
  content:
    title: "Research"
- block: markdown
  id: research-summary
  content:
      # title: Overview
      text: |
        <h2>I am an applied statistician who builds statistical tools to enable cool science.</h2>

        I have deep expertise in causal inference with complex longitudinal data, and apply that expertise to a variety of methodological and application areas, including health policy,substance use, and oncology. Below is a selection of [methodological](#methods-projects) and [collaborative](#collab-projects) projects.
- block: portfolio
  id: methods-projects
  content:
    title: Methods Projects
    filters:
      folders:
        - projects
      tags:
        - methods
      exclude_tags: [software, applied]
    sort_by: 'Title'
    sort_ascending: true
    buttons:
      - name: All
        tag: '*'
      - name: Health Policy
        tag: 'health policy'
      - name: Sequentially-Randomized Trials
        tag: 'SMARTs'
    design:
      view: 'showcase'
      columns: '1'
- block: portfolio
  id: collab-projects
  content:
      title: Applied & Collaborative Projects
      subtitle: Selected projects give a high-level overview of my applied work, interests, and expertise, but I'm always open to learning something new.
      filters:
        folders:
          - projects
        exclude_tags: [software, methods]
      sort_by: 'Title'
      sort_ascending: true
      buttons:
        - name: All
          tag: '*'
        - name: Health Policy
          tag: 'health policy'
        - name: Oncology
          tag: 'cancer'
  design:
    view: showcase
    columns: '1'
---
