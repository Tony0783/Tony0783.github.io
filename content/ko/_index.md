---
title: "홈 페이지"
date: 2024-03-25
type: landing
---

{{< section class="section-container" >}}

  <!-- 추가된 자기소개 요약본 섹션 -->
  {{< section class="summary" background-color="#e6f7ff" padding="50px" >}}
    <h2>자기소개 요약본</h2>
    <p><strong>전북대학교 컴퓨터공학과 졸업 예정</strong></p>
    <p>사용 가능 언어: <strong>Java, C, C++, Python, JavaScript, HTML, C#</strong></p>
    <h3>프로젝트 경험</h3>
    <ul>
      <li>블로그 플랫폼 개발: 댓글 기능, 검색 기능, 사용자 프로필 등록 기능 구현</li>
      <li>할 일 목록 앱 개발: 할 일 추가, 삭제, 수정 기능 구현</li>
    </ul>
  {{< /section >}}

  <!-- 자기소개 섹션 -->
  {{< section class="intro" background-color="#f0f8ff" padding="50px" >}}
    <div class="cards-container" style="display: flex; flex-wrap: wrap; gap: 20px;">
      <!-- 신상 정보 카드 -->
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>신상 정보</h3>
        <p><strong>성별:</strong> 남</p>
        <p><strong>나이:</strong> 22</p>
        <p><strong>학번:</strong> 2020</p>
      </div>
      <!-- 학교 소개 카드 -->
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>학교 소개</h3>
        <p>저는 전북대학교에 재학 중입니다.</p>
        <p><a href="https://www.jbnu.ac.kr/kor/" target="_blank" style="color: blue;">전북대학교 홈페이지</a></p>
      </div>
      <!-- 취미 카드 -->
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>취미</h3>
        <p>저의 취미는 탁구, 스키, 게임입니다.</p>
      </div>
    </div>
  {{< /section >}}

  <!-- 이미지 슬라이더 섹션 -->
  {{< section class="slider" background-color="#f8f8f8" padding="50px" >}}
    <div class="slider-container" style="max-width: 100%; position: relative;">
      <!-- 슬라이더 이미지 -->
      <div class="slides">
        <img src="/images/slider1.jpg" style="width: 100%; height: auto; max-height: 1000px;">
        <img src="/images/slider2.jpg" style="width: 100%; height: auto; max-height: 1000px;">
        <img src="/images/slider3.jpg" style="width: 100%; height: auto; max-height: 1000px;">
        <img src="/images/slider4.jpg" style="width: 100%; height: auto; max-height: 1000px;">
      </div>
      <!-- 이전 버튼 -->
      <a class="prev" style="position: absolute; top: 50%; left: 0; transform: translateY(-50%); font-size: 18px; padding: 16px; cursor: pointer; background-color: rgba(0, 0, 0, 0.5); color: white;">&#10094;</a>
      <!-- 다음 버튼 -->
      <a class="next" style="position: absolute; top: 50%; right: 0; transform: translateY(-50%); font-size: 18px; padding: 16px; cursor: pointer; background-color: rgba(0, 0, 0, 0.5); color: white;">&#10095;</a>
    </div>
  {{< /section >}}

  <!-- 교육 과정 섹션 -->
  {{< section class="education" background-color="#ffffff" padding="50px" >}}
    <h2>교육 및 학습 과정</h2>
    <div class="cards-container" style="display: flex; flex-wrap: wrap; gap: 20px;">
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>웹 서비스 설계</h3>
        <p>웹 서비스의 구조와 설계, 시스템 아키텍처에 대해 공부하고 있습니다.</p>
      </div>
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>컴퓨터 그래픽스</h3>
        <p>컴퓨터 그래픽스의 이론과 실습을 통해 3D 모델링과 렌더링 기법을 배우고 있습니다.</p>
      </div>
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>소프트웨어 공학</h3>
        <p>소프트웨어 개발 프로세스와 유지보수, 프로젝트 관리 방법론에 대해 학습 중입니다.</p>
      </div>
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>정보 검색</h3>
        <p>효율적인 정보 검색 시스템 설계와 관련 알고리즘을 배우고 있습니다.</p>
      </div>
    </div>
  {{< /section >}}

  <!-- 진행했던 프로젝트 섹션 -->
  {{< section class="projects" background-color="#f0f8ff" padding="50px" >}}
    <h2>진행했던 프로젝트</h2>
    <div class="cards-container" style="display: flex; flex-wrap: wrap; gap: 20px;">
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>뉴스 기사 자동 크롤링 프로젝트</h3>
        <p>Python과 BeautifulSoup을 활용해 뉴스 기사 데이터를 자동으로 수집하고 분석하는 시스템 개발.</p>
      </div>
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>게시판 만들기 프로젝트</h3>
        <p>사용자가 게시물을 등록, 수정, 삭제할 수 있는 게시판을 구현. 사용자 인증 및 권한 관리 기능 포함.</p>
      </div>
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>할 일 관리 애플리케이션</h3>
        <p>할 일 목록 추가, 삭제, 편집 기능이 있는 모바일 애플리케이션 개발.</p>
      </div>
    </div>
  {{< /section >}}

{{< /section >}}
