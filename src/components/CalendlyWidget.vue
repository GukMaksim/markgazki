<template>
  <div class="calendly-inline-widget min-w-[320px] h-[700px]" data-url="https://calendly.com/mark-gazki/30min?hide_event_type_details=1&hide_gdpr_banner=1"></div>
</template>

<script setup lang="ts">
import { onMounted } from 'vue'

onMounted(() => {
  const script = document.createElement('script')
  script.type = 'text/javascript'
  script.src = 'https://assets.calendly.com/assets/external/widget.js'
  script.async = true
  document.head.appendChild(script)
})
</script>
