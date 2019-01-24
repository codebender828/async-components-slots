<template>
  <!-- <div>
    {{ greeting }}
    <child>
      <h4 slot="title">I am slot component title</h4>
      <p slot="text-1" >Slot text paragraph.</p>
      <p slot="text-2">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ipsum, ullam quaerat. Id odio ducimus maxime nostrum cum? Obcaecati, qui iusto?</p>
    </child>
  </div> -->
  <div></div>
</template>

<script>
import Child from '@/components/Child.vue';

export default {
  name: 'Home',
  components: {
    Child,
  },
  data () {
    return {
      greeting: 'Hello World'
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
