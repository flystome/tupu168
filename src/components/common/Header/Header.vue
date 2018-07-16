<template>
  <header class="clearfix">
    <div class="w1200">
      <a href="###" class="logo">
        <img src="Img/logo.png">
      </a>
      <div class="link">
        <ul>
          <li><a href="/">首页</a></li>
          <li><a href="">找设计师</a></li>
          <li><a href="/">找设计公司</a></li>
        </ul>
      </div>
      <div class="setting">

      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {

    }
  }
}
</script>

<style scoped lang="scss">
  header {
    width: 100%;
    height: 50px;
    background: #ffd100;
    .logo {
      display: inline-block;
      float: left;
      width: 15%;
      height: 50px;
      text-align: left;
      vertical-align: middle;
      img {
        vertical-align: middle;
      }
    }
    .link {
      width: 50%;
      height: 50px;
      line-height: 50px;
      ul {
        li {
          float: left;
          padding: 0 15px;
        }
      }
    }
  }
</style>
