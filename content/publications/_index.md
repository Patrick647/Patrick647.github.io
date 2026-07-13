---
title: Publications
cms_exclude: true
type: landing

design:
  spacing: '3rem'

sections:
  - block: collection
    id: working-papers
    content:
      title: Working Papers
      text: Manuscripts currently under peer review.
      count: 10
      sort_by: Date
      sort_ascending: false
      filters:
        folders:
          - publications
        publication_type: working-paper
      archive:
        enable: false
    design:
      view: citation
      show_read_time: false
      background:
        color: white

  - block: collection
    id: published-papers
    content:
      title: Publications
      text: Published peer-reviewed papers and related outputs.
      count: 0
      sort_by: Date
      sort_ascending: false
      filters:
        folders:
          - publications
        exclude_publication_type: working-paper
      archive:
        enable: false
    design:
      view: citation
      show_read_time: false
      background:
        color: white
---
