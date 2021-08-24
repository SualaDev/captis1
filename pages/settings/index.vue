<template>
  <div class="container">
    <p class="profile">Update your Profile</p>
    <img src="~assets/icons/man.svg" alt="male-icon" class="man">
    <div class="f-name">
       <label for="full-name">Fullname</label>
      <input v-model="Fullname" type="text" name="name" class="place-name" placeholder="Please enter fullname">
    </div>
    <div class="e-address">
       <label for="email-address">Email Address</label>
      <input v-model="EmailAddress" type="text" name="name" class="place-email" placeholder="Please enter email address">
    </div>
    <div class="p-number">
       <label for="phone-number">Phone Number</label>
      <input v-model="PhoneNumber" type="text" name="name" class="place-number" placeholder="Please enter phone number">
    </div>
    <div class="n-password">
      <label for="new-password">New Password</label>
      <input v-model="NewPassword" type="number" name="name" class="placename" placeholder="***************************">
    </div>
    <div class="c-password">
      <label for="confirm-password">Confirm Password</label>
      <input v-model="ConfirmPassword" type="text" name="name" class="placename" placeholder="***************************">
    </div>
    <label class="grayed-text">
          Two Factor Authentication
    </label>
      <div class="auth-sect">
        <p>SMS Authentication</p>
        <div class="switch-container">
        <input id="switch" type="checkbox">
        <label for="switch" class="switch-btn">
          <!-- <span>
           On
          </span>
          <span>
           Off
          </span> -->
        </label>
         </div>
      </div>
      <div class="auth-sect">
          <!-- <img src="~/assets/icons/google.svg" alt=""> -->
        <p>Google Authentication</p>
        <div class="switch-container">
        <input id="switch" type="checkbox">
        <label for="switch" class="switch-btn">
        </label>
        </div>  
          <!-- <ToggleButton color="#3D82F0" @change="setGoogleAuth()" /> -->
      </div>
      <button>
          SAVE
      </button>
  </div>
</template>

<script>
  export default {
    layout:'Main',
    data () {
    return {
      googleAuth: false,
      smsAuth: false,
      Fullname: '',
      EmailAddress: '',
      PhoneNumber: '',
      NewPassword: '',
      ConfirmPassword: ''
    }
  },
  methods: {
    setGoogleAuth () {
      !this.googleAuth ? this.googleAuth = true : this.googleAuth = false
    },
    setSmsAuth () {
      !this.smsAuth ? this.smsAuth = true : this.smsAuth = false
    }
  } 
  }
</script>

<style scoped>
.container{
  margin: 166px 371px 152px 649px;
}
.profile{
  font-size: 34px;
  font-weight: 300;
  text-align: center;
  color: #110580;
}
.man {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 120px;
  background: #F4F5FA;
  border-radius: 150px;
}
label{
  font-size: 18px;
  font-weight: 400;
  color: #9097A5;
  margin-bottom: 9.93px;
}
.f-name,.e-address,.p-number,.n-password,.c-password,.grayed-text,.auth-sect{
  display: flex;
  flex-direction: column;
  margin-left: 100px;
}
.grayed-text{
  margin-bottom: 56.6px;
}
.auth-sect{
  font-size: 18px;
  font-weight: 600;
  color: #5D6970;
  margin-bottom: 88.8px;
}
.c-password{
  margin-bottom: 71.49px;
}
input{
  width: 450px;
  height: 64.54px;
  border-radius: 8px;
  border: 1px solid #F6F6F9;
  background-color: #FFFFFF;
  margin-bottom: 23.83px;
  padding-left: 24px;
}
.auth-sect {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    margin-top: 25px;
    /* border:1px solid red; */
    position: relative;
    width: 450px;
  }

  .switch-container {
  width: 61px;
  height: 28px;
  display: flex;
  position: relative;
  /* top: 50%;
  left: 50%; */
}

#switch {
  opacity: 1;
  width: 0;
  height: 0;
  position: absolute;
  z-index: 1;
}

.switch-btn {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: 
#3245B8;
  border-radius: 100px;
  padding: 0px 0.4375rem 0px 0.4375rem;
}

.switch-btn:before {
  content: "";
  width: 21px;
  height: 21px;
  border-radius: 50%;
  position: absolute;
  left: 58%;
  margin-top: -1px;
  background: 
#FFFFFF;
  transition: .5s;
}

#switch:checked + .switch-btn:before {
  left: 6%;
  background: #000000;
}

.switch-container span {
  font-size: 11px; 
}

.switch-container .switch-btn span:nth-child(1) {
  color: #09AB5D;
}
button{
  margin-left: 100px;
  width: 450px;
  height: 64.54px;
  border-radius: 4px;
  color: #FFFFFF;
  background-color: 
  #3245B8;
  cursor: pointer;

}
</style>