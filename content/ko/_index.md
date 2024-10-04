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

        ### 프로젝트 경험
        - 블로그 플랫폼 개발: 댓글 기능, 검색 기능, 사용자 프로필 등록 기능 구현
        - 할 일 목록 앱 개발: 작업 추가, 삭제, 편집 기능 구현
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
        content: <span style="font-size:70%">코딩?</span>
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
          text: <span style="font-size:60%">Join Us</span>
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
      slide_height: '350px'
      slide_width: '100%'
      is_fullscreen: false
      loop: true
      interval: 3000
        


  - block: collection
    content:
      title: 교육 및 학습 과정
      subtitle: 주요 학습 과정을 소개합니다.
      count: 3
      filters:
        folders:
          - education
      design:
        view: card
        columns: '3'

  - block: collection
    content:
      title: 프로젝트
      subtitle: 주요 프로젝트를 소개합니다.
      count: 3
      filters:
        folders:
          - projects
      design:
        view: card
        columns: '3'
---
