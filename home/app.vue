<template>
  <div>
    <main-header/>
    <main-content/>
  </div>
</template>
<script>
  import '@/styles/evui.css';

  import mainHeader from './guide/views/header';
  import mainContent from './guide/views/content';

  export default {
    name: 'App',
    components: {
      mainHeader,
      mainContent,
    },
  };
</script>

<style scoped>
  * {
    font-family: 'NanumGothic', Arial, "Helvetica Neue", Helvetica, sans-serif;
  }
</style>
<style>
  body {
    position: absolute;
    width: 100%;
    height: 100%;
  }
</style>
