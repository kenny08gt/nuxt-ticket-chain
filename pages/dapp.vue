<template>
  <div class="isolate bg-white">
    <Navbar />
    <main>
      <div class="relative px-6 lg:px-8">
        <div class="mx-auto max-w-3xl pt-20 pb-32 sm:pt-48 sm:pb-40">
          <h2>First, lets connect your wallet</h2>
        </div>
      </div>
    </main>
    <Footer />
  </div>
</template>
<style lang="scss">
main {
  min-height: calc(100vh - 355px);
}
</style>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'Dapp',
  data() {
    return {}
  },
  mounted() {},
  methods: {
    signClientMethod: async function () {},
  },
})
</script>
