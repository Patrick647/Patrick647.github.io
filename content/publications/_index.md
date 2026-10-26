---
title: Publications
cms_exclude: true
type: landing

# Bylines already list every author; skip the per-author cards under each paper.
cascade:
  params:
    profile: false

design:
  spacing: '1.5rem'

sections:
  - block: collection
    id: published-papers
    content:
      title: Peer-reviewed Publications
      text: 'Published journal articles and related scholarly outputs.<span class="pub-legend">\* Corresponding author · † Co-first author / equal contribution</span>'
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

  - block: collection
    id: working-papers
    content:
      title: Working Papers
      text: 'Manuscripts currently under peer review.<span class="pub-legend">\* Corresponding author · † Equal contribution</span>'
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
---
