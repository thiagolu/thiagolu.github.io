---
layout: default
---
<h1 class="headline">marketing 20T Titulo do site</h1>


> All the faith he had had had had no effect on the outcome of his life.


## <a name="projects"></a> Projects

Rails Studies

 - [Google Search](https://thiagolu.github.io/alpha-webs/)
 - [A Blog](http://t-ls.herokuapp.com/)
 - [Stock Tracker](https://polar-shelf-96927.herokuapp.com/)
 - [Eletronic Wallet](https://personalf.herokuapp.com/)

## <a name="posts"></a> Posts

Some posts about the piras

{% for post in site.posts %}
<h3><a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a></h3>
{% endfor %}
