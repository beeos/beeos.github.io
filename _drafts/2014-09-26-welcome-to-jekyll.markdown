---
layout: post
title:  "Jekyll Sandbox"
date:   2014-09-26 19:06:37
categories: docs
tags: генератор модулятор супинатор
---
{% gist parkr/931c1c8d465a04042403 jekyll-private-gist.markdown %}

Define
: lkasdfj;adsfkjafsd;asdfkl  asasfd;kl af;dja fsd

Again
: alskjasfd;lkjasfd afsd asdfj; afs;dklf adsj;a fsd a fdsa ;fsdkljf ads;lkjaf  sdk; adfsjafdaf s

    f asdk;adf skljdfa s;lk dsaf
    fd sajkldfas ;adjkl fsdfs a

<i class="number">10000000</i>

1. T
{:toc}

## Простые правила

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve --watch`, which launches a web server and auto-regenerates your site when a file is updated.

## Сложные правила

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

## Очень сложные правила

Jekyll also offers powerful support for code snippets:

### Наисложнейшие правила

{% highlight ruby linenos %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

> A nice blockquote with several simple highlights and **definitions**
> 
> <small>— John Doe</small>

* * *

{{ page.date | localize: "%d %B %Y" }}

![image](http://placehold.it/350x150)

<ul>
{% for member in site.data.members | sort: 'github' %}
  <li>
    <a href="https://github.com/{{ member.github }}">
      {{ member.name }}
    </a>
  </li>
{% endfor %}
</ul>

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

Colons can be used to align columns.

| Tables        | Are     не очень      | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (\|) are optional(fn){}, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
_Still_ | `renders` | **nicely**
1 | 2 | 3

I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].


Here is some text ~~containing~~ a footnote.[^somesamplefootnote]

[^somesamplefootnote]: Here is the text of the footnote itself.

This is a statement that should be attributed to
its source [p. 23][#Doe:2006].

And following is the description of the reference to be
used in the bibliography.

[#Doe:2006]: John Doe. *Some Big Fancy Book*.  Vanity Press, 2006.


  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
