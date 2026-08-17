---
layout: splash
title: "my title"
excerpt: "Hej"
main_row:
  - image_path: /assets/images/adam.png
    alt: "picture of Adam"
    title: "Adam Holmgård Nielsen"
    excerpt: |
      - **Key:** This is some sample content that goes here with **Markdown** formatting. Left aligned with type="left"
      - **Troll:** Lolol
education_row:
  - title: "Education"
    excerpt: |
      - **Skole1:** skoleskole
      - **Skole2:** fjrifow
work_row:
  - title: "Work experience"
publication_row:
  - title: "Publications"
---



<div style="max-width: 1100px; margin: 0 auto; overflow: visible !important;" class="no-bullets">

{% include feature_row id="main_row" type="left" %}


{% include feature_row id="education_row" type="left" %}
{% include feature_row id="work_row" type="center" %}
{% include feature_row id="publication_row" type="center" %}
</div>
