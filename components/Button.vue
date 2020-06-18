<template lang="pug">
  button.button(@click="onClick") ボタン
</template>

<script>
export default {
  methods: {
    onClick() {
      alert("click!!");
    }
  }
};
</script>

<style lang="sass" scoped>
.button
  width: 300px
</style>
