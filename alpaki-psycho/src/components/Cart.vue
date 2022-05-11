<template>
  <div class="drop-shadow-md hover:drop-shadow-xl w-full">
    <div class="bg-white rounded-lg p-4">
      <slot />
    </div>
  </div>
</template>

<script lang="ts">
import { Vue } from "vue-class-component";

export default class Cart extends Vue {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
