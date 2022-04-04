<template>
   <v-btn :class="buttonType"  size="x-large">
      Test
    </v-btn>

</template>

<script lang='ts'>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Button',
  props: {
    buttonType: String
  }
})
</script>
