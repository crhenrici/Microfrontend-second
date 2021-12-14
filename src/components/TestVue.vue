<template>
  <div>
    <h1>This message in microfrontend-second comes from app {{ msg }}</h1>
    <h1>Config foo: {{ config.foo }}</h1>
  </div>
</template>
<script>
export default {
   name: 'TestVue',
  props: {
    msg: String,
    config: Object,
  },
  mounted() {
    console.log(this.config.foo)
  }
}
</script>