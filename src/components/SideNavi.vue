<template>
  <div>
    <div class="left-padding">
      <img src="../assets/assets/logo.png" alt="#" class="logo" />
      <div class="flex icon-field">
        <img src="../assets/assets/home.png" alt="#" class="icon" />
        <p>ホーム</p>
      </div>
      <div class="flex icon-field">
        <img src="../assets/assets/profile.png" alt="#" class="icon" />
        <p>プロフィール</p>
      </div>
      <div class="flex icon-field">
        <img src="../assets/assets/logout.png" alt="#" class="icon" />
        <p>ログアウト</p>
      </div>
    </div>
    <hr />
    <ShareMessage />
  </div>
</template>

<script>
import ShareMessage from "../components/ShareMessage" 
export default {
  components: {
    ShareMessage
  }
}
</script>

<style scoped>
.left-padding {
 margin: 20px;
}

.flex {
  display: flex;
}
.logo {
 width: 100px;
}
.icon-field {
 margin-top: 15px;
 cursor: pointer;
}
.icon {
  width: 25px;
}
.icon-field p {
 font-size: 16px;
 padding-left: 15px;
}
</style>