---
title: "박태호님의 정보"
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: 박태호님의 정보
      text: |
        안녕하세요! 저는 전북대학교 컴퓨터공학과에 재학 중인 박태호입니다. 관심 분야는 인공지능, 웹 개발, 데이터 분석 등입니다. 
        다양한 프로젝트를 진행하며 기술을 쌓아가고 있습니다.

      design:
        spacing:
          padding: ['40px', '0', '40px', '0']
        text_align: center
        font_size: '2rem'

  - block: features
    id: profile_picture
    content:
      title: 프로필 사진
      design:
        image:
          filename: avatar.jpg  # 같은 폴더 내의 avatar.jpg 파일을 참조
          alt: 박태호의 프로필 사진
          style: "border-radius: 50%; display: block; max-width: 200px; margin: 0 auto;"
        text_align: center

  - block: features
    id: details
    content:
      title: 세부 정보
      items:
        - name: 이름
          description: 박태호
        - name: 나이
          description: 22
        - name: 전공
          description: 컴퓨터공학과, 전북대학교
        - name: 관심 분야
          description: 인공지능, 웹 개발, 데이터 분석

      design:
        font_size: '1.5rem'
        spacing:
          padding: ['20px', '0', '20px', '0']
        text_align: center

  - block: features
    id: skills
    content:
      title: 기술 스택
      items:
        - name: 프로그래밍 언어
          description: Java, C, C++, Python, JavaScript, HTML/CSS
        - name: 도구
          description: Git, Docker, Visual Studio Code, Jupyter Notebook
        - name: 프레임워크
          description: Django, Flask, React

      design:
        font_size: '1.5rem'
        spacing:
          padding: ['20px', '0', '20px', '0']
        text_align: center
---
