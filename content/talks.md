---
title: 'Talks'
date: 2024-05-19
type: landing # This makes it a standalone landing page

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    id: talks_list # Give it an ID to reference if needed
    content:
      title: My Recent Talks
      text: Here are some of the talks I have given so far, showcasing my research and expertise.
      # Configure the collection to pull content of type 'talk'
      page_type: talk # <--- THIS IS THE KEY CHANGE
      count: 10 # Number of talks to display, e.g., 10 or 0 for all
      # filter_default: 0 # Optionally, if you want to filter by tags/categories
      # filter_button:  # You can add filter buttons if you want
      #  - name: All
      #    tag: '*'
      #  - name: Specific Tag
      #    tag: 'my_tag'

    design:
      columns: '1' # How many columns to display the talks (e.g., '1', '2')
      view: list # How to display each talk (e.g., 'list', 'compact', 'card')
      # You can customize the view further based on your theme's options
      # For a "talk" type, a 'list' view is often good.
---