<template>
  <div class="container">
    <div class="sub-container">
      <div class="welcome">
      <img src="~assets/icons/yellowdog.svg" alt="yellowdog" class="yellow">
      <div class="text">
        <p class="name">Hello Oluwaseun,</p>
        <div class="risky">
          <p class="stats">These are stats for</p>
        <div class="date">
          <p class="today">Today</p>
          <img src="~assets/icons/Vector.svg" alt="" class="dropdownicon">
        </div>
        </div>
      </div>
    </div>
    <Cards />
    <Table />
    </div>
  </div>
</template>

<script>
  export default {
    layout: 'Main',
  }
</script>

<style scoped>
*{
  padding: 0px;
  margin: 0px;
}
.container{
  background-color: #FBFCFF;
  z-index: 4;
}
.sub-container{
  margin: 108px 0 0 316px;
}
.yellow{
  border-radius: 50%;
  margin-right: 24px;
  /* margin-top: 90px; */
}
.text{
  margin-top: 10px;
}
.name{
  font-size: 24px;
  font-weight: 600;
  color:#000000;
}
.date{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  width: 124px;
  height: 35px;
  border: 1px solid #DADADA;
  border-radius: 30px;
  background-color: #FFFFFF;
  margin-left: 12px;
}
.today{
  font-weight: 500;
  font-size: 18px;
  color: #39393A;
}
.stats{
  color: #898A8D;
  font-weight: 500;
  font-size: 18px;
}
.welcome{
  display: flex;
  flex-direction: row;
  /* padding-bottom: 108px; */
}
.risky{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  /* margin-top: 16px; */
}
</style>