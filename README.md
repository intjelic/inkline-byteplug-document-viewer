# Inkline Byteplug Document Viewer

This is a Vue.js component to display a JSON document with a YAML specs as
defined by the Document Validator standard from Bytpelug. It's not technically
an Inkline component but instead it uses Inkline components; therefore it
depends on it.


```
npm install inkline-byteplug-document-viewer
```

## How to use

```vue
<script>
import IDocumentViewer from 'inkline-byteplug-document-viewer'

export default {
  name: "MyApp",
  components: {
    IDocumentViewer
  }
}
</script>

<template>
  <i-document-viewer/>
</template>
```
