<template>
  <div class="app">
    Hello, {{name}}
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App',
  components: {},
  data(){
    return {
      name: 'Link'
    }
  },
  methods: {
    changeName(name: string){
      this.name = name
    }
  }
});
</script>

<style>
</style>
