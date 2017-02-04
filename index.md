---
layout: default
---
<h1 class="headline">{{site.title}}</h1>


> All the faith he had had had had no effect on the outcome of his life.


## Projects

 - [A Blog](http://t-ls.herokuapp.com/)
 - [Google Search](https://thiagolu.github.io/alpha-webs/)
 - [A Blog](http://t-ls.herokuapp.com/)
 - [Stock Tracker](https://polar-shelf-96927.herokuapp.com/users/sign_in)



## Posts


{% for post in site.posts %}
<h3><a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a></h3>
{% endfor %}
