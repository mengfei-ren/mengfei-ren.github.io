---
# Leave the homepage title empty to use the site title
title: Mengfei Ren
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news
    content:
      title: 'News'
      text: >-
        <ul>
        <li><b>[2024-06-07]</b> I have been selected for the award of 2023/24 UAH New Faculty Research Program.</li>
        <li><b>[2024-01-11]</b> Our ESORICS paper is now published. Welcome to check details from <a href="https://doi.org/10.1007/978-3-031-51476-0_23" target="_blank">this link</a>.</li>
        <li><b>[2023-09-25]</b> Our paper "Intelligent Zigbee Protocol Fuzzing via Constraint-Field Dependency Inference" has been accepted and presented in ESORICS 2023. The official link will be available soon.</li>
        <!-- <li><b>[2023-09-05]</b> 1-2 fully funded PhD positions are opening for Spring 2024 or Fall 2024.</li> -->
        <li><b>[2023-08-08]</b> I'm happy to share that I have joined the Department of Electrical and Computer Engineering at University of Alabama in Huntsville as an Assistant Professor.</li>
        <li><b>[2023-07-10]</b> I have successfully defended my Ph.D dissertation <i>"Fuzz Testing of Zigbee Protocol Implementations"</i>.</li>
        </ul>
    design:
      columns: '2'
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: CEO
  #         company: GenCoin
  #         company_url: ''
  #         company_logo: org-gc
  #         location: California
  #         date_start: '2021-01-01'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:

  #             * Analysing
  #             * Modelling
  #             * Deploying
  #       - title: Professor of Semiconductor Physics
  #         company: University X
  #         company_url: ''
  #         company_logo: org-x
  #         location: California
  #         date_start: '2016-01-01'
  #         date_end: '2020-12-31'
  #         description: Taught electronic engineering and researched semiconductor physics.
  #   design:
  #     columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
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
      columns: '2'
      view: citation
  - block: markdown
    id: honor
    content:
      title: 'Honors & Awards'
      text: |-
        - UAH New Faculty Research Program, 2024
    design:
      columns: '2'
  - block: markdown
    id: teaching
    content:
      title: 'Teaching'
      text: |-
        **Courses at University of Alabama in Huntsville**
        - CPE 212: Fundamental of Software Engineering
        - CPE 645: Computer Network Security

        **Courses at University of Texas at Arlington**
        - CSE 4380/5380 Lab: Information Secuirty I 
    design:
      columns: '2'
  - block: markdown
    id: service
    content:
      title: 'Services'
      text: |-
        **Technical Program Committee**
        - [SoutheastCon] IEEE SourtheastCon: 2024
        - [JSS] The Journal of Systems & Software
        
        **External Reviewers**
        - [USENIX Sec] USENIX Security Symposium: 2021 - 2023
        - [ASE] IEEE/ACM International Conference on Automated Software Engineering: 2020
        - [CCS] ACM Conference on Computer and Communication Secuirty: 2019 - 2020
        - [ICICS] International Conference on Information and Communication Secuirty: 2019 - 2021
        - [TDSC] IEEE Journal of Transactions on Dependable and Secure Computing: 2020
        - [TSE] IEEE Journal of Transactions on Software Engineering: 2022
    design:
      columns: '2'
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: mengfei[dot]ren[at]uah[dot]edu
      # phone: 
      # appointment_url: 
      address:
        street: Engineering Building Room 217-D, 
                301 Spartkman Drive
        city: Huntsville
        region: AL
        postcode: '35899'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
      office_hours: Tuesday and Thursday 10:00 - 11:00 AM and email for appointment
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
