<template>
  <h1>Hello World {{ name }}</h1>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  data() {
    return {
      name: 'cataline',
    }
  },
})
</script>
