<template>
  <div class="serviceBox">
    <div class="serviceTitle">
        <p>Xidmetler</p>
      <div class="services"></div>
      <ul>
        <li v-for="item in itemLists" :key="item.message">
          {{ item.message }}
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default { 
    name: "Services",
    data() { 
        return { 
            itemLists: [
               {message: "Saytların hazırlanması"},
               {message: "Veb və mobil proqramların hazırlanması"},
               {message: "Texniki dəstək"}
             ]
        };
    },
    
}

</script>


<style>
.serviceBox {
  margin-top: 20px;
  width: 40%;
  margin-left: auto;
  margin-right: auto;
  height: 300px;
}

.serviceTitle { 
    width: 300px;
    height: 40px;
    margin-right: auto;
    margin-left: auto;
}
ul,
li {
  text-decoration-style: none;
}

li {
  position: relative;
  display: block;
  float: left;
}
</style>