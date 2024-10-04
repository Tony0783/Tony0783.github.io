---
title: "홈페이지"
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 요약
      text: |
        **전북대학교 컴퓨터공학과 졸업 예정**  
        사용 언어: **Java, C, C++, Python, JavaScript, HTML, C#**
    design:
      background_color: "#e6f7ff"
      padding: "50px"

  - block: features
    content:
      title: 소개
      text: |
        ### 개인 정보
        **성별:** 남성  
        **나이:** 22  
        **학번:** 2020

        ### 학교 정보
        현재 전북대학교에서 공부 중입니다.  
        [전북대학교 웹사이트](https://www.jbnu.ac.kr/kor/){:target="_blank"}

        ### 취미
        취미는 탁구, 스키, 게임입니다.
    design:
      background_color: "#f0f8ff"
      padding: "50px"

  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">Recruit</span>
        content: <span style="font-size:70%">코딩</span>
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
        content: <span style="font-size:70%">AI 기술 개발<span style="font-size:70%">
        align: center
        background:
          image:
            filename: slider2.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">협동</span>
        align: center
        background:
          image:
            filename: slider3.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">학교</span>
        content: <span style="font-size:70%">대학교</span>
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
      
    # Partial 호출
    text: |
      {{ range .Items }}
        {{ partial "card.html" (dict "title" .Title "description" .Summary "link" .RelPermalink) }}
      {{ end }}

  - block: collection
    content:
      title: Latest Publications
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

  - block: markdown
    content:
      title: Contact
      subtitle: Join Us
      text: |
        {{% cta cta_link="./contact/" cta_text="Join team →" %}}
    design:
      columns: '1'
---
