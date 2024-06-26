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
      username: ho-han-sheng
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
  - block: portfolio
    id: research-themes
    content:
      title: Publications
      subtitle: 
      text: 
      filters:
        # Folders to display content from
        folders:
          - publications
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
