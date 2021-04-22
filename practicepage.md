---
layout: page
title: Practice Page
permalink: /practicepage/
---
<footer class="site-footer h-card">
  <data class="u-url" href="{{ "/" | relative_url }}"></data>

  <div class="wrapper">

    
      {%- if site.author %}
        <ul class="contact-list">
          {% if site.author.name -%}
            <li class="p-name">{{ site.author.name | escape }}</li>
          {% endif -%}
          {% if site.author.email -%}
            <li><a {{ site.description | escape }}class="u-email" href="mailto:{{ site.author.email }}">{{ site.author.email }}</a> </p>
          {%- endif %}
        </ul>
      {%- endif %}
      </div>
      <div class="footer-col">
        <p>
      </div>
    </div>

    <div class="social-links">
      {%- include social.html -%}
    </div>

  </div>

</footer>

---
 <style>
.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
 
  color: black;
  text-align: center;
}
</style>

<div class="footer">
  <p>Winnebago View 24J Motorhome Mods     <a href="mailto:our2020view@gmail.com"> our2020view@gmail.com</a></p>
</div> 


