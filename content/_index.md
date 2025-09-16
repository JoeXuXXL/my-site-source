---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-09-14
type: landing

design:
  # Default section spacing
  spacing: '3rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/CV_phdphase.pdf
      headings:
        about: About me
        # education: Education
        interests: Research Interests
    design:
      # Apply a gradient background
      css_class: g-gradient-to-b from-sky-250 via-sky-100 to-white dark:from-slate-800 dark:via-sky-900 dark:to-slate-950  # hbx-bg-gradient
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: features
    content:
      title: Education
      # The 'features' block is responsive. It will be 3 columns on large screens,
      # and automatically adjust to 2 or 1 column on smaller screens.
      columns: '3'
      items:
        - name: '**PhD in Informatique**'
          description: '<span class="text-lg font-semibold text-primary-600 dark:text-primary-400">Inria Paris-Saclay & Institut Polytechnique de Paris</span><br>France • 2023–Present<br>Supervised by Prof. Marc-Olivier Renou'
          icon: hero/graduation-cap
          # icon_pack: fas
        - name: '**MSc in Mathematics**'
          description: '<span class="text-lg font-semibold text-primary-600 dark:text-primary-400">ETH Zürich</span><br>Switzerland • 2020–2023'
          icon: hero/graduation-cap
          # icon_pack: fas
        - name: '**BSc in Mathematics and Physics**'
          description: '<span class="text-lg font-semibold text-primary-600 dark:text-primary-400">University of Toronto</span><br>Canada • 2016–2020'
          icon: hero/graduation-cap
          # icon_pack: fas
    design:
      # This ensures the background color matches the rest of the page.
      # You can also use 'hbx-bg-gradient' or other classes if you prefer.
      css_class: g-gradient-to-b from-sky-200 via-sky-50 to-white dark:from-slate-800 dark:via-sky-900 dark:to-slate-950
  # - block: markdown
  #   content:
  #     title: "Education"
  #     text: |
  #       **🎓 PhD in Informatique**  
  #       *Inria Paris-Saclay & Institut Polytechnique de Paris*  
  #       France • 2023–Present  
  #       Supervised by Prof. Marc-Olivier Renou

  #       **🎓 MSc in Mathematics**  
  #       *ETH Zürich*  
  #       Switzerland • 2020–2023

  #       **🎓 BSc in Mathematics and Physics**  
  #       *University of Toronto*  
  #       Canada • 2016–2020
  #   design:
  #     columns: "3"
  #     css_class: g-gradient-to-b from-sky-200 via-sky-50 to-white dark:from-slate-800 dark:via-sky-900 dark:to-slate-950

  # - block: resume-experience
  #   content:
  #     title: "Education"
  #     items:
  #       - title: "PhD Infomatique"
  #         company: "Inria Paris-Saclay & Institut Polytechnique de Paris"
  #         location: "France"
  #         date_start: "2023-10-01"
  #         date_end: ""
  #         description: |
  #           Supervised by Prof. Marc-Olivier Renou
  #       - title: "MSc Mathematics"
  #         company: "Eidgenössische Technische Hochschule (ETH) Zürich"
  #         location: "Switzerland"
  #         date_start: "2020-09-15"
  #         date_end: "2023-06-03"
  #       - title: "BSc Mathematics and Physics"
  #         company: "University of Toronto"
  #         location: "Canada"
  #         date_start: "2016-09-01"
  #         date_end: "2020-05-31"
  #   design:
  #     columns: "1"
  # - block: markdown
  #   content:
  #     title: 'About me'
  #     subtitle: ''
  #     text: |-
  #       I am a mathematical physicist in quantum information theory and quantum foundations. 

  #       I am interested in understanding quantum network correlations, many-body physics, and cryptography, by applying tools including the theory of operator algebras and noncommutative polynomial optimization. I joined the team PhiQus at Inria Paris-Saclay as a PhD student since October 2023. 

  #       Feel free reach me at xu[dot]xiangling[at]inria[dot]fr.
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ''
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - conference
  #   design:
  #     view: card
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
