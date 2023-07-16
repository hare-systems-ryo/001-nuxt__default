<script setup lang="ts">
useHead({
  htmlAttrs: { lang: () => 'ja', prefix: 'og: http://ogp.me/ns#' },
  meta: [
    { 'http-equiv': 'refresh', content: '' },
    { name: 'viewport', content: 'width=device-width, initial-scale=1.0,maximum-scale=1.0' },
    { name: 'keywords', content: () => 'keywords' },
    { name: 'format-detection', content: 'telephone=no' },
    { name: 'theme-color', content: '#FFF' },
    { hid: 'robots', name: 'robots', content: 'noindex' },
  ],
  link: [],
  script: [],
  noscript: [{ children: 'JavaScript is required' }],
  title: '',
  bodyAttrs: {
    class: () => 'lang-ja',
  },
});
</script>
<template>
  <div class="test1">
    <div class="">aaaaa</div>
    <div class="">aaaaa</div>
    <div class="test2">aaaaa</div>
  </div>
</template>

<style lang="scss" scoped>
.test1 {
  background-color: rgb(255, 255, 255);
  padding: 10px;
  .test2 {
    background-color: rgb(185, 185, 255);
  }
}
</style>
