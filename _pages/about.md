---
layout: about
title: About
permalink: /

subtitle: 

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
     <p> </p>
     <p> </p>
     <p> </p>

news: false
selected_papers: false
social: true
latest_posts:
  - date: "March 7, 2024"
    link: "https://www.linkedin.com/feed/update/urn:li:activity:7167929915160416257/"
    description: "Webinar on Quantum Computing by IIT Madras"
  - date: "February 6, 2024"
    link: "https://www.linkedin.com/feed/update/urn:li:activity:7158450504539283457/"
    description: "Webinar on Human-Robot Interaction by Stanford University"
  - date: "April 6, 2023"
    link: "https://www.linkedin.com/feed/update/urn:li:activity:7051565419035279361/"
    description: "Webinar on Snow Leopard Conservation by WWF"  
---

A flora and fauna lover, with deep research interest in Machine Learning domain of **Natural Langauge Processing (NLP)**. I work broadly in the areas of Automatic Speech Recognition (ASR), Large Language Models (LLMs), Signal Processing and Machine Learning Operations (MLOps). I'm also fascinated in exploring the areas of Computer Vision, Embodied AI, Robotics & Multi Agent Systems.

Beyond technical stuff, I love hitting the gym, write poetry & stories, experiment with music & technology by creating short tunes & lyric less musics. Also, when I unwind, I'm drawn to Netflix webseries & films for entertainment.

I am **open to collaborating** with individuals/ groups/ labs who share similar
 research interests, with the aim of working on a novel project and subsequently publishing a paper in a core A/A* conference or a reputable journal.

I can be reached at **sarthakjainssjj@gmail.com** & for urgent matters, please use **shubh2002jain@gmail.com**.

{% if page.latest_posts %}
<section>
  <h2>Latest Posts/ News</h2>
  <ul>
    {% for post in page.latest_posts %}
    <li>
      <span>{{ post.date }}</span>
      <a href="{{ post.link }}">{{ post.description }}</a>
    </li>
    {% endfor %}
  </ul>
</section>
{% endif %}
