---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

<!-- <script src="//cdn.ckeditor.com/4.6.2/full-all/ckeditor.js"></script> -->

<!-- <script src="{{ site.url }}/assets/ckeditor/ckeditor.js"></script>

<textarea name="editor1"></textarea>

<script>
CKEDITOR.replace( 'editor1' ,{
});
CKEDITOR.editor.appendText("hello ");
CKEDITOR.editor.insertHtml('<a href="//www.so.com">link</a>'); -->
<!-- </script> -->
{% for post in site.posts %}
<div>
<h1> <a href="{{post.url | relative_url}}">{{ post.title }} </a></h1>
<p> {{ post.description }} </p>
</div>
{% endfor %}

{% for article in site.tech_node %}
<div>
<h1> <a href="{{article.url | relative_url}}">{{ article.title }} </a></h1>
</div>
{% endfor %}
