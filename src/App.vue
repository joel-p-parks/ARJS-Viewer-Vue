<template>
<div>
  <JSViewer v-bind:report="{ Uri: 'report.rdlx-json'}"></JSViewer>
</div>
</template>

<script>
import { Viewer } from '@grapecity/activereports-vue';

export default {
  name: 'App',
  components: {
    JSViewer: Viewer
  }
}
</script>

<style src="../node_modules/@grapecity/activereports/styles/ar-js-ui.css"></style>
<style src="../node_modules/@grapecity/activereports/styles/ar-js-viewer.css" ></style>

<style>
#viewer-host {
  width: 100%;
  height: 100vh;
}
</style>
