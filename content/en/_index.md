---
title: "Home Page"
date: 2024-03-25
type: landing
---

{{< section class="section-container" >}}

  <!-- Summary Section -->
  {{< section class="summary" background-color="#e6f7ff" padding="50px" >}}
    <h2>Personal Summary</h2>
    <p><strong>Expected Graduation: Computer Science, Chonbuk National University</strong></p>
    <p>Languages: <strong>Java, C, C++, Python, JavaScript, HTML, C#</strong></p>
    <h3>Project Experience</h3>
    <ul>
      <li>Blog Platform Development: Implemented comment functionality, search feature, and user profile management.</li>
      <li>To-Do List App Development: Developed functionality for adding, editing, and deleting tasks.</li>
    </ul>
  {{< /section >}}

  <!-- Introduction Section -->
  {{< section class="intro" background-color="#f0f8ff" padding="50px" >}}
    <div class="cards-container" style="display: flex; flex-wrap: wrap; gap: 20px;">
      <!-- Personal Info Card -->
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>Personal Information</h3>
        <p><strong>Gender:</strong> Male</p>
        <p><strong>Age:</strong> 22</p>
        <p><strong>Student ID:</strong> 2020</p>
      </div>
      <!-- University Info Card -->
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>University Information</h3>
        <p>I am currently studying at Chonbuk National University.</p>
        <p><a href="https://www.jbnu.ac.kr/kor/" target="_blank" style="color: blue;">Chonbuk National University Website</a></p>
      </div>
      <!-- Hobbies Card -->
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>Hobbies</h3>
        <p>My hobbies include table tennis, skiing, and gaming.</p>
      </div>
    </div>
  {{< /section >}}

  <!-- Image Slider Section -->
  {{< section class="slider" background-color="#f8f8f8" padding="50px" >}}
    <div class="slider-container" style="max-width: 100%; position: relative;">
      <!-- Slider Images -->
      <div class="slides">
        <img src="/images/slider1.jpg" style="width: 100%; height: auto; max-height: 1000px;">
        <img src="/images/slider2.jpg" style="width: 100%; height: auto; max-height: 1000px;">
        <img src="/images/slider3.jpg" style="width: 100%; height: auto; max-height: 1000px;">
        <img src="/images/slider4.jpg" style="width: 100%; height: auto; max-height: 1000px;">
      </div>
      <!-- Previous Button -->
      <a class="prev" style="position: absolute; top: 50%; left: 0; transform: translateY(-50%); font-size: 18px; padding: 16px; cursor: pointer; background-color: rgba(0, 0, 0, 0.5); color: white;">&#10094;</a>
      <!-- Next Button -->
      <a class="next" style="position: absolute; top: 50%; right: 0; transform: translateY(-50%); font-size: 18px; padding: 16px; cursor: pointer; background-color: rgba(0, 0, 0, 0.5); color: white;">&#10095;</a>
    </div>
  {{< /section >}}

  <!-- Education Section -->
  {{< section class="education" background-color="#ffffff" padding="50px" >}}
    <h2>Education and Learning Process</h2>
    <div class="cards-container" style="display: flex; flex-wrap: wrap; gap: 20px;">
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>Web Service Design</h3>
        <p>Studying the structure and design of web services, and system architecture.</p>
      </div>
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>Computer Graphics</h3>
        <p>Learning 3D modeling and rendering techniques through theory and practice in computer graphics.</p>
      </div>
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>Software Engineering</h3>
        <p>Studying software development processes, maintenance, and project management methodologies.</p>
      </div>
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>Information Retrieval</h3>
        <p>Learning about the design of efficient information retrieval systems and related algorithms.</p>
      </div>
    </div>
  {{< /section >}}

  <!-- Project Section -->
  {{< section class="projects" background-color="#f0f8ff" padding="50px" >}}
    <h2>Projects</h2>
    <div class="cards-container" style="display: flex; flex-wrap: wrap; gap: 20px;">
      <!-- Project 1: News Article Crawling -->
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>News Article Crawling Project</h3>
        <p>Developed a system using Python and BeautifulSoup to automatically collect and analyze news articles.</p>
      </div>
      <!-- Project 2: Bulletin Board Development -->
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>Bulletin Board Development Project</h3>
        <p>Implemented a bulletin board where users can post, edit, and delete entries. Includes user authentication and permission management.</p>
      </div>
      <!-- Project 3: To-Do List App -->
      <div class="card" style="border: 1px solid #ddd; padding: 20px; width: 30%;">
        <h3>To-Do List App</h3>
        <p>Developed a mobile application with functionality for adding, deleting, and editing tasks.</p>
      </div>
    </div>
  {{< /section >}}

{{< /section >}}
