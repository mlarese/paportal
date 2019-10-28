<template>
  <div class="iframe-container">
    <iframe :src="src" />
  </div>
</template>

<script>
// import AsyncIframe from 'vue-friendly-iframe'

export default {
  // components: { AsyncIframe },
  data () {
    return {
      src: 'https://www.bing.com'
    }
  },
  methods: {
    onLoad () {

    },
    onDocumentLoad () {

    }
  }
}
</script>
