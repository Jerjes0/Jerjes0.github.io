---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: news
    content:
      title: News
      filters:
        folders:
          - news
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      view: compact
      columns: '2'

  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Student Researcher
          company: Halıcıoğlu Data Science Institute, University of California San Diego
          company_url: 'https://datascience.ucsd.edu/'
          # company_logo: climate_ai.png
          location: La Jolla, CA
          date_start: '2024-09-23'
          date_end: 
          description: |2-

              * Developing vision-language models to detect and interpret findings in radiology imaging, with the AiDA Lab (Prof. Albert Hsiao).
              * Building vision-language models for scientific discovery from neuroscience literature, with the Voytek Lab (Prof. Bradley Voytek).
              * Focusing on clinical alignment and workflow enhancement to make these models practical for real diagnostic and research settings.

        - title: Data Scientist II
          company: ClimateAi
          company_url: 'https://climate.ai/'
          # company_logo: climate_ai.png
          location: Remote
          date_start: '2024-02-01'
          date_end: '2024-09-15'
          description: |2-

              * Designed custom dashboards for clients tracking wildfire, hurricane, and agronomic risk.
              * Built algorithms to aggregate climate projection data for hydrological basins, improving data accuracy and usability.
              * Wrote climate risk analysis report guidelines that gave stakeholders clear, actionable insights for decision-making.

        - title: Data Scientist I
          company: ClimateAi
          company_url: 'https://climate.ai/'
          # company_logo: climate_ai.png
          location: Remote
          date_start: '2023-01-09'
          date_end: '2024-02-01'
          description: |2-

              * Built client-specific datasets to assess climate risks such as pests, disease, sunshine hours, and heat stress.
              * Migrated and adapted the codebase from Google Cloud to Amazon Web Services with no disruption to service.
              * Developed algorithms to post-process high-resolution global climate projection variables, improving compute efficiency.

        - title: Software Engineer
          company: Deal Engine
          company_url: 'https://deal-engine.com/'
          # company_logo: deal_engine
          location: Remote
          date_start: '2022-08-01'
          date_end: '2023-01-09'
          description: |2-

              * Built NLP algorithms to infer tax rules across different countries and airlines.
              * Managed source control with Git to keep the codebase reliable across a collaborative team.
              * Built and maintained SQL databases for accurate, available tax data.

    design:
      columns: '2'

  - block: collection
    id: publications
    content:
      title: Selected Publications
      text: |-
        <p style="margin-bottom: 1.5rem;">For the complete list of publications, see my <a href="https://scholar.google.com/citations?view_op=list_works&hl=en&user=VqAQKv0AAAAJ">Google Scholar profile</a>.</p>
      filters:
        folders:
          - publication
        featured_only: true
      order: desc
    design:
      columns: '2'
      view: citation

  - block: markdown
    id: gallery
    content:
      title: "Photo Gallery"
      subtitle: ""
      text: |-
        I've always liked taking pictures of sunsets, flowers and the sea. Recently I decided to try to up my game, and here you can see a little of the pictures I've taken so far. Not an expert at all, but I do love taking pictures of pretty things.

        <p style="text-align: center;">
          <a href="/gallery"><strong>See the full gallery</strong></a>
        </p>

        <p style="text-align: center;">
          <img src="/uploads/main.JPG"
              alt="Preview Image"
              style="max-width: 50%; height: auto; display: block; margin: 0 auto;" />
        </p>
    design:
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ""
      text: |-
        Hi there! I'm always excited to chat about research, collaborations, or talk about grad school in general. Whatever's on your mind, feel free to drop me a line— I'm here to help and share ideas.
      email: jaguirrechavez@ucsd.edu
      # phone: 619 3757 052
      # appointment_url: 'https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0KmNCBN-RhgGyNkHLTTEbYEmUJlanx8KaH830_nH4wo_2utSdGcA9HKmviW9LdbDcNAmYxjQSo'
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: Linkedin
          link: 'https://www.linkedin.com/in/jerjesaguirre/'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
