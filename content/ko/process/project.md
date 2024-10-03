---
title: "Project"
date: 2024-10-04
type: landing

sections:
  - block: features
    content:
      title: 진행했던 프로젝트
      text: |
        제가 진행했던 주요 프로젝트입니다. 각 프로젝트마다 목표와 구현 과정을 간략히 설명합니다.

  # 첫 번째 프로젝트: 블로그 플랫폼 개발
  - block: features
    id: blog-platform
    content:
      title: 블로그 플랫폼 개발
      text: |
        사용자들이 블로그 포스트를 작성하고, 댓글을 달 수 있는 블로그 플랫폼을 개발했습니다. 
        **기능:** 사용자 인증, 글 작성 및 편집, 댓글 기능.  
        **주요 도전:** 실시간 댓글 기능을 구현하면서 서버와의 비동기 통신을 학습했습니다.
      items:
        - name: 사용된 기술 스택
          description: Python, Django, JavaScript, HTML/CSS

  # 두 번째 프로젝트: 뉴스 기사 자동 크롤링
  - block: features
    id: news-crawling
    content:
      title: 뉴스 기사 자동 크롤링
      text: |
        Python과 BeautifulSoup을 활용해 뉴스 기사 데이터를 자동으로 수집하고 분석하는 시스템을 구축했습니다.
        **기능:** 다양한 뉴스 사이트에서 기사 수집, 텍스트 분석 및 요약.
        **주요 도전:** 여러 사이트에서 비슷한 구조로 데이터를 추출할 수 있는 크롤러 로직을 설계하는 데 집중했습니다.
      items:
        - name: 사용된 기술 스택
          description: Python, BeautifulSoup, Pandas

  # 세 번째 프로젝트: 할 일 관리 애플리케이션
  - block: features
    id: todo-app
    content:
      title: 할 일 관리 애플리케이션
      text: |
        할 일 목록을 추가하고, 삭제하며, 완료 상태를 관리할 수 있는 애플리케이션을 개발했습니다.
        **기능:** 사용자 친화적인 UI, 할 일 추가 및 수정, 완료 상태 관리.  
        **주요 도전:** 모바일 환경에서의 최적화를 고려하며, React Native로 애플리케이션을 제작했습니다.
      items:
        - name: 사용된 기술 스택
          description: React Native, JavaScript, Node.js
---
