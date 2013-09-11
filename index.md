---
layout: page
title: Welcome!
tagline: Just starting...
---
{% include JB/setup %}

I'm experienced in 

* Data, look at [BEF-China data portal](http://china.befdata.biow.uni-leipzig.de), I did that for the [Department Functional Biodiversity, University of  Leipzig](http://uni-leipzig.de/spezbot)
* Statistics, especially R, for example [BEF-data R package](http://cran.r-project.org/web/packages/rbefdata/index.html)
* Ecology, [Publications](http://orcid.org/0000-0001-5358-5469)

Find me elsewhere at
* [Department Functional Biodiversity, University of  Leipzig](http://uni-leipzig.de/spezbot)
* [Orcid](http://orcid.org/0000-0001-5358-5469)
* [github](https://github.com/kej)
* [Bündnis 90/die Grünen in Berlin, Neukölln](http://www.gruene-neukoelln.de)


Starting with jekyll is not that difficult, but it's still step by step. 
So here are my first posts, including the "how to" post jekyll bootstrap provided me with.
    
## Posts


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



