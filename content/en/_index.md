---
title: "Homepage"
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: Summary
      text: |
        **Expected to graduate from Jeonbuk National University with a degree in Computer Science**  
        Languages used: **Java, C, C++, Python, JavaScript, HTML, C#**

    design:
      background_color: "#e6f7ff"
      padding: "50px"

  - block: features
    content:
      title: Introduction
      text: |
        ### Personal Information
        **Gender:** Male  
        **Age:** 22  
        **Student ID:** 2020

        ### School Information
        Currently studying at Jeonbuk National University.  
        [Jeonbuk National University Website](https://www.jbnu.ac.kr/kor/){:target="_blank"}

        ### Hobbies
        Hobbies include table tennis, skiing, and gaming.
    design:
      background_color: "#f0f8ff"
      padding: "50px"

  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Recruit</span>
        content: <span style="font-size:70%">Coding?</span>
        align: center
        background:
          image:
            filename: slider1.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text-color: '#000'
          url: contact

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">AI technology development</span>
        align: center
        background:
          image:
            filename: slider2.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Collaboration</span>
        align: center
        background:
          image:
            filename: slider3.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">University</span>
        content: <span style="font-size:70%">University</span>
        align: center
        background:
          image:
            filename: slider4.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      slide_height: '550px'
      slide_width: '100%'
      is_fullscreen: false
      loop: true
      interval: 3000

  - block: collection
    content:
      id: section-1
      title: Notifications & News
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - notification
          - post
          - event
    design:
      view: community/custom_card
      columns: '2'

  - block: collection
    content:
      title: Latest Publications
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Join team →" %}}
    design:
      columns: '1'
---
