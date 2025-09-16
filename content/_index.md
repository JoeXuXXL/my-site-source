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
      css_class: g-gradient-to-b from-sky-50 via-white to-white dark:from-slate-800 dark:via-sky-950 dark:to-slate-950  # hbx-bg-gradient
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: "Education"
      text: |
        <div class="education-grid">
          <!-- PhD -->
          <div class="education-item">
            <div class="education-icon">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path d="M12 14l9-5-9-5-9 5 9 5z" />
                <path d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l9-5-9-5-9 5 9 5zm0 0l-9 5m9-5v6" />
              </svg>
            </div>
            <div class="education-content">
              <h3 class="education-title">PhD Informatique</h3>
              <p class="education-institution">Inria Paris-Saclay & Institut Polytechnique de Paris</p>
              <p class="education-location">France</p>
              <p class="education-dates">2023 - Present</p>
              <p class="education-description">Supervised by Prof. Marc-Olivier Renou</p>
            </div>
          </div>

          <!-- MSc -->
          <div class="education-item">
            <div class="education-icon">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path d="M12 14l9-5-9-5-9 5 9 5z" />
                <path d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l9-5-9-5-9 5 9 5zm0 0l-9 5m9-5v6" />
              </svg>
            </div>
            <div class="education-content">
              <h3 class="education-title">MSc Mathematics</h3>
              <p class="education-institution">ETH Zürich</p>
              <p class="education-location">Switzerland</p>
              <p class="education-dates">2020 - 2023</p>
            </div>
          </div>

          <!-- BSc -->
          <div class="education-item">
            <div class="education-icon">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path d="M12 14l9-5-9-5-9 5 9 5z" />
                <path d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l9-5-9-5-9 5 9 5zm0 0l-9 5m9-5v6" />
              </svg>
            </div>
            <div class="education-content">
              <h3 class="education-title">BSc Mathematics and Physics</h3>
              <p class="education-institution">University of Toronto</p>
              <p class="education-location">Canada</p>
              <p class="education-dates">2016 - 2020</p>
            </div>
          </div>
        </div>
    design:
      columns: "1"
      css_class: education-section

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
