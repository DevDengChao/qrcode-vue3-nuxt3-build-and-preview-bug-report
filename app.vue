<script>
import QRCodeVue3 from "qrcode-vue3"

export default defineComponent({
  components: {
    // Manually register component,
    // otherwise "Failed to resolve component: QRCodeVue3. Hydration node mismatch."
    QRCodeVue3
  }
})
</script>

<template>
  <QRCodeVue3 value="hello world"/>
</template>
