<template>
    <h1>This message in microfrontend-second comes from app {{ msg }}</h1>
</template>
<script>
export default {
   name: 'TestVue',
  props: {
    msg: String
  },
}
</script>