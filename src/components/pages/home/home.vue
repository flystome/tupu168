<template>
  <div id="home">
    <Banner></Banner>
    <section>
      <ul class="tab">
        <li>风格</li>
        <li>空间</li>
        <li>户型</li>
      </ul>
      <List></List>
    </section>
  </div>
</template>

<script>
import Banner from './banner/banner'
import List from './list/list'

export default {
  name: 'home',
  data () {
    return {

    }
  },
  components: {
    Banner,
    List
  }
}
</script>

<style scoped style="scss">
  @import 'home.scss';
</style>
