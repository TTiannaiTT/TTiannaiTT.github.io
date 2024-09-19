---
layout: page
permalink: /course/
title: Course
description: Welcome to the Courses page of my personal website! On this page, I highlight the core courses from my undergraduate studies, reflecting my academic performance and interests.
nav: true
nav_order: 6
---
## Academic Performance
---
### Overview
GPA： 3.84 / 4.0 (currently)

### Representative Courses:

| Title of Courses | Grade |
| :--------------- | :----- |
| *Machine Learning (Billingual)* | *97 / 100 ( Top 1 )* |
|*Pattern Recognition (English)* | *90 / 100*|
|*Optimization Method* | *91 / 100*|
|*Introduction to Artificial Intelligence (Billingual)* | *98 / 100 ( Top 1 )*|
|*Data Structure (Billingual)* | *100 / 100 ( Top 1 )*|
|*Operating System (English)* | *97 / 100 (Top 1 %)*|
|*Programming & Algorithmic Language i (Billingual)* | *93 / 100*|
|*Programming & Algorithmic Language ii (Billingual)* | *95 / 100*|
|*Discrete Mathematics (Billingual)* | *94 /100*|
|*Linear Algebra* | *98 / 100 ( Top 1% )*|


*PS: Top 1 and Top 1% represents my performance in this course among all students from different majors who took the course.*



## Related Materials
---
You can access my course notes and study materials through the GitHub repository below. I would be very happy if they are helpful to your learning. If you find them useful, feel free to give the repository a star⭐ to show your support.

{% if site.data.repositories.course_repo %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.course_repo %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}

---

