<template lang="pug">
.pug
  .pug_child
</template>

<script>
export default {
  name: 'HelloWorld',

  props: {
    msg: {
      type: String
    }
  }
}
</script>

<style lang="stylus" scoped> // 單單這條在vue3會報錯: no end tag

</style> // 於是得要給結尾
