---
title: "About 박태호"
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 박태호의 포트폴리오
      text: |
        박태호의 개인 포트폴리오입니다. 이 포트폴리오에서는 지금까지 진행했던 프로젝트, 자기소개, 학습 과정, 목표 등을 다룰 예정입니다.

  - block: slider
    content:
      slides:
      - title: 프로젝트
        content: 박태호의 주요 프로젝트들을 확인하세요.
        align: center
        background:
          color: '#333'
      - title: 학습 과정
        content: 다양한 학습 과정을 소개합니다.
        align: center
        background:
          color: '#666'
      - title: 목표 및 계획
        content: 박태호의 미래 계획을 확인해 보세요.
        align: center
        background:
          color: '#555'
    design:
      slide_height: '350px'
      slide_width: '50%'
      loop: true
      interval: 3000

  - block: features
    id: features
    content:
      title: 포트폴리오의 구성
      text: 박태호님의 포트폴리오는 다음과 같은 항목들로 구성되어 있습니다.<br><br><br><br>
      items:
        - name: 프로젝트
          icon: code
          description: 다양한 웹 개발 프로젝트와 AI 프로젝트를 소개합니다.
        - name: 학습 과정
          icon: book-open
          description: 프로그래밍 언어, 데이터 분석, AI 관련 학습 과정에 대해 다룹니다.
        - name: 목표
          icon: target
          description: 박태호님의 앞으로의 계획과 목표를 확인하세요.

  - block: collection
    content:
      title: 주요 프로젝트
      text: |
        박태호님이 지금까지 진행했던 프로젝트 목록입니다.
      count: 3
      filters:
        author: ''
        category: 'projects'
        exclude_featured: false
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '3'

  - block: markdown
    content:
      title: 더 알아보기
      text: |
        <p>더 많은 정보는 아래 링크를 통해 확인해 보세요.</p>
        {{% cta cta_link="./projects/" cta_text="프로젝트 보러 가기 →" %}}
    design:
      columns: '1'

---
