---
layout: default
title: Home
---

<div class="centered-image">
  <img src="{{ site.profile_image }}" alt="Rishabh Singhal">
</div>

# Rishabh Singhal

**PhD Student in Neuroengineering**

## About Me
I am a PhD student at McGill University working on neuroengineering projects to increase personhood for non-communicative individuals through interdisciplinary research.

## Research Interests
- Neuroengineering
- Patient Care
- Interdisciplinary Research on Personhood

<div class="timeline">
  {% for event in site.timeline_events %}
  <div class="timeline-event">
    <div class="timeline-date">{{ event.date }}</div>
    <div class="timeline-content">{{ event.content }}</div>
  </div>
  {% endfor %}
</div>

## Publications
- "Modeling Cognition with Recurrent Neural Networks"
- "Interdisciplinary Approaches to Personhood in Non-communicative Individuals"

## Contact
<span id="email">rishabh.singhal@umontreal.ca</span> <button onclick="copyEmail()">Copy Email</button> or connect with me on [LinkedIn]("{{ site.linkedin_username }}")

