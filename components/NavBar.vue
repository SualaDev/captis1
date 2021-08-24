<template>
  <div class="nav">
    <div class="lhs">
      <h4 class="header-name">DASHBOARD</h4>
    </div>  
    <div class="rhs">
      <div class="search-box">
        <img src="~/assets/icons/search.svg" alt="search-icon" class="search">
        <input class="search-input" type="text" name="search-input" placeholder="Search transactions...">
      </div>
      <div class="icons">
        <img src="~/assets/icons/upload (2) 1.svg" alt="dropbox" class="upload">
        <img src="~/assets/icons/ic_baseline-notifications.svg" alt="bell-notification" class="notification">
      </div>  
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.nav{
  height: 82.75px;
  background-color: #FBFCFF;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  border-bottom: 1px solid #E6E8ED;
  /* margin-bottom: 108px; */
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 2;
}
.lhs{
  float: left;
  margin-left: 317px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 107px;
  font-weight: 700;
  color: #344563;
}
.rhs{
  width:500px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
/* .search-box{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items:center;
} */
.search-box{
  border: 1.5px solid #ECECEC;
  width: 349px;
  height: 56px;
  background-color: #FBFCFF; 
  border-radius: 4px;
  display: flex;
  flex-direction: row;
  /* justify-content: space-around; */
  align-items: center;
}

.search {
  padding: 0 20px;
}

.search-box input {
  background: transparent;
  border: none;
  outline: none;
  font-size: 16px;
}
.icons{
  width: 75px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  margin-right: 20px;
}
</style>