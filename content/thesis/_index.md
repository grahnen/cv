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
    title: 'Thesis'
    text: |
      The thesis is a compilation of the papers mentioned below. It will consist of the papers, as well as a /kappa/, which I am currently writing. Once there is a rough draft i will upload it here.
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
