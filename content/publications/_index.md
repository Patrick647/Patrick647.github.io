---
title: Publications
cms_exclude: true
type: landing

# Papers have no detail pages: the list links straight to each PDF.
# "link" (not "never") keeps them in taxonomies, which the collection filters
# (exclude_publication_type / publication_type) depend on. Bundle PDFs are still published.
# private keeps the unrendered URLs out of the theme's sitemap and 404 suggestions.
cascade:
  - target:
      kind: page
    build:
      render: link
      list: always
      publishResources: true
    params:
      private: true
outputs: [HTML]

design:
  spacing: '1.5rem'

sections:
  - block: collection
    id: published-papers
    content:
      title: Published Articles
      text: 'Journal articles that have been published.<span class="pub-legend">\* Corresponding author · † Co-first author / equal contribution</span>'
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
