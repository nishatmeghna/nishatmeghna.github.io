---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<style>
code {padding: 6px 8px; font-size: 90%;}
</style>

Welcome to Rahad Arman Nabid's academic website! I am currently a PhD student working as a research assistant at [Temple HCI lab](https://www.linkedin.com/company/temple-hci-lab/). My research revolves around LLMs in education, Narrative Visualization, and Human-AI collaboration for intelligent systems. I am fortunate to be under the supervision of my PI, Professor [Stephen MacNeil](http://stevemacn.github.io/). My research philosophy aims to enhance the accessibility and impact of just-in-time learning through AI and intelligent systems.  

In the fall of 2023, I became a part of Temple University's Computer and Information Science Department. My area of concentration lies in Human-Computer Interaction within the field of AI. To align with this focus, I have enrolled in courses offered by the AI track, such as machine learning, graph theory, data mining, and deep learning. My expected graduation date is 2027!!! 


### Currently Ongoing Projects 
Currently, I am involved in three separate projects: Expert Goggles (EG), Piggyback Learning (PG), and VisChatBot (VCB). In the EG project, our primary objective is to evaluate three distinct approaches that allow individuals to understand visualization charts effectively. Specifically, we have developed a learner-driven approach that employs narrative-based guidance to aid non-experts in interpreting data from these charts.

Within the PG project, our focus lies in creating a mixed initiative environment derived from YouTube videos, which aims to enhance early education learning. This environment facilitates a collaborative learning experience where users can actively participate in the educational process.

In the VCB project, our primary focus is on employing procedural methods to enable interactive annotation on visualizations using narrative storytelling techniques. This approach eliminates the need for manual coding and streamlines the process for news portals.

<div class="row" style="text-align:center">
  <iframe style="display:inline-block; border-radius: 5px; border:0px solid #FFF; width: 95%; height: 246px" src="/gifs/eg.gif" frameborder="0" allowfullscreen></iframe>

 Figure EG: Expert Goggles following Learner Based Data Storytelling from Visualization.
</div>

### Free time
* 🏃‍♂🚴‍♂️🏊‍♂️ Running, [cycling](https://www.wielervrienden.nl/profiel/pavlo-7126007), swimming, cross-country skiing, hiking. Like, [a lot of it](https://www.strava.com/athletes/bazilinskyy).
* 🗺️ Travelling (especially through [couchsurfing](https://www.couchsurfing.com/people/pavlo.bazilinskyy)/[bewelcome](https://www.bewelcome.org/members/bazilinskyy)/[trustroots](https://www.trustroots.org/profile/bazilinskyy), [travel map](https://www.roadgoat.com/travelers/pavlo-bazilinskyy?share_map=City)).
* 💻 Coding ([github](https://github.com/bazilinskyy)).
* 📖 Reading ([goodreads](https://www.goodreads.com/user/show/5571310-pavlo-bazilinskyy)).
* ♟️ Chess ([chess.com](https://www.chess.com/member/bazilinskyy)).
* 🎸 Music ([last.fm](https://www.last.fm/user/Hollgam)). I also play sax alto and guitar.
* 📺 Films and tv series ([imdb](https://www.imdb.com/user/ur16534776), [trakt](https://trakt.tv/users/bazilinskyy)). Somebody likes tv, surprise! 😬

<br/>

<div class="well-md">
  <h3>Funding</h3>
  <div style='display:block; text-align:center; margin-left:auto; margin-right:auto;'>
   {% for funder in site.data.funders %}{% if funder.url %}<a href="{{funder.url}}" target="_blank"><img src='/images/logos/{{ funder.image }}' style='max-height: 70px; max-width: 170px;'/></a>{% else %}<img src='/images/logos/{{ funder.image }}' class='mycenter' style='max-height: 70px; max-width: 170px;'/>{% endif %}   {% endfor %}
  </div>
</div>
