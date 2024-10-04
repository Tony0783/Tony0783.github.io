---
title: "포트폴리오 소개"
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: 박태호의 포트폴리오
      text: |
        박태호의 개인 포트폴리오입니다. 이 포트폴리오에서는 지금까지 진행했던 프로젝트들을 소개합니다.

  - block: features
    id: project_list
    content:
      title: 프로젝트 리스트
      items:
        - name: 블로그 플랫폼 개발
          description: |
            Django와 React를 사용하여 사용자 인증, 댓글 기능, 게시글 작성 등의 기능을 제공하는 블로그 플랫폼을 개발했습니다. 사용자 프로필 관리, 검색 기능, 태그 분류 기능도 구현했습니다.
        - name: 뉴스 기사 자동 크롤링
          description: |
            Python의 BeautifulSoup 라이브러리를 사용하여 뉴스 웹사이트에서 기사를 자동으로 수집하고 분석하는 시스템을 구축했습니다. 수집된 데이터는 Pandas와 Matplotlib을 사용해 분석하고 시각화했습니다.
        - name: 할 일 관리 애플리케이션
          description: |
            Flutter를 활용하여 사용자가 할 일을 추가, 수정, 삭제할 수 있는 모바일 애플리케이션을 개발했습니다. Firebase와 연동하여 데이터를 실시간으로 관리할 수 있으며, 사용자 인증 기능도 구현되었습니다.

    design:
      spacing:
        padding: ['40px', '0', '40px', '0']
        gap: '40px'
      layout: list
      layout_style: flex
      list_layout: vertical
---
