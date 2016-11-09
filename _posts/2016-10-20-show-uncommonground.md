---
layout: show
title: DōsLambōs at Uncommon Ground
description: We performed a 30 minute set at the Uncommon Ground on Clark
content: DōsLambōs was at Uncommon Ground on October 20, 2016! This first concert in a while. We performed a 30 minute set. Excited for many more to come!
image: concert-pics/16-10-20-uncommon-ground.jpg
image-alt: DōsLambōs at Uncommon Ground
sub-header: We're making moves
call-to-action-button-text: Be our friend
call-to-action-link: http://facebook.com/doslambosband
published: true
---

  <section id="two" class="spotlights">
  	<section>
    <a href="generic.html" class="image">
      <img src="{{ site.url }}/assets/images/{{ page.image }}" alt="{{ page.image-alt }}" data-position="center right" />
    </a>
  		<div class="content">
  			<div class="inner">
  				<header class="major">
  					<h3>{{ page.sub-header }}11</h3>
  				</header>
  				<p>{{ page.description }}</p>
  				<ul class="actions">
  					<li><a href="{{ page.call-to-action-link}}" class="button">{{page.call-to-action-button-text}}</a></li>
            112
  				</ul>
  			</div>
  		</div>
  	</section>

    <div class="previous">
    {% if page.previous.url == null %}
        <p>No Previous Page</p>
      {% else %}
        <p>Previous Post: <a href="{{ page.previous.url }}">{{ page.previous.title }}</a></p>
    {% endif %}
    </div>

    <div class="next">
    {% if page.next.url == null %}
        <p>No Next Page</p>
      {% else %}
        <p>Next Post: <a href="{{ page.next.url }}">{{ page.next.title }}</a></p>
    {% endif %}
    </div>
  </section>
