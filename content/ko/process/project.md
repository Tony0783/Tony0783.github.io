---
title: "프로젝트 소개"
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: 박태호의 프로젝트 포트폴리오
      text: |
        박태호님의 주요 프로젝트들을 소개합니다. 각 프로젝트의 상세 설명을 통해 구현한 기술들을 확인할 수 있습니다.

  - block: features
    id: project_overview
    content:
      title: 주요 프로젝트
      text: |
        박태호님이 수행한 대표적인 프로젝트들입니다.
      items:
        - name: 블로그 플랫폼 개발
          image: images/blog_platform.jpg
          description: |
            Django와 React를 사용하여 사용자 인증, 댓글 기능, 게시글 작성 등의 기능을 제공하는 블로그 플랫폼을 개발했습니다. 사용자 프로필 관리, 검색 기능, 태그 분류 기능도 구현했습니다.
        - name: 뉴스 기사 자동 크롤링
          image: images/news_crawling.jpg
          description: |
            Python의 BeautifulSoup 라이브러리를 사용하여 뉴스 웹사이트에서 기사를 자동으로 수집하고 분석하는 시스템을 구축했습니다. 수집된 데이터는 Pandas와 Matplotlib을 사용해 분석하고 시각화했습니다.
        - name: 할 일 관리 애플리케이션
          image: images/todo_app.jpg
          description: |
            Flutter를 활용하여 사용자가 할 일을 추가, 수정, 삭제할 수 있는 모바일 애플리케이션을 개발했습니다. Firebase와 연동하여 데이터를 실시간으로 관리할 수 있으며, 사용자 인증 기능도 구현되었습니다.

    design:
      layout: vertical  # 세로로 나열되도록 설정
      spacing:
        padding: ['20px', '0', '20px', '0']
---

