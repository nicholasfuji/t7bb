---
layout: post
author: ERC
date: 2020-01-02 02:29 +08:00
actions:
    - label: hello
      url: "https://www.google.com"
image: /assets/images/dost.jpg
tags: 
 - russia
categories: 
 - russia

---
dostoevsky

go to [Facebook][face-book].

[face-book]: https://www.facebook.com

* TOC
{:toc}

# header 1
## header 2
### header 3
It will then render the markdown and html titles (lines that begins with `#` or using the `<h1></h1>` tages)


#source of looping posts in index (site.post): https://www.csrhymes.com/development/2017/10/27/multiple-post-types-in-jekyll.html

type (    {% for item in site.posts %}
            <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
             {{ item.excerpt }}
          {% endfor %}      )
