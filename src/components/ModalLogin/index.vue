<template>
<h1>Modal de Login</h1>
</template>

<script>
import { reactive } from 'vue'
export default {
  name: 'ModalLogin',
  setup () {
    const state = reactive({
      hasErrors: false,
      isLoading: false,
      email: {
        value: '',
        errorMessage: ''
      },
      password: {
        value: '',
        errorMessage: ''
      }
    })
  }
}
</script>
