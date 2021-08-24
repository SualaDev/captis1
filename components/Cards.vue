<template>
  <div class="cards">
    <div class="card-container">
      <div class="card">
        <div class="card-details">
          <p class="card-number">Total Loan Collected</p>
          <p class="card-text">7800</p>
        </div>
      </div>
      <div class="card">
        <div class="card-details">
          <p class="card-number">Total Repayed Loan</p>
          <p class="card-text">800</p>
        </div>
      </div>
      <div class="card">
        <div class="card-details">
          <p class="card-number">Total Transactions </p>
          <p class="card-text">7800</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'Main',
  data() {
    return {
      tableElements: [
        {
          userId: '#1927hf',
          fullName: 'Courtney Henry',
          email: 'Courtneyhenry@gmail.com',
          regDate: '22,JAN. 2021 - 3:34PM',
          loanCollected: '1,000,000'
        },
        {
          userId: '#1927hf',
          fullName: 'Wade Warren',
          email: 'Wadewarren@gmail.com',
          regDate: '22,JAN. 2021 - 3:34PM',
          loanCollected: '500,000,000'
        },
        {
          userId: '#1927hf',
          fullName: 'Lesile Alexander',
          email: 'Lesilealexander@gmail.com',
          regDate: '22,JAN. 2021 - 3:34PM',
          loanCollected: '500,000'
        },
        {
          userId: '#1927hf',
          fullName: 'Jacob Jones',
          email: 'Jacobjones@gmail.com',
          regDate: '22,JAN. 2021 - 3:34PM',
          loanCollected: '900,000'
        },
        {
          userId: '#1927hf',
          fullName: 'Bessie Cooper',
          email: 'Bessiecooper@gmail.com',
          regDate: '22,JAN. 2021 - 3:34PM',
          loanCollected: '500,000'
        },
        {
          userId: '#1927hf',
          fullName: 'Brooklyn Simmons',
          email: 'Brookynsimmons@gmail.com',
          regDate: '22,JAN. 2021 - 3:34PM',
          loanCollected: '600,000'
        },
      ],
    }
  },
}
</script>

<style scoped>
.card-container {
  display: flex;
  margin-top: 71px;
}
.card {
  display: flex;
  background-color: #3245B8;
  padding: 46px 32px;
  border-radius: 8px;
  align-content: flex-start;
  width: 266px;
  height: 100px;
  margin-right: 64px;
  box-shadow: 0px 4px 8px rgba(50, 69, 184, 0.33);
}

.card-details {
  margin-left: 24px;
}

.card-number {
  font-size: 18px;
  font-weight: 500;
  color: #FFFFFF;
}

.card-text {
  color: #FFFFFF;
  margin-top: 16px;
  font-size: 32px;
  font-weight: 700;
}
table {
  margin-top: 77px;
  width: 1023px;
  height: 612px;
  background-color: white;
  border-radius: 8px;
  text-align: left;
  border: 1px solid #E6E8ED;
  /* margin-left: 101px; */
}
.lines {
  width: 20px;
}
.filter{
  background-color: #3245B8;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
  width: 160px;
  height: 45px;
  border-radius: 4px;
}
.results{
  font-size: 13px;
  font-weight: 500;
  color: #FFFFFF;
}
.table-top {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 18px 40px;
  border-bottom: 1px solid #E6E8ED;
}

.table-top-text {
  font-size: 16px;
  font-weight: 300;
}

.table-head {
  background-color: #FFFFFF;
  /* border: 1px solid #E6E8ED; */
  padding: 0 40px;
}

tr {
  display: flex;
  padding: 0 40px;
}

th {
  font-weight: 600;
  color: #39393A;
  /* padding: 15px; */
}
/* td{
  padding: 15px;
} */

.td-th {
  padding: 25px 15px;
  width: 23%;
  display: flex;
  color: #39393A;
  /* margin-right: 2%; */
}

.user {
  width: 15%;
}

.email {
  width: 28%;
}

.user-type {
  /* color: rgba(247, 148, 29, 1); */
}
</style>