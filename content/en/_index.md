---
title: "Homepage"
date: 2024-03-25
type: landing
featured_image: "/images/kakao.jpg"
description: "전북대학교 박태호 포트폴리오"
opengraphImage: "https://tony0783.github.io/images/kakao.jpg"

sections:

  # Summary Section
  - block: features
    content:
      text: |
        **Expected to graduate from Chonbuk National University with a major in Computer Science**  
        Languages used: **Java, C, C++, Python, JavaScript, HTML, C#**
    design:
      background_color: "#e6f7ff"
      padding: "50px"

  # Personal Information Card Section
  - block: features
    content:
      title: Personal Information
      items:
        - name: "Personal Info"
          description: |
            **Gender:** Male  
            **Age:** 23  
            **Student ID:** 2020
        - name: "School Information"
          description: |
            Studying at Chonbuk National University.  
            [Chonbuk National University Website](https://www.jbnu.ac.kr/kor/)
        - name: "Hobbies"
          description: |
            Hobbies include table tennis, skiing, and gaming.
    design:
      view: custom_compact_card
      columns: '3'

  # Image Slider Section
  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">Recruit</span>
        content: <span style="font-size:70%">Coding</span>
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
        content: <span style="font-size:70%">AI Technology Development</span>
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

  # Learning Content Card Section
  - block: features
    content:
      title: Current Learning Content
      items:
        - name: "Web Service Design"
          description: "Studying the structure and design of web services, including system architecture."
        - name: "Computer Graphics"
          description: "Learning about the theory of computer graphics, including 3D modeling and rendering techniques."
        - name: "Software Engineering"
          description: "Studying software development processes, maintenance, and project management methodologies."
        - name: "Information Retrieval"
          description: "Learning about designing efficient information retrieval systems and related algorithms."
    design:
      background_color: "#ffffff"
      padding: "50px"
      layout: list
      list_layout: vertical

  # Site Content Section (collection section)
  - block: collection
    content:
      id: site_content
      title: Site Content
      items:
        - name: "Site Overview"
          description: "Describes the main content and features of the site."
        - name: "Learning Content"
          description: "Summarizes materials related to the current learning process."
    design:
      view: custom_card
      columns: '2'
      background_color: "#e6f7ff"
      padding: "50px"
      layout: list
      list_layout: vertical

---
