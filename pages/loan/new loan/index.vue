<template>
  <div class="container">
    <table>
      <div class="table-top">
        <p class="table-top-text">New Loans Collected</p>
        <div class="filter">
          <p class="results">Filter Results</p>
          <img src="~/assets/icons/filter.svg" alt="filter" class="lines">
        </div>
      </div>
      <div>
        <tr class="table-head">
          <th class="user td-th">User ID</th>
          <th class="reg-date td-th">Full Name</th>
          <th class="full-name td-th">Email Address</th>
          <th class="email td-th">Collection Date</th>
          <th class="td-th">Loan Collected</th>
        </tr>
        <tr v-for="el in tableElements" :key="el.userId" class="table-body">
          <td class="user td-th">{{ el.userId }}</td>
          <td class="reg-date td-th">{{ el.fullName }}</td>
          <td class="full-name td-th">{{ el.email }}</td>
          <td class="email td-th">{{ el.regDate }}</td>
          <td class="user-type td-th">
            {{ el.loanCollected }}
          </td>
        </tr>
      </div>
      <!-- <div v-show="activeTab == 'candidates-tab'" class="tab-2">
        <CandidateTable />
      </div> -->
    </table>
  </div>
</template>

<script>
  export default {
    layout:'Main',
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
.container{
  margin: 189px 115px 240px 305.5px;
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
</style>