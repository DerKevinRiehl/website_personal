---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:

  - block: portfolio
    id: Research
    content:
      title: Research Areas
      #subtitle: my research
      filters:
        folders:
          - research_areas
          # research
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      #buttons:
       # - name: All
       #   tag: '*'
       # - name: AI/ML in healthcare
       #   tag: AI/ML in healthcare
       # - name: Digital Age & Healthspan
       #   tag: Digital Age & Healthspan
       # - name: Digital Inflammatory Biomarker
       #   tag: Digital Inflammatory Biomarker
       # - name: Pharmacoepi
       #   tag: Pharmacoepi
       # - name: Multi-modal Data
       #   tag: Multi-modal Data
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: TRUE
      spacing: {padding: [0, 0, 0, 0]}


  - block: portfolio
    id: Research
    content:
      title: Featured Work
      #subtitle: my research
      filters:
        folders:
          - publication
          # research
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: TRUE
      spacing: {padding: [0, 0, 0, 0]}

---
