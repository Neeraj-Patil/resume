---
title: 'Home'
date: 2023-10-24
type: landing

sections:

  # HERO / BIOGRAPHY
  - block: biography
    content:
      username: me

      button:
        text: Download Resume
        url: uploads/Neeraj_Patil_Resume.pdf

    design:
      show_status: false

      spacing:
        padding: ['0', '0', '5rem', '0']

      banner:
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg

      biography:
        style: 'text-align: justify; font-size: 0.95rem; line-height: 1.8;'

      avatar:
        size: large
        shape: rounded

  # EXPERIENCE
  - block: experience
    content:
      title: Professional Experience
      username: me

    design:
      date_format: 'January 2006'
      is_education_first: false

  # PROJECTS
  - block: collection
    id: projects
    content:
      title: Featured Projects
      text: >
        A collection of analytics, automation, ERP, and business intelligence projects focused on solving operational and business challenges through data-driven solutions.

      filters:
        folders:
          - project

      count: 6

      sort_by: 'date'
      sort_ascending: false

    design:
      view: article-grid
      columns: '2'

  # SKILLS
  - block: skills
    content:
      title: Technical Skills
      username: me

  # ACHIEVEMENTS / AWARDS
  - block: awards
    content:
      title: Achievements & Leadership
      username: me

  # OPTIONAL LANGUAGES
  - block: languages
    content:
      title: Languages
      username: me
---
