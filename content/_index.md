---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
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
        - title: Full Stack Web Developer
          company: DXC Technology
          company_url: ''
          company_logo: ''
          location: 'Bitritto, Bari, Italy'
          date_start: '2020-09-23'
          date_end: '2021-09-30'
          description: |2-
              Responsibilities include:

              * Analysing
              * Developing
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      # Contact (add or remove contact options as necessary)
      email: roberto.barile@uniba.it
      phone:
      appointment_url:
      address:
        street: Via Edoardo Orabona
        city: Bari
        region: BA
        postcode: '70056'
        country: Italy
        country_code: It
      directions: Dipartimento di Informatica, 4th floor, LACAM
      office_hours:
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
