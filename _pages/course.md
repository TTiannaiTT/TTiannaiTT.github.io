---
layout: page
permalink: /course/
title: Course
description: Welcome to the Courses page of my personal website! On this page, I highlight the core courses from my undergraduate studies.
nav: true
nav_order: 6
---
## Academic Performance
---
### Overview
GPA： 3.88 / 4.0 (currently)  
Average Score: 91.36 / 100 (currently)
<br/>

### Representative Courses:

| Course Name| Grade |
| :--------------- | :----- |
| *Machine Learning (Billingual)* | *97 / 100* |
|*Pattern Recognition (English)* | *90 / 100*|
|*Optimization Method* | *91 / 100*|
|*Introduction to Artificial Intelligence (Billingual)* | *98 / 100*|
|*Data Structure (Billingual)* | *100 / 100*|
|*Operating System (English)* | *97 / 100*|
|*Programming & Algorithmic Language i (Billingual)* | *93 / 100*|
|*Programming & Algorithmic Language ii (Billingual)* | *95 / 100*|
|*Discrete Mathematics (Billingual)* | *94 /100*|
|*Linear Algebra* | *98 / 100*|



## Related Materials
You can access my course notes and study materials through the GitHub repository below. I would be very happy if they are helpful to your learning.

{% if site.data.repositories.course_repo %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.course_repo %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}

---

