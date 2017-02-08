---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

<!-- <script src="//cdn.ckeditor.com/4.6.2/full-all/ckeditor.js"></script> -->
<script src="{{ site.url }}/assets/ckeditor/ckeditor.js"></script>

<textarea name="editor1"></textarea>

<script>
CKEDITOR.replace( 'editor1' ,{
});
CKEDITOR.editor.appendText("hello ");
CKEDITOR.editor.insertHtml('<a href="//www.so.com">link</a>');

</script>
