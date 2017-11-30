<template>
  <div class="Home">
    <section>
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

Menu {
  height: 30vh;
  margin: 9.5%
}

.corpo {
  height: 100vh;
}

</style>
