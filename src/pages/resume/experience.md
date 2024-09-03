---
layout: '@/templates/BasePost.astro'
title: Experience
description: Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi.
pubDate: 2020-02-03T00:00:00Z
imgSrc: '/assets/images/image-post4.jpeg'
imgAlt: 'Image post 4'
tag: ["helm"]
---

# Experiences.

#   Add/remove as many `experience` items below as you like.

#   Required fields are `title`, `company`, and `date_start`.

#   Leave `date_end` empty if it's your current employer.

#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
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

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: MEng Electronic Engineering
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2021-01-01'
    date_end: '2022-01-01'
    description: |2-
        * Dissertation on Y
        * Basketball team
        * DJ club

  - title: BEng Electronic Engineering
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: My dissertation was on X

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization`, and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
item:
  - certificate_url: https://www.coursera.org
    date_end: ''
    date_start: '2021-01-25'
    description: ''
    organization: Coursera
    organization_url: https://www.coursera.org
    title: Neural Networks and Deep Learning
    url: ''
  - certificate_url: https://www.edx.org
    date_end: ''
    date_start: '2021-01-01'
    description: Formulated informed blockchain models, hypotheses, and use cases.
    organization: edX
    organization_url: https://www.edx.org
    title: Blockchain Fundamentals
    url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  - certificate_url: https://www.datacamp.com
    date_end: '2020-12-21'
    date_start: '2020-07-01'
    description: ''
    organization: DataCamp
    organization_url: https://www.datacamp.com
    title: 'Object-Oriented Programming in R'
    url: ''


title: Get in touch
subtitle:

content:
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
