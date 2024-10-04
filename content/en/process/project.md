---
title: "Portfolio Introduction"
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: Taeho Park's Portfolio
      text: |
        This is Taeho Park's personal portfolio. In this portfolio, I introduce the projects I have completed so far.

  - block: features
    id: project_list
    content:
      title: Project List
      items:
        - name: Blog Platform Development
          description: |
            Developed a blog platform using Django and React, providing features such as user authentication, comments, and post creation. Also implemented user profile management, search functionality, and tag categorization.
        - name: Automatic News Article Crawling
          description: |
            Built a system using Python's BeautifulSoup library to automatically collect and analyze articles from news websites. The collected data was analyzed and visualized using Pandas and Matplotlib.
        - name: To-Do Management Application
          description: |
            Developed a mobile application using Flutter, where users can add, modify, and delete tasks. Integrated with Firebase for real-time data management and implemented user authentication.

    design:
      spacing:
        padding: ['40px', '0', '40px', '0']
        gap: '40px'
      layout: list
      layout_style: flex
      list_layout: vertical
---
