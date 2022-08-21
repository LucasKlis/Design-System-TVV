<template>
  <h1>
    Hello world, I am form!
  </h1>
<input v-model="text">
</template>
<script>
export default {
  setup() {
    data(){
      return{
        header: "Vue is ready to party!"
      }
    }
  },
}
.mount('Form')
</script>