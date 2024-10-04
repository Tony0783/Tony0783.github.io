---
title: "Home Page"
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: Summary
      text: |
        **Expected Graduate from Chonbuk National University, Computer Science Department**  
        Languages: **Java, C, C++, Python, JavaScript, HTML, C#**

        ### Project Experience
        - Blog platform development: Implemented comment functionality, search feature, and user profile registration
        - To-Do List app development: Implemented functionality for adding, deleting, and editing tasks
    design:
      background_color: "#e6f7ff"
      padding: "50px"

  - block: features
    content:
      title: Introduction
      text: |
        ### Personal Information
        **Gender:** Male  
        **Age:** 22  
        **Student ID:** 2020

        ### School Information
        I am currently studying at Chonbuk National University.  
        [Chonbuk National University Website](https://www.jbnu.ac.kr/kor/){:target="_blank"}

        ### Hobbies
        My hobbies are table tennis, skiing, and gaming.
    design:
      background_color: "#f0f8ff"
      padding: "50px"

  - block: slider
    content:
      slides:
        - image: /static/images/slider1.jpg
        - image: /static/images/slider2.jpg
        - image: /static/images/slider3.jpg
    design:
      slide_height: '1000px'
      is_fullscreen: false
      loop: true
      interval: 3000
      arrows: true
      autoplay: true

  - block: collection
    content:
      title: Education and Learning Courses
      subtitle: Here are some of the key courses.
      count: 3
      filters:
        folders:
          - education
      design:
        view: card
        columns: '3'

  - block: collection
    content:
      title: Projects
      subtitle: Here are some of the major projects.
      count: 3
      filters:
        folders:
          - projects
      design:
        view: card
        columns: '3'

---