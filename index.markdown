---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
<div class="hero">
    <img class="right" src="https://www.gravatar.com/avatar/f9bbdfa5acbc875911686caea16dc53e?s=200">
    <h2> Hello, I'm James</h2>
    <P>
This is a hero section for the index page.  It serves as an introduction and could perhaps include a picture or something</P>
<p class="reverse">This is absolutely still a test</p>
<p>Plays league of legends stare out the window. Lies down lick sellotape hopped up on catnip, yet bleghbleghvomit my furball really tie the room together, thug cat . Play riveting piece on synthesizer keyboard sit in window and stare oooh, a bird, yum shove bum in owner’s face like camera lens or toy mouse squeak roll over. Fall asleep on the washing machine hide when guests come over stare at guinea pigs yet vommit food and eat it again eat and than sleep on your face. Jump five feet high and sideways when a shadow moves throwup on your pillow. Missing until dinner time. Pet right here, no not there, here, no fool, right here that other cat smells funny you should really give me all the treats because i smell the best and omg you finally got the right spot and i love you right now nap all day flop over, so missing until dinner time, for see owner, run in terror sun bathe. Give attitude intently sniff hand, yet meow all night having their mate disturbing sleeping humans. Lounge in doorway chase imaginary bugs.</p>
</div>

{% for post in site.posts limit: 5%}
  <div class="posttitle">
    <h2>{{ post.title }}</h2>
    <h4>Posted {{ post.date | date: "%-d %B %Y" }}</h4>
  </div>
  <DIV class="postcontent">
    {{ post.content }}
   </DIV>
      {% endfor %}
<p><h2><a href="/archive.html">Older Blog Posts...</a></h2></p>
