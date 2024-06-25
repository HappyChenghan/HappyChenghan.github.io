---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
- [**Mpbicom'22**] Protego: securing wireless communication via programmable metasurface
  Xinyi Li,Chao Feng,Fengyi Song,**Chenghan Jiang**,Yangfan Zhang,Ke Li,Xinyu Zhang,Xiaojiang Chen



{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


