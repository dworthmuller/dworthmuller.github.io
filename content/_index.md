---
# Leave the homepage title empty to use the site title
title: Dennis Wörthmüller
date: 2023-02-01
type: landing

sections:
  # - block: about.avatar
  # - block: v1/about
  - block: v1/about-custom
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
      button:
        url: uploads/resume_dw.pdf  
    design:
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: cytoskeleton.jpg
          filters:
            brightness: 1
          size: cover
          position: center
          parallax: false
      spacing:
        padding: ["2%", "5%", "20px", "2%"] # section spacing top, right, bottom, left
  - block: custom/research_section
    id: research
    content:
      title: Research
    design:
      columns: '2'
      spacing:
        padding: ["20px", "5%", "20px", "2%"]
  # PUBLICATIONS v1 (without featured publications section)  
  - block: collection
    id: publications
    content:
      title: Publications
      # text: <h2><b><u>All Publications</u>:</b><br><a href="./publication/" _target="_blank">View / filter all 34 academic publications</a></h2><br>
      #   <h2><b><u>Latest Publications</u>:</b></h2>
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
      spacing:
        padding: ["20px", "5%", "20px", "2%"] # section spacing top, right, bottom, left
  # # PUBLICATIONS v2 (with featured publications section)  
  # - block: custom/collection-custom_publications
  #   id: publications
  #   # --- block part 1 = ALL + FEATURED publications
  #   content1:
  #     title: Publications
  #     text: <h2><b><u>All Publications</u>:</b><br><a href="./publication/" _target="_blank">View / filter all 34 academic publications</a></h2><br>
  #       <h2><b><u>Featured Publications (top 5)</u>:</b></h2>
  #     count: 1  #>> select how many publications to display
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true #>> select only publications where "featured: true"
  #   design1:
  #     view: custom/citation-publication-featured #>> use custom view where icon is changed to star
  #   # --- block part 2 = LATEST publications
  #   content2:
  #     text: <br><h2><b><u>Latest Publications (last 5)</u>:</b></h2>
  #     count: 5  #>> select how many publications to display
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: false
  #   design2:
  #     view: citation #>> use default "citation" style
  #   design:
  #     columns: '2'
  #     view: citation
  #     spacing:
  #       padding: ["20px", "5%", "20px", "2%"] #>> block spacing top, right, bottom, left
  #   --- customize the "See All" link: 
  #   content:
  #     archive:
  #       enable: true
  #       text: See all blog posts
  #       link: post/

  - block: collection
    id: talks
    content:
      title: Talks
      # text: <h2><b><u>All Talks</u>:</b><br><a href="./talk/" _target="_blank">View all talks/posters</a></h2><h2><b><u>Latest Talks</u>:</b></h2>
      filters:
        folders:
          - talk
    design:
      columns: '2'
      view: custom/citation-talk
      spacing:
        padding: ["20px", "5%", "20px", "2%"] # section spacing top, right, bottom, left
  - block: collection
    id: conferences
    content:
      title: Conferences
      # text: <h2><b><u>All Talks</u>:</b><br><a href="./talk/" _target="_blank">View all talks/posters</a></h2><h2><b><u>Latest Talks</u>:</b></h2>
      filters:
        folders:
          - conferences
    design:
      columns: '2'
      view: custom/citation-conference
      spacing:
        padding: ["20px", "5%", "20px", "2%"] # section spacing top, right, bottom, left
  # - block: collection
  #   id: lectures
  #   content:
  #     title: Lectures
  #     subtitle: ''
  #     text: ''
  #     count: 0  # how many pages to display (0 = all pages)
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - lectures
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  #     spacing:
  #       padding: ["20px", "5%", "20px", "2%"] # section spacing top, right, bottom, left

  # - block: collection
  #   id: projects
  #   content:
  #     title: Funded projects
  #     subtitle: ''
  #     text: ''
  #     count: 0  # how many pages to display (0 = all pages)
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - projects
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     # view: custom/compact
  #     view: custom/compact-project
  #     columns: '2'
  #     spacing:
  #       padding: ["20px", "5%", "20px", "2%"] # section spacing top, right, bottom, left
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      email: dennis.worthmuller@curie.fr
      address:
        street: Institut Curie, UMR168 Physics of Cells and Cancer
        city: Paris
        region: 
        postcode: '75005'
        country: France
        country_code: FR
      contact_links:
        - icon: globe
          name: Institut Curie
          link: 'https://institut-curie.org/unit/umr168/'
      autolink: true  # Automatically link email and phone or display as text?
    design:
      columns: '2'
      spacing:
        # NB: leave bottom spacing after last section, so that menu section higlight works
        padding: ["20px", "5%", "250px", "2%"] #section spacing top, right, bottom, left
---
