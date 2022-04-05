<template>
 
    <div class="menuHeader">
      <div class="headerLeft">
        <div class="logo">
          <p class="logo">CodeZone</p>
        </div>
      </div>

      <div class="headerRight">
        <div class="menuBox">
          <ul>
            <li class="menus"><a href="#">Home</a></li>
            <li class="menus"><a href="#">About us</a></li>
            <li class="menus"><a href="#">Services</a></li>
            <li class="menus"><a href="#">News</a></li>
          </ul>
        </div>

        <div class="contactBtn">
          <button class="contactBtn">Contact Us</button>
        </div>
      </div>
    </div>
</template>


<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  outline: none;
  list-style-type: none;
  border: 0;
}

.menuHeader {
  background-color: #e47500;
  display: flex;
  width: 100%;
  height: 70px;
  justify-content: space-between;
  align-items: center;
}

.headerLeft {
  display: flex;
  height: 100%;
  align-items: center;
  color: white;
}

.logo {
  margin-left: 20px;
  font-family: "Roboto", sans-serif;
  font-size: 22px;
}

.headerRight {
  display: flex;
  height: 100%;
  align-items: center;
  margin-right: 30px;
 
}

.contactBtn {
  width: 132px;
  height: 42px;
  margin-right: 20px;
  background-color: white;
  color: #dc7000;
  align-items: center;
  border-color: transparent;
}

.menuBox {
  display: flex;
  height: 100%;
  align-items: center;
}

ul,
li,
a {
  text-decoration: none;
}

ul {
  display: flex;
  align-items: center;
}

li {
  margin-right: 20px;
  width: 120px;
}

a {
  color: white;
  font-size: 18px;
  font-family: "Roboto", sans-serif;
}
</style>

<script>
export default {
  name: "Header",
};
</script>