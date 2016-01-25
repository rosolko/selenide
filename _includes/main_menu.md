<ul class="main-menu-pages">
  <li><a href="{{ BASE_PATH }}/quick-start.html">Quick start</a></li>
  <li><a href="{{ BASE_PATH }}/documentation.html">Docs</a></li>
  <li><a href="{{ BASE_PATH }}/faq.html">FAQ</a></li>
  <li><a href="{{ BASE_PATH }}/blog.html">Blog</a></li>
  <li><a href="{{ BASE_PATH }}/javadoc.html">Javadoc</a></li>
  <li><a href="{{ BASE_PATH }}/users.html">Users</a></li>
  <li><a href="{{ BASE_PATH }}/quotes.html">Quotes</a></li>
</ul>

<div class="news">
  <div class="news-line"><a href="/2015/11/30/selenide-3.0/">Released Selenide 3.0!</a></div>
  <!--<div class="news-line"><a href="/2015/11/30/selenide-2.25/">Released Selenide 2.25!</a></div>-->
  <!--<div class="news-line"><a class="video" href="//www.youtube.com/watch?v=BjEW08vDUfI">Selenide presentation at Devoxx 2015</a></div>-->
  <!--<div class="news-line"><a href="/2015/11/08/selenide-2.24/">Released Selenide 2.24!</a></div>-->
  <!--<div class="news-line"><a href="/2015/09/23/selenide-on-seleniumconf/">Selenide on SeleniumConf 2015</a></div>-->
  <!--<div class="news-line"><a href="https://t.co/Ih8FQ7VJMj">Selenide presentation at SeleniumConf 2015 in Portland!</a></div>-->
  <!--<div class="news-line"><a class="video" href="//vimeo.com/107647158">How to write UI test in 10 minutes</a></div>-->
</div>

<h3 style="display:none">Blog</h3>
<div class="archive" style="display:none">
  {% assign posts_collate = site.posts %}
  {% include JB/posts_collate %}
  <a href="{{ BASE_PATH }}/archive.html" class="right small">Blog archive</a>
</div>