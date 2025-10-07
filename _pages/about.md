---
layout: page
title: about
permalink: /
nav: true
---

<img class="col one right" src="{{ site.baseurl }}/assets/img/prof_pic.jpg">

<br/>

TEST SITE 07/20/25


<br/>
<br/>
<hr/>
<br/>
<div class="contacticon center">
    {%- if site.email -%}
	<a href="mailto:{{ site.email }}"><i class="fa fa-envelope-square"></i></a>
    {% endif %}
    {%- if site.github_username -%}
	<a href="https://github.com/{{ site.github_username }}" target="_blank"><i class="fa-brands fa-square-github"></i></a>
    {% endif %}
    {%- if site.linkedin_username -%}
	<a href="https://www.linkedin.com/in/{{ site.linkedin_username }}" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
    {% endif %}
    {%- if site.twitter_username -%}
	<a href="https://twitter.com/{{ site.twitter_username }}" target="_blank"><i class="fa-brands fa-square-x-twitter"></i></a>
    {% endif %}
</div>

<div class="col three caption">
	
</div>
