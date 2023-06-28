<template>
  <div>
    <header class="header">
      <!-- 基于原生js实现顶部导航，包括blog、about -->
      <div class="nav">
        <div class="nav-item">
          <router-link to="/">Blog</router-link>
        </div>
        <!-- <div class="nav-item">
          <router-link to="/about">About</router-link>
        </div> -->
      </div>
    </header>

    <!-- 基于原生实现居中包括标题、内容 -->
    <div class="main">
      <div class="title">
        <h1>Jeff Chen</h1>
      </div>
      <div class="content">
        <div>
            <h3>爱好？</h3>
            <div>看看书、打打游戏。</div>
        </div>
        <div>
            <h3>博客？</h3>
            <div>撸的vercel.com，代码存储在github.com</div>
        </div>
        <div>
            <h3>我的技能？</h3>
            <div>懂点编程的皮毛小玩意</div>
        </div>
        <div>
            <h3>我是谁？</h3>
            <div>我是 Jeff Chen,最近瞎折腾搞了2个域名：tt.sb,ll.td</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.header {
    padding:40px;
}
.nav {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  grid-gap: 20px;
  gap: 20px;
  font-size: 16px;
  line-height: 16px;
}
.nav-item a{
    text-decoration: none;
    color: #6e6e6e;
}

.nav-item a:hover{
    color: #6666;
}
.main{
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    padding-left:10%;
    padding-right:10%;
    margin:0 auto;
}
.title{
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
}
.content{
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
}
</style>