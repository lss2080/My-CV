<template>
  <div class="skillcontent">
    <div class="bg3-img">
      <img src="../assets/bg3.jpg" :style="{height:skillHeight}">
    </div>
    <div class="midcontent animated flipInX">
      <div class="skilltitle display-4 shake-rotate">Skills:</div>
      <h5
        class="skillhover shake-little"
        style="width: 100px;background-color: #0e82ff;padding:2px 5px;border-radius:7px;"
      >脑图工具</h5>
      <div class="progress">
        <div class="progress-bar progress-bar-striped progress-bar-animated" style="width:100%"></div>
      </div>
      <br>
      <h5
        class="skillhover shake-little"
        style="width: 100px;background-color: #29a746;padding:2px 5px;border-radius:7px;"
      >原型设计</h5>
      <div class="progress">
        <div
          class="progress-bar bg-success progress-bar-striped progress-bar-animated"
          style="width:100%"
        ></div>
      </div>
      <br>
      <h5
        class="skillhover shake-little"
        style="padding-bottom:5px; width: 102px;background-color: #17a2b8;padding:2px 5px;border-radius:7px;"
      >办公软件</h5>
      <div class="progress">
        <div
          class="progress-bar bg-info progress-bar-striped progress-bar-animated"
          style="width:100%"
        ></div>
      </div>
      <br>
      <h5
        class="skillhover shake-little"
        style="padding-bottom:5px; width: 101px;background-color: #ffc107;padding:2px 5px;border-radius:7px;"
      >BootStrap</h5>
      <div class="progress">
        <div
          class="progress-bar bg-warning progress-bar-striped progress-bar-animated"
          style="width:70%"
        ></div>
      </div>
      <br>
      <h5
        class="skillhover shake-little"
        style="padding-bottom:5px; width: 100px;background-color: #dc3545;padding:2px 5px;border-radius:7px;"
      >行业软件</h5>
      <div class="progress">
        <div
          class="progress-bar bg-danger progress-bar-striped progress-bar-animated"
          style="width:80%"
        ></div>
      </div>
      <br>
      <h5
        class="skillhover shake-little"
        style="padding-bottom:5px; width: 106px;background-color: #343a40;padding:2px 5px;border-radius:7px;"
      >自学能力</h5>
      <div class="progress">
        <div
          class="progress-bar bg-dark progress-bar-striped progress-bar-animated"
          style="width:90%"
        ></div>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    name: 'skilll',
    props: ['skillHeight']
  }
</script>
<style scoped>
  .skillcontent {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100%;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .bg3-img {
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: -1;
  }
  .bg3-img img {
    width: 100%;
  }
  .midcontent {
    width: 70%;
    color: #ffffff;
  }
  .skilltitle {
    position: relative;
    width: 170px;
    top: -20px;
    left: 40%;
    background-color: rgba(247, 0, 255, 0.5);
    text-align: center;
    padding-top: 7px;
    padding-bottom: 1px;
    border-radius: 10px;
    font-family: "Kristen ITC", "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    cursor: pointer;
  }
  .skillhover:hover {
    cursor: pointer;
    box-shadow: 0 0 16px rgba(225, 0, 255, 0.644);
  }
</style>
