---
layout: default
comments: true
---
<div class="post">
<p>{{ page.date | date_to_string }}</p>
<h2>{{ page.title }}</h2>
{{ content }}
</div>

<div id="disqus_thread" class="disqus-box">
<script>
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = '//lawre.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
</div>
