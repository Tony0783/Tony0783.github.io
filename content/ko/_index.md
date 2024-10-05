---
title: "전북대 박태호"
date: 2024-03-25
type: page
featured_image: "/images/kakao.jpg"

sections:

  # 요약 섹션
  - block: features
    content:
      text: |
        **전북대학교 컴퓨터공학과 졸업 예정**  
        사용 언어: **Java, C, C++, Python, JavaScript, HTML, C#**
    design:
      background_color: "#e6f7ff"
      padding: "50px"

    # 개인 정보 카드 섹션
  - block: features
    content:
      title: 개인 정보
      items:
        - name: "개인 정보"
          description: |
            **성별:** 남성  
            **나이:** 23  
            **학번:** 2020
        - name: "학교 정보"
          description: |
            전북대학교에서 공부 중입니다.  
            [전북대학교 웹사이트](https://www.jbnu.ac.kr/kor/)
        - name: "취미"
          description: |
            취미는 탁구, 스키, 게임입니다.
    design:
      view: custom_compact_card
      columns: '3'



  # 이미지 슬라이더 섹션
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
        content: <span style="font-size:70%">AI 기술 개발</span>
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

  # 학습 내용 카드 섹션
  - block: features
    content:
      title: 현재 학습 중인 내용
      items:
        - name: "웹 서비스 설계"
          description: "웹 서비스의 구조와 설계, 시스템 아키텍처에 대해 학습 중입니다."
        - name: "컴퓨터 그래픽스"
          description: "컴퓨터 그래픽스의 이론과 3D 모델링, 렌더링 기법을 배우고 있습니다."
        - name: "소프트웨어 공학"
          description: "소프트웨어 개발 프로세스와 유지보수, 프로젝트 관리 방법론을 학습 중입니다."
        - name: "정보 검색"
          description: "효율적인 정보 검색 시스템 설계와 관련 알고리즘에 대해 배우고 있습니다."
      title: 인공지능 논문
      text: |
        인공지능에 대해 더 알고싶다면 [여기](https://ettrends.etri.re.kr/ettrends/185/0905185011/35-5_123-133.pdf) 를 클릭하세요. 
    design:
      background_color: "#ffffff"
      padding: "50px"
      layout: list
      list_layout: vertical
  

  # 진행할 내용 (collection 섹션 수정)
  - block: collection
    content:
      id: site_content
      title: 사이트 내용
      items:
        - name: "사이트 개요"
          description: "사이트의 주요 내용과 기능들을 설명합니다."
        - name: "학습 내용"
          description: "현재 학습 중인 과정과 관련된 자료를 정리합니다."
    design:
      view: custom_card
      columns: '2'
      background_color: "#e6f7ff"
      padding: "50px"
      layout: list
      list_layout: vertical

---
