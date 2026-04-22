---
title: Thesis
summary: My PhD Thesis
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: markdown
    content:
      title: 'Thesis'
      text: |
        The thesis is a compilation of the papers mentioned below. It consists of the papers and a comprehensive summary (kappa). It is available here: https://grahnen.se/uploads/thesis.pdf
    design:
      columns: '1'
  - block: collection
    id: thesispapers
    content:
      title: Publications in Thesis
      filters:
        folders:
          - publication
        tags: 
          - thesis
    design:
      view: citation
---
