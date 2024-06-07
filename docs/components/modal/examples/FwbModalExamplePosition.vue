<template>
  <div class="flex flex-wrap justify-start gap-2 vp-raw">
    <span>
      <fwb-modal-example
        position="bottom-left"
        trigger-text="Bottom Left"
      />
    </span>
    <span>
      <fwb-modal-example
        position="bottom-right"
        trigger-text="Bottom Right"
      />
    </span>
    <span>
      <fwb-modal-example
        position="bottom-center"
        trigger-text="Bottom Center"
      />
    </span>
    <span>
      <fwb-modal-example
        position="top-left"
        trigger-text="Top Left"
      />
    </span>
    <span>
      <fwb-modal-example
        position="top-center"
        trigger-text="Top Center"
      />
    </span>
    <span>
      <fwb-modal-example
        position="top-right"
        trigger-text="Top Right"
      />
    </span>
    <span>
      <fwb-modal-example
        position="center-left"
        trigger-text="Center Left"
      />
    </span>
    <span>
      <fwb-modal-example
        position="center"
        trigger-text="Center"
      />
    </span>
    <span>
      <fwb-modal-example
        position="center-right"
        trigger-text="Center Right"
      />
    </span>
  </div>
</template>

<script setup>
import FwbModalExample from './FwbModalExample.vue'
</script>
