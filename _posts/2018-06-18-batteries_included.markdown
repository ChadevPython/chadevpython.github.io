---
layout: meetup
title:  "June Meetup"
truncate: true
meetup: "june-2018-06-18"
event_date: 2018-06-18
event_time: 6pm - 8pm
location:
  name: "Floor 5 at The Edney Innovation Center <br> 1100 Market Street, Suite 500, Chattanooga, TN"
  url: "https://www.google.com/maps/place/1100+Market+St+%23500,+Chattanooga,+TN+37402/@35.0433881,-85.3179746,14.86z/data=!4m5!3m4!1s0x88605e7c73d2b5ed:0xf9bc32f47eb19fd8!8m2!3d35.0436249!4d-85.3089768"
  embeded_url: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3266.5244526817687!2d-85.3089768!3d35.0436249!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88605e7c73d2b5ed%3A0xf9bc32f47eb19fd8!2s1100+Market+St+%23500%2C+Chattanooga%2C+TN+37402!5e0!3m2!1sen!2sus!4v1534883926333"
date: 2018-06-18
---

<p class="intro">
<span class="dropcap">B</span>atteries Included: The Python Standard Library w/Caleb Salt
</p>

The wikipedia page for "Batteries Included" says:

Batteries Included may refer to:

- Batteries Included (company), a computer hardware and software company
- "Batteries Included" (song), a 1996 single by Servotron
- Motto of the Python programming language, meaning it comes with a large library of useful modules.
- Batteries Included (slang), in a product usability (mostly in software) it states that the product comes together with all possible parts required for full usability.

I really love working with Python, in part due to its extensive standard library. We'll go over some of the cool things in there looking at code and examples of their use.

<hr>
Reminder: If you want to give a talk at an upcoming meetup please reach out.


{% if page.location && page.location.embeded_url %}
  {% include location.html url=page.location.embeded_url %}
{% endif %}
