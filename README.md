# jQuery Slug

```html
<script src="jquery.js"></script>
<script src="slug.js"></script>

<input type ="text" value="" id="slug-source" /> <!-- O texto para o slug -->
<input type ="text" value="" id="slug-target" /> <!-- O texto processado do slug -->

<script>
jQuery(function($) {
  $.slugify("não é assim"); // "nao-e-assim"
  $('#slug-target').slugify('#slug-source'); // Digite enquanto você digita

  $("#slug-target").slugify("#slug-source", {
  	separator: '_' // Se você deseja alterar o separador de hífen (-) para sublinhado (_).
  });
});
</script>
```
