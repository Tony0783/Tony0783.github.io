---
title: "Homepage"
date: 2024-03-25
type: landing

sections:

  # Summary Section
  - block: features
    content:
      title: Summary
      text: |
        **Expected to graduate from Jeonbuk National University with a degree in Computer Science**  
        Languages used: **Java, C, C++, Python, JavaScript, HTML, C#**
    design:
      background_color: "#e6f7ff"
      padding: "50px"

  # Personal Information Card Section
  - block: features
    content:
      title: Personal Information
      items:
        - name: "Personal Information"
          description: |
            **Gender:** Male  
            **Age:** 23  
            **Student ID:** 2020
        - name: "School Information"
          description: |
            Currently studying at Jeonbuk National University.  
            [Jeonbuk National University Website](https://www.jbnu.ac.kr/kor/)
        - name: "Hobbies"
          description: |
            Hobbies include table tennis, skiing, and gaming.
    design:
      background_color: "#f0f8ff"
      padding: "50px"
      layout: list
      list_layout: vertical

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

  # Learning Content Card Section
  - block: features
    content:
      title: Current Learning Topics
      items:
        - name: "Web Service Design"
          description: "Studying the structure and design of web services, as well as system architecture."
        - name: "Computer Graphics"
          description: "Learning about computer graphics theory, including 3D modeling and rendering techniques."
        - name: "Software Engineering"
          description: "Studying software development processes, maintenance, and project management methodologies."
        - name: "Information Retrieval"
          description: "Learning about the design of efficient information retrieval systems and related algorithms."
    design:
      background_color: "#ffffff"
      padding: "50px"
      layout: list
      list_layout: vertical

  # Completed Projects Card Section
  - block: features
    content:
      title: Completed Projects
      items:
        - name: "Blog Platform Development"
          description: "Developed a blog platform using Django and React, including features like comments, user authentication, etc."
        - name: "To-Do Management Application"
          description: "Developed a mobile application using Flutter for managing to-do lists."
        - name: "News Article Auto Crawling"
          description: "Developed a system using Python and BeautifulSoup to automatically collect and analyze news articles."
    design:
      background_color: "#f8f8ff"
      padding: "50px"
      layout: list
      list_layout: vertical

---
