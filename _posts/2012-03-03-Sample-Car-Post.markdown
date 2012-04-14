---
layout: post
title: Sample Post
category: more
---

<div class="row">
	<div class="span3 columns">
	
	  <h3>Online Buzz</h3>
	  <p>What others are thinking. Add to the conversation and generate some chatter.</p>
	  <p><a href="https://twitter.com/share" class="twitter-share-button" data-via="kevingailey">Tweet</a></p>
	  <p><g:plusone size="medium"></g:plusone></p>	
	  <p><script type="text/javascript" src="http://www.reddit.com/buttonlite.js?i=2&styled=off&url={{ page.url }}&newwindow=1"></script></p> 	  
	  <br/>
	  <h3>Read later</h3>
	  <p><a href="http://www.instapaper.com/hello2?url={{ page.url }}&title={{ page.title }}" title="Save {{ page.title }} to Instapaper" target="_blank">Save this blog post</a> to read later.</p>
    </div>
	<div class="span9 columns">
	  <h2>Info</h2>
	  <p>This is a template for other posts.</p>  
	  <hr>
	  <h2>Another Section Title</h2>
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

<div class="row">
	<div class="span3 columns">&nbsp;</div>
    <div class="span9 columns">     
		
<!-- Twitter -->
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>

<!-- Google + -->
<script type="text/javascript">
  (function() {
    var po = document.createElement('script'); po.type = 'text/javascript'; po.async = true;
    po.src = 'https://apis.google.com/js/plusone.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(po, s);
  })();
</script>