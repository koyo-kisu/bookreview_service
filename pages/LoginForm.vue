<template>
<div class="container">
  <div>
    <h3 class="login-title">おかえりなさい！</h3>
  </div>
  <div>
    <form class="login-form">
      <div class="form-group">
        <label for="exampleInputEmail1" class="login-title-mail">メールアドレス</label>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
      </div>
      <div class="form-group">
        <label for="exampleInputPassword1" class="login-title-password">パスワード</label>
        <br>＊英数字6文字以上で登録してください
        <input type="password" class="form-control" id="exampleInputPassword1">
        <a href="#"><small>パスワードをお忘れですか？</small></a>
      </div>
      <div class="form-group form-check">
        <input type="checkbox" class="form-check-input" id="exampleCheck1">
        <label class="form-check-label" for="exampleCheck1">保存する</label>
      </div>
      <nuxt-link to="/logincheck">
        <button type="submit" class="btn btn-primary loginbtn">ログイン</button>
      </nuxt-link>
    </form>
  </div>
</div>

</template>

<style>
* {
    padding: 0;
    margin: auto;
}

a {
  text-decoration: none;
}

.container input {
  width: 600px;
}

.login-title {
  text-align: center;
  margin-top: 30px;
  margin-bottom: 30px;
}

.login-title-mail, .login-title-password {
  font-weight: bold;
}

.login-form {
  margin: 0 auto;
  width: 600px;
}

.loginbtn {
  width: 600px;
}
</style>

<script>
export default {
    
}
</script>
