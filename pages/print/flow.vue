<template>
  <flow-pc />
</template>

<script lang="ts">
import Vue from 'vue'
import { MetaInfo } from 'vue-meta'
import FlowPc from '@/components/flow/FlowPc.vue'
export default Vue.extend({
  components: {
    FlowPc
  },
  layout: 'print',
  head(): MetaInfo {
    return {
      title: this.$t(
        '新型コロナウイルス感染症にかかる相談窓口について'
      ) as string
    }
  }
})
</script>
