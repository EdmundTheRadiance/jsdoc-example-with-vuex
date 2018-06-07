<template>
  <div>
    <p>Hello world!</p>
    <p>foo is: {{ foo }}</p>
  </div>
</template>

<script>
import { mapGetters } from 'vuex';

/**
 * @vue
 */
export default {
  data () {
    return {}
  },
  computed: {
    ...mapGetters(['foo']),
  }
}
</script>

<style lang="scss" scoped>
p {
  font-size: 20px;
}
</style>
