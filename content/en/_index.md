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

  - block: collection
    content:
      id: section-1 
      count: 6
      offset: 0
      order: desc
      filters:
        folders:
          - 개인정보
          - 학교
          - 목표
    design:
      view: community/custom_card
      columns: '1'

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


  - block: collection
    content:
      id: section-2 
      count: 6
      offset: 0
      order: desc
      filters:
        folders:
          - graphic
          - software
          - service
    design:
      view: community/custom_card
      columns: '1'


  - block: collection
    content:
      id: section-3
      count: 6
      offset: 0
      order: desc
      filters:
        folders:
          - running
          - ski
          - game
    design:
      view: community/custom_card
      columns: '1'

---
