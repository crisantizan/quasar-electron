<template>
  <div id="q-app">
    <router-view />
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator';

@Component({
  name: 'App',
})
export default class extends Vue {}
</script>

<style>
</style>
