---
layout: post
title: "Customizing my navigation bar"
description: ""
category: 
tags: []
---
{% include JB/setup %}

Thanks to my brother [(kudos!)](http://www.linkedin.com/in/bnadrowski) I now removed a page from my navigation bar! It is as simple as removing the 

    group: navigation

from the YAML front matter. Pages in these group are selected in 

    _includes/themes/twitter.default.html

and handed over to 

    _includes/JB/pages_list

Wow!
