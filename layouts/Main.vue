<template>
  <div class="container">
    <!-- <div class="responsive-nav">
      <ResponsiveNav />
    </div> -->
    <div class="navbar">
      <NavBar />
    </div>
    <div class="main-section">
      <div class="sidebar">
        <SideBar />
      </div>
      <div class="content-section">
        <Nuxt />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main'
}
</script>

<style scoped>
.main-section{
  display: flex;
}
.navbar{
  width: 100%;
  display: block;
}
.content-section{
  width: 100%;
  /* margin: 108px 0px 0px 316px; */
  /* padding-bottom: 5%; */
  background-color: #FBFCFF;
}
.side-bar{
  display: block;
}
</style>

/* @media screen and (max-width:800px){
  .sidebar{
    display: none;
  }
  .navbar{
    display: none;
  }
  .content-section{
    margin: 0;
    width: 90%;
    margin: auto;
  }
  .responsive-nav{
    display: block;
    width: 100%;
  }
  .responsive-sidebar{
    display: block;
    width: 100%;
  } */
/* }   */