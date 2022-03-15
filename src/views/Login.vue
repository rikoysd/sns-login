<template>
  <div>
    <h1>ログイン</h1>
    <div class="item">
      <div>ユーザーID/メールアドレス</div>
      <div><input type="text" /></div>
    </div>
    <div class="item">
      <div>パスワード</div>
      <div><input type="password" /></div>
    </div>
    <button type="button">ログイン</button>
    <div class="sns-btn">
      <button type="button" class="btn">Twitterでログインする</button>
      <button type="button" class="btn">Facebookでログインする</button>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
@Component
export default class XXXComponent extends Vue {}
</script>

<style scoped>
.item {
  margin-bottom: 20px;
}

.sns-btn {
  margin-top: 40px;
}

.btn {
  margin-left: 20px;
}
</style>
