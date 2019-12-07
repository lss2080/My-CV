<template>
  <div class="introcontent">
    <div class="bg2-img"><img src="../assets/bg1.jpg" :style="{height:introHeight}"></div>
    <div class="midcontent">
      <div class="card">
        <div class="card-body text-center animated flipInX">
          <h1 class="card-title"><img class="introimg" src="../assets/introimg.jpg"></h1>
          <h3 class="card-text">您好，我叫廖诗森，目前在北京。 目前从事产品设计工作，有着一定的编程基础，
            目前能熟练运用<span style="text-decoration: underline;">VUE、AXURE、墨刀、Mindmanager、Xmind</span>等工具软件，
            熟悉<span style="text-decoration: underline;">GIS、遥感、、数据库、Vue框架</span>等的基础，
            能很好的使用工作中的各类工具软件,对前端很感兴趣，具有良好的自学能力，目前的规划是立足专业特点能力，设计出友好的产品服务于社会和用户，
            努力的成为一名优秀的产品设计师！</h3>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'introduce',
  props: ['introHeight']
}
</script>
<style scoped>
.introcontent {
  width: 100%;
  height: 100%;
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
}
.bg2-img {
  position: absolute;
  display: block;
  width: 100%;
  z-index: -1;
}
.bg2-img img{
  width: 100%;
}
.midcontent {
  width: 60%;
}
.card {
  border: none;
  border-radius: 20px;
  background-color: rgba(255, 255, 255, 0);
}
.introimg {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  animation: rotate 10s linear infinite;
}
@keyframes rotate {
  from{
    transform: rotate(0deg);
  }
  to{
    transform: rotate(359deg);
  }
}
.introimg:hover {
  box-shadow: 0 0 16px rgb(255, 102, 0);
}
.card-text {
  font-family: 'STKaiti','Courier New', Courier, monospace;
  font-size: 22px;
  color: #ffffff;
}
</style>
