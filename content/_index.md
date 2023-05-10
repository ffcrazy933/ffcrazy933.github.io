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
      text: <ul>
<li>
<p><strong><em>May</em> 2023</strong>: Got two papers about LLMs accepted to the main conference of ACL 2023! <a href="/publication/uncommongen/">One</a> is about analyzing why LLMs fail to generate negative knowledge while being able to recognize them. The other is <a href="/publication/coscript/">CoScript</a>, studying how to generate plans under constraints with LLMs. See you in Toronto!</p>
</li>
<li>
<p><strong><em>Feb.</em> 2023</strong>: Presenting <a href="/publication/vence/">VENCE</a> on AAAI 2023!</p>
</li>
<li>
<p><strong><em>Nov.</em> 2022</strong>: Two papers accepted to AAAI 2023! One is <a href="/publication/vence/">VENCE</a> on correcting factual errors in texts, and the other is <a href="/publication/neon/">NEON</a> on explaining why a statement is false: both focus on solving the tasks without direct supervision. Welcome to check it out!</p>
</li>
<li>
<p><strong><em>Oct.</em> 2022</strong>: Gave a talk at MSRA.</p>
</li>
<li>
<p><strong><em>Oct.</em> 2022</strong>: I was awarded with China National Scholarship for Doctoral Students.</p>
</li>
<li>
<p><strong><em>Sept.</em> 2022</strong>: Just married💕!</p>
</li>
<li>
<p><strong><em>Sept.</em> 2022</strong>: We officially release a new version of the E-KAR dataset (v1.0 -&gt; v1.1), with a substantially improved <a href="https://huggingface.co/datasets/Jiangjie/ekar_english" target="_blank" rel="noopener">English dataset</a>! Over 600 problems and 1,000 explanation texts are manually adjusted, and we are as strict as we can! See more information at the <a href="https://ekar-leaderboard.github.io" target="_blank" rel="noopener">E-KAR project page</a>. Have fun!</p>
</li>
<li>
<p><strong><em>July</em> 2022</strong>: <a href="https://mp.weixin.qq.com/s/7RVdq4vrLO6e63dOYMMR_A" target="_blank" rel="noopener">Talk</a> titled “Right for the Right Reasons: Explainable Reasoning on Analogical Recognition and Fact Verification” (in <em>Chinese</em>).</p>
</li>
<li>
<p><strong><em>July</em> 2022</strong>: <a href="/publication/act/">ACT for NAT</a> will be presented at NAACL-HLT 2022.</p>
</li>
<li>
<p><strong><em>May</em> 2022</strong>: <a href="https://ekar-leaderboard.github.io" target="_blank" rel="noopener">E-KAR</a> will be presented at the <a href="https://csrr-workshop.github.io" target="_blank" rel="noopener">Commonsense Representation and Reasoning (CSRR) workshop</a> at ACL 2022, discussions welcomed!</p>
</li>
<li>
<p><strong><em>May</em> 2022</strong>: <a href="https://ekar-leaderboard.github.io" target="_blank" rel="noopener">E-KAR</a> will be presented at ACL 2022 (virtually) in a poster session, welcome to check it out!</p>
</li>
<li>
<p><strong><em>Apr.</em> 2022</strong>: Our paper (<a href="/publication/act/">ACT</a>) on non-autoregressive translation got accepted at NAACL-HLT 2022!</p>
</li>
<li>
<p><strong><em>Mar.</em> 2022</strong>: The <a href="https://eval.ai/web/challenges/challenge-page/1671/overview" target="_blank" rel="noopener">leaderboard</a> of <a href="https://ekar-leaderboard.github.io" target="_blank" rel="noopener">E-KAR</a> has been released at EvalAI! Welcome to participate!</p>
</li>
<li>
<p><strong><em>Mar.</em> 2022</strong>: Our work <a href="/publication/loren/">LOREN</a> received the attention of <a href="https://twitter.com/WikiResearch" target="_blank" rel="noopener">WikiResearch Team</a> 🧐, here’s <a href="https://twitter.com/WikiResearch/status/1504873884776030211" target="_blank" rel="noopener">the tweet</a>.</p>
</li>
<li>
<p><strong><em>Feb.</em> 2022</strong>: Giving oral &amp; poster presentations about <a href="/publication/loren/">LOREN</a> and <a href="/publication/educat/">EDUCAT</a> at AAAI 2022 virtual conference.</p>
</li>
<li>
<p><strong><em>Feb.</em> 2022</strong>: Our paper (<a href="https://ekar-leaderboard.github.io" target="_blank" rel="noopener">E-KAR</a>) on analogical reasoning got accepted at ACL 2022 (Findings)!</p>
</li>
</ul>
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: experience
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
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
---
