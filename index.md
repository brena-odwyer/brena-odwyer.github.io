---
layout: home
---
<script>
var userLang = navigator.language || navigator.userLanguage;
if (userLang === 'pt-BR') {
  window.location = '{{ "/pt" | relative_url }}'
} else {
  window.location = '{{ "/en" | relative_url }}'
}
</script>

