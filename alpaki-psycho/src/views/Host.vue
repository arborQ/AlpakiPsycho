<template>
  <div class="w-1/2 mx-auto">
    <Cart>lol</Cart>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Cart from "@/components/Cart.vue";

@Options({
  components: { Cart },
})
export default class Host extends Vue {}
</script>
