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
      title: News
      text:"
      + ***May*** **2023**:Two papers accepted to ACL 2023! One is **Coscript** on constraint language planning, and the other is **KPCE** on concept extraction through the lens of a Structural Causal Model.  
        + sdf
      + ***Oct.*** **2022**:Our work **Generative Entity Typing with Curriculum Learning** got accepted at EMNLP 2022!  
        + asdf
      + ***Sept.*** **2022**:Our work **Contextual Information and Commonsense Based Prompt for Emotion Recognition in Conversation** has been reported in the ECML PKDD 2022 online!"
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: accomplishments
    id: awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2022-05-25'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: Outstanding Academic Scholarship for Master’s Students
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2021-05-25'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: Outstanding Academic Scholarship for Master’s Students
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2022-03-25'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: Outstanding Graduate Student of Shanghai Colleges and University
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2020-05-25'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: Outstanding Student pacemaker of Fudan University
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2020-03-25'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: First-Class Academic Scholarship of Fudan University
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2019-05-25'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: National Encouragement Scholarship
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2018-05-25'
          description: ''
          organization: Fudan University
          organization_url: ''
          title: China National Scholarship
    design:
      columns: '2'
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
    id: recent
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: CEO
          company: GenCoin
          company_url: ''
          company_logo: org-gc
          location: California
          date_start: '2021-01-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Professor of Semiconductor Physics
          company: University X
          company_url: ''
          company_logo: org-x
          location: California
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
---
