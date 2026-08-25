---
title: ""
date: 2022-08-14
type: landing

design:
  spacing: "2rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: https://usf.box.com/s/k9g864k4o6t23z1psg74t8qr8a5zez93
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation

  - block: collection
    id: working_papers
    content:
      title: Working Papers
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      view: citation

  - block: collection
    id: works_in_progress
    content:
      title: Works in Progress
      filters:
        folders:
          - works_in_progress
    design:
      view: citation

  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        <div style="font-size: 0.9em;">
        Kate Tiedemann School of Business and Finance, University of South Florida<br>
        4202 East Fowler Avenue, Tampa, FL 33620<br>
        Email: <a href="mailto:dfang@usf.edu">dfang@usf.edu</a><br>
        </div>
    design:
      columns: '1'
---
