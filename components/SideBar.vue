<template>
  <div class="side-bar">
    <img src="~assets/icons/image.svg" alt="captis-logo" class="image">
    <div class="menu-links">
      <NuxtLink to="/" class="lnk">
          <svg width="18" height="18" viewBox="0 0 18 18"  xmlns="http://www.w3.org/2000/svg" class>
          <path fill-rule="evenodd" clip-rule="evenodd" d="M1.5 2.25C1.5 1.83579 1.83579 1.5 2.25 1.5H7.5C7.91421 1.5 8.25 1.83579 8.25 2.25V7.5C8.25 7.91421 7.91421 8.25 7.5 8.25H2.25C1.83579 8.25 1.5 7.91421 1.5 7.5V2.25ZM3 3V6.75H6.75V3H3Z" />
          <path fill-rule="evenodd" clip-rule="evenodd" d="M9.75 2.25C9.75 1.83579 10.0858 1.5 10.5 1.5H15.75C16.1642 1.5 16.5 1.83579 16.5 2.25V7.5C16.5 7.91421 16.1642 8.25 15.75 8.25H10.5C10.0858 8.25 9.75 7.91421 9.75 7.5V2.25ZM11.25 3V6.75H15V3H11.25Z" fill="#39393A"/>
          <path fill-rule="evenodd" clip-rule="evenodd" d="M9.75 10.5C9.75 10.0858 10.0858 9.75 10.5 9.75H15.75C16.1642 9.75 16.5 10.0858 16.5 10.5V15.75C16.5 16.1642 16.1642 16.5 15.75 16.5H10.5C10.0858 16.5 9.75 16.1642 9.75 15.75V10.5ZM11.25 11.25V15H15V11.25H11.25Z" fill="#39393A"/>
          <path fill-rule="evenodd" clip-rule="evenodd" d="M1.5 10.5C1.5 10.0858 1.83579 9.75 2.25 9.75H7.5C7.91421 9.75 8.25 10.0858 8.25 10.5V15.75C8.25 16.1642 7.91421 16.5 7.5 16.5H2.25C1.83579 16.5 1.5 16.1642 1.5 15.75V10.5ZM3 11.25V15H6.75V11.25H3Z" fill="#39393A"/>
          </svg>
          <span class="text">
            Dashboard
          </span>
      </NuxtLink>
        <NuxtLink to="/loan/new loan" class="lnk">
          <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g opacity="0.7">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M9 2.25C5.27208 2.25 2.25 5.27208 2.25 9C2.25 12.7279 5.27208 15.75 9 15.75C12.7279 15.75 15.75 12.7279 15.75 9C15.75 5.27208 12.7279 2.25 9 2.25ZM0.75 9C0.75 4.44365 4.44365 0.75 9 0.75C13.5563 0.75 17.25 4.44365 17.25 9C17.25 13.5563 13.5563 17.25 9 17.25C4.44365 17.25 0.75 13.5563 0.75 9Z" fill="#39393A"/>
          <path fill-rule="evenodd" clip-rule="evenodd" d="M9 5.25C9.41421 5.25 9.75 5.58579 9.75 6V12C9.75 12.4142 9.41421 12.75 9 12.75C8.58579 12.75 8.25 12.4142 8.25 12V6C8.25 5.58579 8.58579 5.25 9 5.25Z" fill="#39393A"/>
          <path fill-rule="evenodd" clip-rule="evenodd" d="M5.25 9C5.25 8.58579 5.58579 8.25 6 8.25H12C12.4142 8.25 12.75 8.58579 12.75 9C12.75 9.41421 12.4142 9.75 12 9.75H6C5.58579 9.75 5.25 9.41421 5.25 9Z" fill="#39393A"/>
          </g>
          </svg>
          <span class="text">
            New Loan 
          </span>
        </NuxtLink>
        <NuxtLink to="/loan/repayments" class="lnk">
          <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M8.66451 0.82918C8.87566 0.723607 9.12418 0.723607 9.33533 0.82918L16.8353 4.57918C17.0894 4.70622 17.2499 4.96592 17.2499 5.25C17.2499 5.53408 17.0894 5.79378 16.8353 5.92082L9.33533 9.67082C9.12418 9.77639 8.87566 9.77639 8.66451 9.67082L1.16451 5.92082C0.910422 5.79378 0.74992 5.53408 0.74992 5.25C0.74992 4.96592 0.910422 4.70622 1.16451 4.57918L8.66451 0.82918ZM3.17697 5.25L8.99992 8.16147L14.8229 5.25L8.99992 2.33853L3.17697 5.25Z" fill="#39393A" />
            <path fill-rule="evenodd" clip-rule="evenodd" d="M0.8291 12.4146C1.01434 12.0441 1.46485 11.8939 1.83533 12.0792L8.99992 15.6615L16.1645 12.0792C16.535 11.8939 16.9855 12.0441 17.1707 12.4146C17.356 12.7851 17.2058 13.2356 16.8353 13.4208L9.33533 17.1708C9.12418 17.2764 8.87566 17.2764 8.66451 17.1708L1.16451 13.4208C0.794026 13.2356 0.643858 12.7851 0.8291 12.4146Z" fill="#39393A" />
            <path fill-rule="evenodd" clip-rule="evenodd" d="M0.8291 8.66459C1.01434 8.29411 1.46485 8.14394 1.83533 8.32918L8.99992 11.9115L16.1645 8.32918C16.535 8.14394 16.9855 8.29411 17.1707 8.66459C17.356 9.03507 17.2058 9.48558 16.8353 9.67082L9.33533 13.4208C9.12418 13.5264 8.87566 13.5264 8.66451 13.4208L1.16451 9.67082C0.794026 9.48558 0.643858 9.03507 0.8291 8.66459Z" fill="#39393A" />
          </svg>
          <span class="text">
            Repayments
          </span>
        </NuxtLink>
        <NuxtLink to="/loan/history" class="lnk">
          <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g opacity="0.7">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M9 2.25C5.27208 2.25 2.25 5.27208 2.25 9C2.25 12.7279 5.27208 15.75 9 15.75C12.7279 15.75 15.75 12.7279 15.75 9C15.75 5.27208 12.7279 2.25 9 2.25ZM0.75 9C0.75 4.44365 4.44365 0.75 9 0.75C13.5563 0.75 17.25 4.44365 17.25 9C17.25 13.5563 13.5563 17.25 9 17.25C4.44365 17.25 0.75 13.5563 0.75 9Z" fill="#39393A"/>
         <path fill-rule="evenodd" clip-rule="evenodd" d="M9 3.75C9.41421 3.75 9.75 4.08579 9.75 4.5V8.53647L12.3354 9.82918C12.7059 10.0144 12.8561 10.4649 12.6708 10.8354C12.4856 11.2059 12.0351 11.3561 11.6646 11.1708L8.66459 9.67082C8.4105 9.54378 8.25 9.28408 8.25 9V4.5C8.25 4.08579 8.58579 3.75 9 3.75Z" fill="#39393A"/>
         </g>
         </svg>
         <span class="text">
          Loan History
         </span>
        </NuxtLink>
        <NuxtLink class="lnk" to="/notifications">
          <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g opacity="0.7">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M9 2.25C7.80653 2.25 6.66193 2.72411 5.81802 3.56802C4.97411 4.41193 4.5 5.55653 4.5 6.75V10.5C4.5 11.0312 4.35913 11.5478 4.09808 12H13.9019C13.6409 11.5478 13.5 11.0312 13.5 10.5V6.75C13.5 5.55653 13.0259 4.41193 12.182 3.56802C11.3381 2.72411 10.1935 2.25 9 2.25ZM16.5 12C16.1022 12 15.7206 11.842 15.4393 11.5607C15.158 11.2794 15 10.8978 15 10.5V6.75C15 5.1587 14.3679 3.63258 13.2426 2.50736C12.1174 1.38214 10.5913 0.75 9 0.75C7.4087 0.75 5.88258 1.38214 4.75736 2.50736C3.63214 3.63258 3 5.1587 3 6.75V10.5C3 10.8978 2.84196 11.2794 2.56066 11.5607C2.27936 11.842 1.89783 12 1.5 12C1.08579 12 0.75 12.3358 0.75 12.75C0.75 13.1642 1.08579 13.5 1.5 13.5H16.5V12ZM7.32617 15.1012C7.68447 14.8934 8.14341 15.0154 8.35125 15.3737C8.41718 15.4873 8.51181 15.5817 8.62567 15.6472C8.73952 15.7128 8.86861 15.7473 9 15.7473C9.13139 15.7473 9.26048 15.7128 9.37433 15.6472C9.48819 15.5817 9.58282 15.4873 9.64875 15.3737C9.85659 15.0154 10.3155 14.8934 10.6738 15.1012C11.0321 15.3091 11.1541 15.768 10.9462 16.1263C10.7485 16.4673 10.4646 16.7503 10.123 16.9471C9.78144 17.1438 9.39418 17.2473 9 17.2473C8.60582 17.2473 8.21856 17.1438 7.877 16.9471C7.53543 16.7503 7.25154 16.4673 7.05375 16.1263C6.84591 15.768 6.96788 15.3091 7.32617 15.1012Z" fill="#39393A"/>
          </g>
          </svg>
          <span class="text">
            Notifications
          </span>
        </NuxtLink>
        <NuxtLink to="/settings" class="lnk">
          <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g opacity="0.7">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M3.34835 11.5984C4.05161 10.8951 5.00544 10.5 6 10.5H12C12.9946 10.5 13.9484 10.8951 14.6517 11.5984C15.3549 12.3016 15.75 13.2554 15.75 14.25V15.75C15.75 16.1642 15.4142 16.5 15 16.5C14.5858 16.5 14.25 16.1642 14.25 15.75V14.25C14.25 13.6533 14.0129 13.081 13.591 12.659C13.169 12.2371 12.5967 12 12 12H6C5.40326 12 4.83097 12.2371 4.40901 12.659C3.98705 13.081 3.75 13.6533 3.75 14.25V15.75C3.75 16.1642 3.41421 16.5 3 16.5C2.58579 16.5 2.25 16.1642 2.25 15.75V14.25C2.25 13.2554 2.64509 12.3016 3.34835 11.5984Z" fill="#39393A"/>
          <path fill-rule="evenodd" clip-rule="evenodd" d="M9 3C7.75736 3 6.75 4.00736 6.75 5.25C6.75 6.49264 7.75736 7.5 9 7.5C10.2426 7.5 11.25 6.49264 11.25 5.25C11.25 4.00736 10.2426 3 9 3ZM5.25 5.25C5.25 3.17893 6.92893 1.5 9 1.5C11.0711 1.5 12.75 3.17893 12.75 5.25C12.75 7.32107 11.0711 9 9 9C6.92893 9 5.25 7.32107 5.25 5.25Z" fill="#39393A"/>
          </g>
          </svg>
          <span class="text">
            Settings
          </span>
        </NuxtLink>
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.side-bar{
  width: 282px;
  height: 800px;
  background-color: #fff;
  position: fixed;
  border-right: 1px solid #E6E8ED;
  z-index: 3;
  top: 0;
}
.image{
  padding: 84px 54px 59px 55px;
}
.lnk{
      padding: 15px 0 15px 15%;
      display: flex;
      align-items: center;
      font-size: 18px;
      font-weight: 400;
      opacity: 0.7;
      color: #39393A;
      height: 48px;
      cursor: pointer;
      border-left: 4px solid transparent;
      text-decoration: none;
    }
a.nuxt-link-exact-active {
  color: blue;
}
   /* .menu-links{
      padding-top: 10px;
    } */
    /* .link:hover{
      border-left: 4px solid blue;
      fill: blue;
      transition: 0.1s;
    }
    .link svg path{
      fill: inherit;
      transition: 0.1s;
    }
    svg g {
      width: 100%;
      height: 100%;
    }     */
    .lnk svg{
      margin-right: 34.75px;
      fill: inherit;
    }
    a.nuxt-link-exact-active p,
    a:hover p {
  color: #010025;
  font-weight: 600;
}

/* a.nuxt-link-exact-active svg path
,
a:hover svg path {
  background-color: #010025;
  border-radius: 0 20px 20px 0;
} */
.lnk svg path {
  fill: "#39393A";
}
a.lnk.nuxt-link-exact-active svg path {
  fill: blue;
  padding: 0 20px 20px 0;
}
</style>
