<template>
  <div>
    <b>this.$route.query</b>>
    <pre>
      {{ this.$route.query }}
    </pre>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
