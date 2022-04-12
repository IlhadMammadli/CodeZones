<template>
  <div class="headerBackground">
    <div class="topBackground"></div>
    <div class="footerBackground"></div>
    <div class="headerFront">
      <div class="headerFrontLeft">
        <div class="headTitle">
          <p class="title">Digital Margeting</p>
        </div>

        <div class="slogan">
          <p class="sloganText">
            Work that we <br />
            produce for our <br />
            clients
          </p>
        </div>

        <div class="description">
          <p class="descriptionTitle">
            Lorem Ipsum is simply dummy text of the printing and <br/> typesetting
            industry. Lorem Ipsum has been the industry's <br/> standard.
          </p>
        </div>
        <div class="details">
          <button class="getDetails">Get more details</button>
        </div>
      </div>
      <div class="headerFrontRight"></div>
    </div>
  </div>
</template>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,700;1,300&display=swap');


.headerBackground {
  position: relative;
  width: 100%;
  height: 100%;
  margin-top: 0px;
}

.topBackground {
  position: relative;
  float: right;
  background-image: url("..//static/Vector 3.png");
  width: 60%;
  height: 265px;
  background-size: 100%;
  background-repeat: no-repeat;
}

.footerBackground {
  position: absolute;
  width: 100%;
  height: 546px;
  margin-top: 353px;
  background-image: url("../static/Vector 1.png");
  background-repeat: no-repeat;
  background-size: 100%;
}

.headerFront {
  position: relative;
  display: flex;
  width: 80%;
  height: 80%;
  justify-content: space-between;
  margin: 0 auto;
  top: -60px;
}
.headerFrontLeft {
  width: 50%;
  height: 100%;
}

.headerFrontRight {
  display: flex;
  background-image: url("../static/jevi-web-studio-ar-vr 1.png");
  height: 655px;
  width: 50%;
  background-size: 100%;
  background-repeat: no-repeat;
}

.headTitle {
  margin-top: 20px;
}

.title {
  color: #e87d0e;
  font-size: 20px;
  font-family: "Roboto", sans-serif;
}

.slogan { 
  margin-top: 20px;
}

.sloganText { 
  color: #000000;
  font-size: 50px;
  font-family: 'Poppins', sans-serif;

}

.desctiption { 
  margin-top: 20px;
}

.descriptionTitle { 
  color: #000000;
  font-size: 16px;
  font-family: 'Poppins';
  font-weight: lighter;
}

.details { 
  margin-top: 30px;
  
}

.getDetails { 
  background-color: #FA8305;
  color: #ffffff;
  font-size: 16px ;
  width: 195px;;
  height: 53px;
  border-radius: 40px;
}
</style>


<script>
export default {
  name: "BackgroundImage",
};
</script>