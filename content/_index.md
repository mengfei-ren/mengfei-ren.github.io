---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-02-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '🧑‍🎓 Prospective Students'
      subtitle: ''
      text: |-
        I am continuously seeking proactive Ph.D. candidates interested in advancing research in Software Testing. Prospective candidates should possess a strong foundation in computer science or software engineering, with a focus on program analysis, testing, operating systems, and proficient programming skills (C, C++, Python, Java). If this opportunity aligns with your interests, please reach out to me. See current openings in [here](opening/).
    design:
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
      text: |-
        [See All Publications >>](./publication)
    design:
      columns: 2
      view: citation
  - block: markdown
    id: teaching
    content:
      title: Teaching & Services
      text: |-
        #### Teaching Courses
        - [Baylor] CSI 3373: Software Assurance and Testing
        - [UAH] CPE 212: Fundamental of Software Engineering
        - [UAH] CPE 645/CS 685: Applied Cryptography
        - [UTA] CSE 4380/5380 Lab: Information Secuirty I 

        #### Professional Services
        *Technical Program Committee*
        - [SoutheastCon] IEEE SourtheastCon: 2024, 2025
        - [JSS] The Journal of Systems & Software   
    design:
      columns: 1
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        ✉ **Email:** Mengfei_Ren[AT]baylor[dot]edu
        📫 **Address:** Department of Computer Science, One Bear Place #97141, Waco, TX 76798-7141

    design:
      columns: 1
---
