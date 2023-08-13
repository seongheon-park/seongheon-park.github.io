---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    

  - block: markdown
    id: news
    content:
      title: Recent News
      text: One paper is accepted by ICCV 2023!
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

  - block: experience
    content:
      title: Research Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Researcher
          company: Machine Learning Lab., Yonsei University
          company_url: 'https://ml.yonsei.ac.kr/'
          company_logo: yonsei
          location: Seoul
          date_start: '2023-09-01'
          date_end: ''
          description: |2-
              Research topics include:

              * Open-World Learning, Out-of-Distribution Detection
              * (Self-Supervised) Representation Learning
              * Long-Tailed Learning
              * Learning with Limited Labeled Data
    
        - title: Research Assistant 
          company: Digital Image Media Lab., Yonsei University
          company_url: 'https://diml.yonsei.ac.kr/'
          company_logo: yonsei
          location: Seoul
          date_start: '2021-09-01'
          date_end: '2023-08-31'
          description: |2-
              Research topics include:
              * Open-World Learning, Out-of-Distribution Detection
              * Image/Video Anomaly Detection
              * Vision-Language Models
              * Cross-Domain Person Re-Identification
              * Learning with Limited Labeled Data

        - title: Undergraduate Research Assistant 
          company: Digital Image Media Lab., Yonsei University
          company_url: 'https://diml.yonsei.ac.kr/'
          company_logo: yonsei
          location: Seoul
          date_start: '2021-01-01'
          date_end: '2021-08-31'
          description: |2-
              Research topics include:

              * Image and Video Understanding
              * Human-Object Interaction Detection


    design:
      columns: '2'
    
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
 
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
 
 
 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please feel free to contact me!
      # Contact (add or remove contact options as necessary)
      email: sam121796@yonsei.ac.kr
      phone: (82-10) 8221-9574
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: Contact Me
          link: 'https://www.linkedin.com/in/seongheon-‍park-4948291b5'

      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
