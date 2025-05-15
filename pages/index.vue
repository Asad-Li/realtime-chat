<template>

</template>
<script>
import { useWebSocket } from '@vueuse/core'

const { status, data, close } = useWebSocket('ws://localhost:3000/_ws', {
  heartbeat: {
    message: 'ping',
    interval: 1000,
    pongTimeout: 1000,
  },
})

</script>


