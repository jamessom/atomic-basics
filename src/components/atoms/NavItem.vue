<template>
  <a class="nav-item" :src="to">
    {{ text }}
  </a>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'NavItem',
  props: {
    text: {
      type: String,
      required: true,
    },
    to: {
      type: String,
      required: true,
    },
  },
})
</script>

<style lang="scss" scoped>
.nav-item {
  color: #293947;
  text-decoration: none;
  font-size: 1.3rem;
}
</style>
