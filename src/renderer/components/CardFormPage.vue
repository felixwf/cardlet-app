<template>
  <div id="wrapper">
    <p>this is CardFormPage</p>
  </div>
</template>

<script>
export default {
  name: 'card-form-page',
  components: {},
  methods: {
    open (link) {
      this.$electron.shell.openExternal(link)
    }
  }
}
</script>

<style>
#wrapper {
  background: radial-gradient(
    ellipse at top left,
    rgba(255, 255, 255, 1) 40%,
    rgba(150, 150, 150, 0.9) 100%
  );
  height: 100vh;
  padding: 60px 80px;
  width: 100vw;
}
</style>
