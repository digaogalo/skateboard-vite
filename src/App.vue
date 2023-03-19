<script setup lang="ts">
</script>

<template>
  <h1 class="text-3xl font-bold underline bg-red-300">
    Hello world!
  </h1>
  <MyComponent />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import MyComponent from './components/MyComponent.vue'

export default defineComponent({
  name: 'App',
  components: {
    MyComponent
  },
})
</script>



