---
layout: default
title: Solenoid
---

<div class="hero">
  <a href="#" id="homeLink">
    <picture>
      <source srcset="/img/solenoid-logo-inverted-optimized.webp" type="image/webp">
      <img src="/img/solenoid-logo-inverted-optimized.png" alt="Solenoid" class="logo">
    </picture>
  </a>
</div>

<script>
  document.getElementById('homeLink').addEventListener('click', function(e) {
    e.preventDefault();
    const browserLang = navigator.language || navigator.userLanguage;
    const lang = browserLang.startsWith('ja') ? 'ja' : 'en';
    window.location.href = '/' + lang + '/about';
  });
</script>
