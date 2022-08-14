<template>
  <div class="app">
    <Logo />
    <NavBar />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Logo } from '@/components/atoms'
import { NavBar } from '@/components/molecules'

export default defineComponent({
  name: 'App',
  components: { Logo, NavBar },
})
</script>

<style lang="scss" scoped>
.app {
}
</style>
