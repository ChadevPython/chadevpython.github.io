---
layout: meetup
title:  "February Meetup"
truncate: true
meetup: "february-2018-02-19"
event_date: 2018-02-19
event_time: 6pm - 8pm
location:
  name: "Floor 5 at The Edney Innovation Center <br> 1100 Market Street, Suite 500, Chattanooga, TN"
  url: "https://www.google.com/maps/place/1100+Market+St+%23500,+Chattanooga,+TN+37402/@35.0433881,-85.3179746,14.86z/data=!4m5!3m4!1s0x88605e7c73d2b5ed:0xf9bc32f47eb19fd8!8m2!3d35.0436249!4d-85.3089768"
  embeded_url: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3266.5244526817687!2d-85.3089768!3d35.0436249!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88605e7c73d2b5ed%3A0xf9bc32f47eb19fd8!2s1100+Market+St+%23500%2C+Chattanooga%2C+TN+37402!5e0!3m2!1sen!2sus!4v1534883926333"
date: 2018-02-19
---

<p class="intro">
<span class="dropcap">C</span>hadevMonster Hack Night!!!
</p>

#### What we'll do

Lets all get together and work on ChadevMonster!

#### What's ChadevMonster???

Have you found a really neat article you want to share with the community? Or do
you find lots of articles you want to share with the community? Or maybe you have
published your own article you want to share? ChadevMonster is a web app that lets
you submit those articles to a queue then once a day one of those articles is posted
to our Chadev subreddit and when we get to a certain point it will post directly to one of our slack channels.

#### About the technology

This is built using Python and the Flask framework. If you're brand new to development,
python, or flask or if you're a seasoned developer come help us learn from each
other and build a wonderful app for our community.

#### What to bring

Bring a computer if you want or just bring your willingness to learn, help, and work together.


<hr>
Reminder: If you want to give a talk at an upcoming meetup please reach out.


{% if page.location && page.location.embeded_url %}
  {% include location.html url=page.location.embeded_url %}
{% endif %}
