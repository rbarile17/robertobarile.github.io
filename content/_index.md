---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: 2
  - block: talks
    id: talks
    content:
      title: Recent & Upcoming Talks
      subtitle: ''
  - block: community_service
    id: community_service
    content:
      title: 'Community Service'
      subtitle: ''
---
