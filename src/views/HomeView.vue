<template lang="pug">
| Home Page
</template>

<script lang="ts">
  import { defineComponent, computed, ref, onMounted, watch } from "vue"
  import TierOne from "@/components/TierOne.vue"

  export default defineComponent({
    props: {},
    components: { TierOne },
    setup(props, ctx) {
      return {

      }
    }
  })
</script>
