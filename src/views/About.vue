<template>
  <div class="about">
    <h1>This is an about page</h1>
    <CheckBox msg="male"/>
  </div>
</template>

<script>

import CheckBox from '@/components/CheckBox.vue'

export default {
  name: 'About',
  components: {
    CheckBox
  }
}
</script>

<style>

</style>
