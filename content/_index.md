---
title:
date: 2022-10-24
type: landing

sections:
  - block: hero 
    content:
      title: Theory of Computer Science 
      text: |
        <br>

        The **Theory of Computer Science (TCS) Group** does research on the theoretical foundations of computer science. The aim is to seek greater understanding of fundamental computational techniques and their inherent limitations.
        The TCS group forms an integral part of a [vibrant community of TCS researchers in Amsterdam](https://theory.amsterdam).

  - block: markdown
    id: open_positions
    design:
      columns: '1'
    content:
      title: Open Positions
      subtitle:
      text: |
        ## Open positions:
        * [Assistant Professor in Cyber Security](project/cics_ud_chris)
  - block: collection
    id: news    
    content:
      title: Latest News
      subtitle:

      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: showcase
      columns: '1'
  
  - block: hero
    design:
      columns: '1'
    content:
      title: TCS group pre 2022
      text: |
        The TCS group has a history of developing theory and tools in the field of algebraic specification which can be used to specify, analyse, and verify concurrent communicating and programmed systems. [This link](https://ivi.fnwi.uva.nl/tcs/index_old.html) leads you back to the old group homepage, including [publications from 1997-2018 and technical reports](https://ivi.fnwi.uva.nl/tcs/publications.php) as well as [software](https://ivi.fnwi.uva.nl/tcs/software.html).

  - block: people
    id: people
    content:
      title: Team
      subtitle:
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Group Chair
        - Scientific Staff
        - Postdocs
        - PhD Students
        - Guests
        - Support
        - Alumni
      sort_by: Params.lastname
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true        
  - block: hero
    design:
      columns: '1'
    content:
      title: TCS group pre 2022
      text: |
        The TCS group has a history of developing theory and tools in the field of algebraic specification which can be used to specify, analyse, and verify concurrent communicating and programmed systems. [This link](https://ivi.fnwi.uva.nl/tcs/index_old.html) leads you back to the old group homepage, including [publications from 1997-2018 and technical reports](https://ivi.fnwi.uva.nl/tcs/publications.php) as well as [software](https://ivi.fnwi.uva.nl/tcs/software.html).

  - block: collection
    id: projects
    content:
      title: Projects
      subtitle:

      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: project
    design:
      view: compact
      columns: '2'
      flip_alt_rows: false
  
  - block: contact
    id: contact
    content:
      # Contact (edit or remove options as required)
      title: Contact
      subtitle:

      email: c.schaffner@uva.nl
      #phone: 888 888 88 88
      address:
        street: LAB42, Science Park 900, 1098XH Amsterdam, The Netherlands
        # city: Amsterdam
        # region: NH
        # postcode: '1098 XH'
        country: Netherlands
        country_code: NL
      coordinates:
        latitude: '52.3548'
        longitude: '4.9545'
      directions: 'https://ivi.uva.nl/contact/directions/directions.html'
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'

      # Automatically link email and phone or display as text?
      autolink: true

      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false

    design:
      columns: '1'
---
