---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-02-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"

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
          filename: UAH.jpg
          filters:
            brightness: 0.3
          size: cover
          position: center
          parallax: true
  - block: markdown
    content:
      title: '🧑‍🎓 Prospective Students'
      subtitle: ''
      text: |-
        I am continuously seeking proactive Ph.D. candidates interested in advancing research in Software Testing and IoT Security. Prospective candidates should possess a strong foundation in computer science or cybersecurity, with a focus on software testing, operating systems, and proficient programming skills (C, C++, Python, Java). If this opportunity aligns with your interests, please reach out to me. See current openings in [here](opening/).
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
  - block: markdown
    id: honors
    content:
      title: Honors & Rewards
      text: |-
        🏆 UAH New Faculty Research Award, 2024

        🏆 UT Arlington Summer Dissertation Fellowship, 2023
        
        🎀 USENIX Security Symposium Diversity Grant, 2022
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
        ✉ Email: mengfei[dot]ren[AT]uah[dot]edu
        📫 Address: Engineering Building RM272, 301 Sparkman Drive, Huntsville, AL, 35899
        📅 Office Hours: Monday & Wednesday 2:30 - 3:30 PM
    design:
      columns: 1
---
