<template>
  <div class="Home">
    <section class="menu">
      <Menu></Menu>
    </section>
    <section class="corpo">
      <principal></principal>
    </section>
  </div>
</template>

<script>
import Menu from "./Menu"
import principal from "./Principal"

export default {
  name: 'Home',
  components: { Menu , principal}
}
</script>

<style scoped>

.menu {
  height: 20vh;
  margin: auto
}

.corpo {
  height: 80vh;
}

</style>
