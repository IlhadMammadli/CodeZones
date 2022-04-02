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
  bottom: 0;
  background-image: url("..//static/Vector 1.png");
  width: 100%;
  height: 100%;
  height: 345px;
  background-size: 100%;
}

.visualImage {
  position: absolute;
  right: 0;
  background-image: url("..//static/jevi-web-studio-ar-vr 1.png");
  margin-top: -195px;
  margin-right: 115px;
  width: 675px;
  height: 595px;
}

</style>