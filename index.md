---
layout: default
---
<h1 class="headline">marketing 20T Titulo do site</h1>


<div id="classico-19-04-2018-20-58-e27194d5d6d46436a772"></div>
<script type="text/javascript" src="https://d335luupugsy2.cloudfront.net/js/rdstation-forms/stable/rdstation-forms.min.js"></script>
<script type="text/javascript">
  new RDStationForms('classico-19-04-2018-20-58-e27194d5d6d46436a772-html', 'UA-39884858-1').createForm();
</script>


> All the faith he had had had had no effect on the outcome of his life.


## <a name="projects"></a> Projects

Rails Studies

 - [A Blog](http://t-ls.herokuapp.com/)
 - [Stock Tracker](https://polar-shelf-96927.herokuapp.com/)
 - [Eletronic Wallet](https://personalf.herokuapp.com/)

## <a name="posts"></a> Posts

Some posts about the piras

{% for post in site.posts %}
<h3><a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a></h3>
{% endfor %}
