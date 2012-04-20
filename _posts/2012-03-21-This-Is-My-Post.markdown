---
layout: post
title: Sample Post
category: more
---


	<div class="span9 columns">
	  <h2>Hello World</h2>
	  <p>This is my first post. More to come.</p>  
	  <hr>
	  <h2>And Other Updates!</h2>
	  <p>.</p>	  
	  <hr>
	</div>
</div>

<div class="row">
	<div class="span3 columns">&nbsp;</div>
	<div class="span9 column">
			<p class="pull-right">{% if page.previous.url %} <a href="{{page.previous.url}}" title="Previous Post: {{page.previous.title}}"><i class="icon-chevron-left"></i></a> 	{% endif %}   {% if page.next.url %} 	<a href="{{page.next.url}}" title="Next Post: {{page.next.title}}"><i class="icon-chevron-right"></i></a> 	{% endif %} </p>  
	</div>
</div>