---
layout: events
title: Events
excerpt: ""
search_omit: true
image:
  feature: About_img.png
---

Events for the academic year 2017-18 will be announced soon. Meanwhile, you can follow us on Facebook!


{% for post in site.categories.events %} 

<div class="row rect col-sm-12 col-xs-12" style="background: {% if post.status == 'Finished' %} #9e9e9e {% elsif post.status == 'Nearest'%} #7cbf5b {% elsif post.status == 'Future'  %}  #ffffff {% endif %}">

 <a href="{{ site.url }}{{ post.url }}">
  <div class="col-sm-1 col-xs-0"></div>
  <div class="col-sm-2 col-xs-2">
<div class="date"> 
   	<p>{{ post.day }}<span>{{ post.month }}</span></p>
   </div>
  </div> 
  <div class="col-sm-9 col-xs-10">
   <p class="event"> {{post.pseudo_title}}  </p>
  </div>
  </a>
</div>

 


{% endfor %}

<div class="fb-page" data-href="https://www.facebook.com/mnpiitb" data-tabs="timeline" data-small-header="false" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="true"><blockquote cite="https://www.facebook.com/mnpiitb" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/mnpiitb">Maths and Physics Club, IIT Bombay</a></blockquote></div>
