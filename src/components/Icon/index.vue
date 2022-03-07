<template>
  <component :is="name" v-bind="$props"/>
</template>

<script>
import LoadingIcon from './Loading.vue'
import CopyIcon from './Copy.vue'
export default {
  components: { LoadingIcon, CopyIcon },
  props: {
    name: { type: String, required: true }
  }
}
</script>
