---
# Leave the homepage title empty to use the site title
title:
date: 2023-10-13
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
  - block: accomplishments
    id: news
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      # title: 'Accomplish&shy;ments'
      title: News
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      items:
        # - certificate_url: https://www.coursera.org
        #   date_end: ''
        #   date_start: '2021-01-25'
        #   description: ''
        #   organization: Coursera
        #   organization_url: https://www.coursera.org
        #   title: Neural Networks and Deep Learning
        #   url: ''
        # - date_start: "2024-09-25"
        #   organization: Cambridge Computer Laboratory
        #   organization_url: https://www.cst.cam.ac.uk/
        #   title: 🌟 Please checkout our recent work on [data augmentation for tabular data](https://arxiv.org/abs/2409.16118)
        - date_start: "2025-10-23"
          organization: Google
          organization_url: https://blog.google/outreach-initiatives/google-org/phd-fellowship-program-2025/
          title: 🎊 Awarded with ["Google PhD Fellowship"](https://blog.google/outreach-initiatives/google-org/phd-fellowship-program-2025/) in the branch of Machine Learning and ML Foundations (1st recipient of the CST at University of Cambridge)
        - date_start: "2025-02-28"
          organization: ICLR 2025
          organization_url: https://iclr.cc/
          title: 🌟 One first author [paper](https://arxiv.org/abs/2503.09453) accepted by DeLTa & SynthData@ICLR 2025, and awarded with "Early Career Scholar Award" (only 6 recipients worldwide)
        - date_start: "2024-09-25"
          organization: NeurIPS 2024
          organization_url: https://neurips.cc/
          title: 🌟 One co-first author [paper](https://arxiv.org/abs/2409.16118) accepted by NeurIPS 2024 (with an acceptance rate of 25.8%), and awarded with "NeurIPS 2024 Scholar Award"
        # - date_start: "2024-09-10"
        #   organization: Cambridge Computer Laboratory
        #   organization_url: https://www.cst.cam.ac.uk/
        #   title: 📝 I will co-supervise a Part III/MPhil project with Prof Mateja Jamnik for the upcoming academic year (2024-2025). Please checkout the [proposal](https://www.cl.cam.ac.uk/~mj201/teaching/student-projects.html) and reach out!
        # - date_start: "2024-07-23"
        #   organization: ICML 2024
        #   organization_url: https://icml.cc/
        #   title: 🌟 Please checkout our recent work on [interpretable machine learning for healthcare](https://icml.cc/virtual/2023/27785) (presented at ICML 2024 in Vienna)
        - date_start: "2024-05-02"
          organization: ICML 2024
          organization_url: https://icml.cc/
          title: 🌟 One first author [paper](https://arxiv.org/abs/2306.12330) accepted by ICML 2024 (with an acceptance rate of 27.03%)
        # - date_start: "2023-11-22"
        #   organization: NeurIPS 2023
        #   organization_url: https://sites.google.com/view/tglworkshop-2023/home
        #   title: 🌟 One [paper](https://arxiv.org/abs/2311.12255) accepted by NeurIPS 2023 workshop on Temporal Graph Learning
        - date_end: ""
          date_start: "2023-08-07"
          description: ""
          organization: University of Cambridge
          organization_url: https://www.cam.ac.uk/
          title: 🎓 Pass with Distinction for MPhil in Advanced Computer Science, and awarded with "College Prize for Academic Excellence"
    design:
      columns: "2"
      spacing:
        #   # Customize the section spacing. Order is top, right, bottom, left.
        padding: ["20px", "0", "20px", "0"]
  - block: collection
    id: publications
    content:
      title: Selected Publications & Preprints
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: "2"
      view: Citation
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
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  # design:
  #   columns: '2'
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
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
---
