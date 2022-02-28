<template>
  <component :is="name" v-bind="$props"/>
</template>

<script>
import LoadingIcon from './Loading.vue'
export default {
  components: { LoadingIcon },
  props: {
    name: { type: String, required: true }
  }
}
</script>
