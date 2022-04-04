<template>
  <side-menu />
  <Button buttonType="primary" />
  <br/>
    <br/>
  <Button buttonType="secondary" />
    <br/>
      <br/>
  <Button buttonType="tertaire" />       
</template>

<script lang="ts">
import { defineComponent } from 'vue';

// Components
import SideMenu from '../components/SideMenu.vue';
import Button from '../components/Button.vue'

export default defineComponent({
  name: 'HomeView',

  components: {
    SideMenu,
    Button
  },
});
</script>
