# vue-horizon-suite-viewer

To install the viewer in your Vue 3 project, execute the following command:

```bash
npm i vue-horizon-suite-viewer
```

You will also need to install three.js separately, as it is a peer dependency.

```bash
"peerDependencies": {
  "three": "^0.164.1"
},
```

Then, in your Vue project, use this component:

```vue
<template>
  <HorizonSuiteViewer deployment-id="your-id"/>
</template>

<script>
  import {HorizonSuiteViewer} from "vue-horizon-suite-viewer"
</script>
```

Be sure to replace "your-id" with the deployment ID that you can find in your dashboard.

If you need further modifications or additions, please let me know!