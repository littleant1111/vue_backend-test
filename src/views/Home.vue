<template>
  <div class="home">
    <button-test></button-test>
  </div>
</template>

<script>
  import ButtonTest from "./childcomponts/ButtonTest";
export default {
  name: 'Home',
  components: {
    ButtonTest
  }
}
</script>
