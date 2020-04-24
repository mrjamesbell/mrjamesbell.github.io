---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
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
