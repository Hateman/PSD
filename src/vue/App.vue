<template>
<div>
  <!-- <app-header></app-header> -->
  <app-content></app-content>
</div>
</template>

<script>
import Content from './Content.vue';
// import Header from './Header.vue';


export default {
  components: {
    'app-content': Content,
    // 'app-header': Header,
  },
}

</script>

<style></style>
