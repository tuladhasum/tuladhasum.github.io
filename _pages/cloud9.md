---
layout: blog
title: Cloud 9 Page
permalink: /pages/cloud9/
id: hello world
---

## Variable
{% highlight ruby %}{% raw %}
{% assign my_variable = false %}
{% if my_variable != true %}
  Hi there!
{% endif %}{% endraw %} {% endhighlight %}

## Iteration
{% highlight ruby %}{% raw %}
{% for i in (1..5) %}
    {% if i == 3 %}
      {% break %}
    {% else %}
      {{ i }}
    {% endif %}
{% endfor %}{% endraw %} {% endhighlight %}


## Gist
{% gist tuladhasum/08ffa171cbe301db4aaf %}

---

HTML
: Hypertext Markup Language, a standardized system for tagging text files.


CSS
: Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language

> Some good examples on jekkyll sites are on [adamsilver](https://github.com/adamsilver) website
> This is officially cloud 9 page

> Source [Jekyll Cheat Sheet](http://sumit-php-tuladhasum.c9users.io/pages/cloud9/)

> Source [Pygments Formatting](http://pygments.org/docs/formatters/)

---
## Tables

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## Text Markup
**strong** text

_emphasis_ text

`inline` code

[link](http://jekyllrb.com) text

{{ page.id }}