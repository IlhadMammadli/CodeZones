<template>
  <div clas="headerView">
    <div class="rightTopVector"></div>
    <div class="bottomVector">
       <div class="visualImage"></div>
    </div>
  </div>
</template>
<script>
export default {
  name: "BackgroundImage",
};
</script>

<style>

.headerView {
  display: flex;
  width: 100%;
  height: 700px;
}

.rightTopVector {
  display: flex;
  margin-left: auto;
  background-image: url("..//static/Vector 3.png");
  height: 265px;
  width: 60%;
}

.bottomVector {
  position: absolute;
  top: 0;
  background-image: url("..//static/Vector 1.png");
  width: 100%;
  height: 100%;
  margin-top: 200px;
  background-size: 100%;
  background-repeat: no-repeat;
}

.visualImage {
  position: absolute;
  right: 0;
  top: 0;
  background-image: url("..//static/jevi-web-studio-ar-vr 1.png");
  margin-right: 105px;
  width: 675px;
  height: 595px;
  bottom: 405px;
}

</style>