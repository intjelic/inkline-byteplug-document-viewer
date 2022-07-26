<template>
  <i-button :loading="true">
      Document Viewer
      <template #loading>
          <i-loader color="dark" class="_margin-right:1/2" />
          Loading
      </template>
  </i-button>
</template>

<script>
export default {
  name: "IDocumentViewer"
}
</script>
