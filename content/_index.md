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
  - block: accomplishments
    id: awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: 2006
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
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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
      view: compact
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
    content:
      title: Recent Publications
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
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
---
