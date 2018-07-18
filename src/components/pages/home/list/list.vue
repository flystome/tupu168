<template>
  <div id="list">
    <ul class="clearfix">
      <li>
        <div class="item">
          <div class="item_img">
            <img src="~Img/list1.png" alt="">
          </div>
          <div class="item_detail">
            <p class="title">&laquo;萌芽熊&raquo;  喜欢你</p>
            <p class="kind">动漫-三维动画</p>
            <ul class="action clearfix">
              <li><i class="fa fa-comment-alt"></i><span class='num'></span></li>
              <li><i class="fa fa-eye"></i><span class='num'></span></li>
              <li><i class="fa fa-thumbs-up"><span class='num'></span></i></li>
            </ul>
          </div>
          <div class="item_author">
            <p><span class='photo'></span></span><span class="name"></span></p>
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
  @import './list.scss';
</style>
