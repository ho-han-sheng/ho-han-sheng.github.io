---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hello!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
        - title: Research Assistant
          company: School of Humanities and Behavioural Sciences, Singapore University of Social Sciences
          company_url: 'https://www.suss.edu.sg/about-suss/schools/shbs'
          company_logo: 
          location: 
          date_start: '2023-10-23'
          date_end: 
          description:
        - title: Research Intern
          company: 'Multimodal Neuroimaging in Neuropsychiatric Disorders Laboratory, Center for Sleep and Cognition, Yong Loo Lin School of Medicine, National University of Singapore'
          company_url: 'https://neuroimaginglab.org'
          company_logo: 
          location: 
          date_start: '2023-01-25'
          date_end: '2023-07-14'
          description: |2-

              * Wrote Python and R scripts for data cleaning, exploratory data analysis, and mixture modelling of multimodal data.
              * Conducted qualitative interviews for stimulus recall tasks
              * Scoring of neurocognitive batteries
        - title: Peer Mentor
          company: School of Science and Technology, Singapore University of Social Sciences
          company_url: 'https://www.suss.edu.sg/about-suss/schools/sst'
          company_logo: 
          location: 
          date_start: '2022-01-01'
          date_end: '2022-12-31'
          description: |2-
              Conducted weekly tutorials for:

              * MTH219 Fundamentals of Statistics and Probability
              * MTH220 Statistical Methods and Inference
    design:
      columns: '2'
---
