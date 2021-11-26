---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<style>
code {padding: 6px 8px; font-size: 90%;}
</style>

Welcome to my personal homepage! I am currently working as a postdoctoral researcher in the group of [Dr. Joost de Winter](https://sites.google.com/site/jcfdewinter) at the department of [Cognitive Robotics](https://www.tudelft.nl/3me/over/afdelingen/cognitive-robotics-cor) of TU Delft. My focus is on Human Factors of communication between automated vehicles and vulnerable road users (pedestrians, cyclist). I am a bit advocate of open science (hence this website being on GitHub) and I volunteer as a [data champion](https://openworking.wordpress.com/2019/08/19/switch-gear-drive-the-uptake-of-open-science-within-your-research-team) of the 3mE faculty of TU Delft. 


### Short bio
I joined TU Delft in August 2014 to work on the HFAuto project as a Marie Curie Fellow. During my PhD, my aim was to develop a human-machine interface for highly automated driving, focusing on the auditory modality. I defended my PhD in December, 2018. You may see my thesis at [the repository of TU Delft](https://repository.tudelft.nl/islandora/object/uuid%3A51dbba63-ba7c-4958-ab7d-d6dc182ec5b5).

Before starting my PhD on human factors, I was doing something completely different. I concluded Erasmus Mundus Double MSc in Dependable Software Systems with double distinction at the University of St Andrews (Scotland) and Maynooth University (Ireland) in 2014. I wrote two dissertations within this degree where I evaluated [implications of porting a strongly-encapsulated programming language Insense to multi-core systems](https://www.researchgate.net/publication/281319882_Multi-core_Insense) and the [impact of the cache on multi-threaded data-sharing applications](https://www.researchgate.net/publication/282074873_Impact_of_cache_on_data-sharing_in_multi-threaded_programmes). I completed my BEng studies in Information Technology at Mikkeli University of Technology (Finland) in 2012, specialising in Software Engineering. In my thesis I focused on development of [a customisable multitenant web form for the bioenergy sector](https://www.researchgate.net/publication/312948358_Customisable_multitenant_web_form_with_JSF_and_MySQL). After my MSc, I decided to switch my research focus, as I was looking for a more hands-on area that has a direct impact on our world and great potential to save millions of people.

I am involved with startups. During 2017–2021 I was a chair and since 2021 I have been a vice-chair of the [Bridging Science and Academia working group](https://www.mariecuriealumni.eu/groups/bridging-science-and-business) of [Marie Curie Alumni Association (MCAA)](https://www.mariecuriealumni.eu). I was also a chair (2015–2017) and a vice-chair (2017–2019) of the [BeNeLux chapter](https://www.mariecuriealumni.eu/groups/benelux-chapter) of MCAA. I was a member of the Capacity building task-force of [(ESAA)](https://www.esaa-eu.org) (2018–2019), a board member of the Eurasian chapter (2017–2019), a member of the Communications and Course Quality Advisory Board (2017–2018) teams, and a director of [Research and innovation unit](https://www.em-a.eu/unit-riu) (2019–2021) of [Erasmus Mundus Association (EMA)](https://www.em-a.eu/).

### Multi-user communication in traffic
I am currently engaged in research on communication between multiple automated vehicles and multiple vulnerable road users. Most of experiments in current research features 1, maybe 2, human participants. But, think about driving around a town in real life. Traffic situations are very complicated. And being able to perform experiments with 3, 4, ..., 16 participants is essential for understanding the mechanics of communication of situation awareness/collaborative decision making/collaboration in both modern and future traffic. To enable such research, I present an open-source simulator supporting a virtually unlimited number of human participants and fine-tunes for high precision data logging. It is aimed for, but not limited to, academic research. Available on [GitHub](https://github.com/bazilinskyy/coupled-sim).

<div class="row" style="text-align:center">
  <iframe style="display:inline-block; border-radius: 10px; border:0px solid #FFF; width: 95%; height: 250px" src="https://www.youtube.com/embed/W2VWLYnTYrM?&loop=1&autoplay=1&mute=1" frameborder="0" allowfullscreen></iframe>
  Demo of coupled simulator with 3 agents in the same traffic scene.
</div>

### Free time
* 🏃‍♂🚴‍♂️🏊‍♂️ Running, cycling, swimming (yap, triathlon), hiking. Like, [a lot of it](https://www.strava.com/athletes/7126007).
* 🗺️ Travelling (especially through [couchsurfing](https://www.couchsurfing.com/people/pavlo.bazilinskyy)/[bewelcome](https://www.bewelcome.org/members/bazilinskyy)/[trustroots](https://www.trustroots.org/profile/bazilinskyy)).
* 📖 Reading ([goodreads](https://www.goodreads.com/user/show/5571310-pavlo-bazilinskyy)).
* ♟️ Chess ([chess.com](https://www.chess.com/member/bazilinskyy)).
* 🎸 Music ([last.fm](https://www.last.fm/user/Hollgam)). I also play sax alto and guitar.
* 📺 I enjoy watching films that feel more like a good book when you watch them.

<br/>
<div class="well-md">
<h3>Sponsors</h3>
<div style='display:block; text-align:center; margin-left:auto; margin-right:auto;'>
 {% for funder in site.data.funders %}{% if funder.url %}<a href="{{funder.url}}" target="_blank"><img src='/images/logopic/{{ funder.image }}' style='max-height: 70px; max-width: 170px;'/></a>{% else %}<img src='/images/logopic/{{ funder.image }}' class='mycenter' style='max-height: 70px; max-width: 170px;'/>{% endif %}   {% endfor %}
</div>

</div>


