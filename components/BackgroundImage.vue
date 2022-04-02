<template>
  <div class="backgroundImage">
    <div class="slogan">
      <p class="slogan-title">We Made Bigger Your Company</p>
    </div>
  </div>
</template>
<script>
export default {
  name: "BackgroundImage",
};
</script>

<style>
.backgroundImage {
  position: relative;
  margin-top: 0px;
  width: 100%;
  height: 344px;
  background-image: url(../static/backgroundImage.jpg);
  background-attachment: fixed;
  background-size: 100% 70%;
}

.slogan {
  display: block;
  position: relative;
  top: 90px;
  margin-left: auto;
  margin-right: auto;
  width: 40%;
  height: 200px;
}

.slogan-title {
  text-align: center;
  color: white;
  font-family: "Roboto", sans-serif;
  font-size: 40px;
}
</style>