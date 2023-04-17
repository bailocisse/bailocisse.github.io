---
# Leave the homepage title empty to use the site title
title: My personal page
date: 2023-01-01
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://coursera.org/share/bd96d1f9af82622cbbd8085514e2c9c7
          date_end: ''
          date_start: '2022-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Database Management Essentials
          url: ''
        - certificate_url: https://courses.edx.org/certificates/dc4b1c6aa5e44832a504b88e93e201ec
          date_end: ''
          date_start: '2022-08-07'
          description: ''
          organization: edX
          organization_url: https://www.edx.org
          title: AWS Cloud Practitioner Essentials
          url: ''
        - certificate_url: https://certificates.emeritus.org/fb370ef9-f647-49c6-b1c7-1bc8be0b1a90
          date_end: ''
          date_start: '2023-01-31'
          description: ''
          organization: Massachussets Institute Of Technology xPRO
          organization_url: https://xpro.mit.edu/
          title: 'Professional Certificate in Data Engineering'
          url: ''
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Data engineering
          tag: Data engineering
        - name: Data Science
          tag: Data science
    #design:
      # Choose how many columns the section has. #Valid values: '1' or '2'.
      #columns: '1'
      #view: showcase
      # For Showcase view, flip alternate rows?
      #flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: mbailocisse@gmail.com
      phone: +336 67 99 44 26
      address:
        street: 42 Rue des Meuniers
        city: Montreuil
        region: Ile-de-France
        postcode: '93100'
        country: France
        country_code: FR

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
    design:
      columns: '2'
---
