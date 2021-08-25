<template>
  <header-bar></header-bar>
  <side-bar></side-bar>
  <content></content>
  <footer-bar></footer-bar>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HeaderBar from './components/HeaderBar.vue'
import SideBar from './components/SideBar.vue'
import Content from './components/Content.vue'
import FooterBar from './components/Footer.vue'
export default defineComponent({
  name: 'App',
  components: {
    HeaderBar,
    SideBar,
    Content,
    FooterBar,
  }
})
</script>

<style>

</style>
