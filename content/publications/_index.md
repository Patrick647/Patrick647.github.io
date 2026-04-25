---
title: Publications
cms_exclude: true
type: landing

design:
  spacing: '2.5rem'

sections:
  - block: collection
    id: working-papers
    content:
      title: Preprints & Manuscripts
      text: Current ADR and clinical informatics manuscripts.
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
      title: Published Articles
      text: Peer-reviewed publications and related academic outputs.
      count: 10
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
