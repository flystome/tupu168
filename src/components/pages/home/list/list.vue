<template>
  <div id="list">
    <ul class="clearfix">
      <li>
        <div class="item">
          <div class="item-img">
            <img src="~Img/list1.png" alt="">
          </div>

        </div>
      </li>
      <li>asdfhiw</li>
      <li>asdfhiw</li>
      <li>asdfhiw</li>
      <li>asdfhiw</li>
      <li>asdfhiw</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'list',
  data () {
    return {

    }
  }
}
</script>

<style scoped lang='scss'>
  #list {
    width: 1200px;
    margin: 0 auto 0px;
    ul {
      width: 100%;
      margin-left: -20px;
      li {
        width: 20%;
        float: left;
        padding-left: 20px;
        box-sizing: border-box;
      }
    }
  }
</style>
