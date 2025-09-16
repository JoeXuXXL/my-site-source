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
      css_class: g-gradient-to-b from-sky-100 via-white to-white dark:from-slate-800 dark:via-sky-950 dark:to-slate-950  # hbx-bg-gradient
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: "Education"
      text: |
        <div class="education-container">
          <!-- PhD -->
          <div class="education-card phd-card">
            <div class="card-header">
              <div class="degree-icon">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                  <path d="M11.7 2.805a.75.75 0 01.6 0A60.65 60.65 0 0122.83 8.72a.75.75 0 01-.231 1.337 49.949 49.949 0 00-9.902 3.912l-.003.002-.34.18a.75.75 0 01-.707 0l-.34-.18-.003-.002a49.981 49.981 0 00-9.902-3.912.75.75 0 01-.231-1.337A60.65 60.65 0 0111.7 2.805z" />
                  <path fill-rule="evenodd" d="M12 2.25a.75.75 0 01.75.75v5.5a.75.75 0 01-1.5 0V3a.75.75 0 01.75-.75zM6.938 4.5a.75.75 0 01.75.75v2.25a.75.75 0 01-1.5 0V5.25a.75.75 0 01.75-.75zm10.125 0a.75.75 0 01.75.75v2.25a.75.75 0 01-1.5 0V5.25a.75.75 0 01.75-.75z" clip-rule="evenodd" />
                  <path d="M4.663 10.711a49.997 49.997 0 00-2.413 4.87.75.75 0 00.636.812l.34.061a.75.75 0 01.155 1.488l-.337.067a.75.75 0 00-.655.739v1.32c0 .414.336.75.75.75h17.25a.75.75 0 00.75-.75v-1.32a.75.75 0 00-.655-.739l-.338-.067a.75.75 0 01.155-1.488l.34-.061a.75.75 0 00.635-.812 49.979 49.979 0 00-2.413-4.87 3.75 3.75 0 00-6.552 0l-.094.176a.75.75 0 01-1.342 0l-.094-.176a3.75 3.75 0 00-6.552 0z" />
                </svg>
              </div>
              <div class="degree-info">
                <h3>PhD Informatique</h3>
                <p class="institution">Inria Paris-Saclay & Institut Polytechnique de Paris</p>
                <p class="duration">2023 - Present</p>
              </div>
            </div>
            <div class="card-details">
              <p>Supervised by Prof. Marc-Olivier Renou</p>
              <p class="location">France</p>
            </div>
          </div>

          <!-- MSc -->
          <div class="education-card msc-card">
            <div class="card-header">
              <div class="degree-icon">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                  <path d="M11.7 2.805a.75.75 0 01.6 0A60.65 60.65 0 0122.83 8.72a.75.75 0 01-.231 1.337 49.949 49.949 0 00-9.902 3.912l-.003.002-.34.18a.75.75 0 01-.707 0l-.34-.18-.003-.002a49.981 49.981 0 00-9.902-3.912.75.75 0 01-.231-1.337A60.65 60.65 0 0111.7 2.805z" />
                  <path fill-rule="evenodd" d="M12 2.25a.75.75 0 01.75.75v5.5a.75.75 0 01-1.5 0V3a.75.75 0 01.75-.75zM6.938 4.5a.75.75 0 01.75.75v2.25a.75.75 0 01-1.5 0V5.25a.75.75 0 01.75-.75zm10.125 0a.75.75 0 01.75.75v2.25a.75.75 0 01-1.5 0V5.25a.75.75 0 01.75-.75z" clip-rule="evenodd" />
                  <path d="M4.663 10.711a49.997 49.997 0 00-2.413 4.87.75.75 0 00.636.812l.34.061a.75.75 0 01.155 1.488l-.337.067a.75.75 0 00-.655.739v1.32c0 .414.336.75.75.75h17.25a.75.75 0 00.75-.75v-1.32a.75.75 0 00-.655-.739l-.338-.067a.75.75 0 01.155-1.488l.34-.061a.75.75 0 00.635-.812 49.979 49.979 0 00-2.413-4.87 3.75 3.75 0 00-6.552 0l-.094.176a.75.75 0 01-1.342 0l-.094-.176a3.75 3.75 0 00-6.552 0z" />
                </svg>
              </div>
              <div class="degree-info">
                <h3>MSc Mathematics</h3>
                <p class="institution">ETH Zürich</p>
                <p class="duration">2020 - 2023</p>
              </div>
            </div>
            <div class="card-details">
              <p class="location">Switzerland</p>
            </div>
          </div>

          <!-- BSc -->
          <div class="education-card bsc-card">
            <div class="card-header">
              <div class="degree-icon">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                  <path d="M11.7 2.805a.75.75 0 01.6 0A60.65 60.65 0 0122.83 8.72a.75.75 0 01-.231 1.337 49.949 49.949 0 00-9.902 3.912l-.003.002-.34.18a.75.75 0 01-.707 0l-.34-.18-.003-.002a49.981 49.981 0 00-9.902-3.912.75.75 0 01-.231-1.337A60.65 60.65 0 0111.7 2.805z" />
                  <path fill-rule="evenodd" d="M12 2.25a.75.75 0 01.75.75v5.5a.75.75 0 01-1.5 0V3a.75.75 0 01.75-.75zM6.938 4.5a.75.75 0 01.75.75v2.25a.75.75 0 01-1.5 0V5.25a.75.75 0 01.75-.75zm10.125 0a.75.75 0 01.75.75v2.25a.75.75 0 01-1.5 0V5.25a.75.75 0 01.75-.75z" clip-rule="evenodd" />
                  <path d="M4.663 10.711a49.997 49.997 0 00-2.413 4.87.75.75 0 00.636.812l.34.061a.75.75 0 01.155 1.488l-.337.067a.75.75 0 00-.655.739v1.32c0 .414.336.75.75.75h17.25a.75.75 0 00.75-.75v-1.32a.75.75 0 00-.655-.739l-.338-.067a.75.75 0 01.155-1.488l.34-.061a.75.75 0 00.635-.812 49.979 49.979 0 00-2.413-4.87 3.75 3.75 0 00-6.552 0l-.094.176a.75.75 0 01-1.342 0l-.094-.176a3.75 3.75 0 00-6.552 0z" />
                </svg>
              </div>
              <div class="degree-info">
                <h3>BSc Mathematics and Physics</h3>
                <p class="institution">University of Toronto</p>
                <p class="duration">2016 - 2020</p>
              </div>
            </div>
            <div class="card-details">
              <p class="location">Canada</p>
            </div>
          </div>
        </div>
    design:
      columns: "1"
      css_class: g-gradient-to-b from-sky-100 via-white to-white dark:from-slate-800 dark:via-sky-950 dark:to-slate-950

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
