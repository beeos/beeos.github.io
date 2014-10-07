---
layout: post
title:  "The first draft text"
date:   2014-09-26 19:06:37
categories: docs
---

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve --watch`, which launches a web server and auto-regenerates your site when a file is updated.

Мои профили на других сайтах: 

{: .fa-ul}
  - <i class="fa-li fa fa-facebook brand"></i>[Facebook](https://www.facebook.com/dmitry.kalinnikov.3)
  - <i class="fa-li fa fa-vk brand"></i>[Вконтакте](https://www.vk.com/beeos)
  - <i class="fa-li fa fa-twitter brand"></i>[Twitter](https://www.twitter.com/beeos)
  - <i class="fa-li fa fa-weibo brand"></i>[Мой Круг](https://www.twitter.com/beeos)

{% assign items = site.data.wishlist %}

{% for item in items %}
{{ item.name }}
{% endfor %}

<table>
{% tablerow item in items cols: 2 limit: 6 %}
    {{ item.name }}
{% endtablerow %}
</table>