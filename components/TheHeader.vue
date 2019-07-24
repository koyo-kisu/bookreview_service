<template>
<header class="pc_header">
  <div class="pc_header_inner">
    <div class="pc_header_top">
      <h1>
        <nuxt-link to="/"><img src="#" alt="">サイト名</nuxt-link>
      </h1>
      <form action="#" class="pc_header_form">
        <input type="serch" name="keyword" placeholder="タイトル・著者名・#タグ" class="input_default">
      </form>
    </div>
<!-- ここからヘッダー左側コンテンツ -->
    <div class="pc_header_nav_box container">
      <div class="row">
        <div class="col-lg-6 nav_left">
            <div class="dropdown nav_left_category">
              <button class="btn btn-light dropdown-toggle table-hover btn-sm" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><i class="fas fa-align-left"></i>
                カテゴリーから探す
              </button>
              <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                <a class="dropdown-item" href="#">単行本<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">文庫本<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">漫画<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">ライトノベル<i class="far fa-chevron-right"></i></a>
              </div>
            </div>
            
            <div class="dropdown nav_left_poptag">
              <button class="btn btn-light dropdown-toggle table-hover btn-sm" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><i class="fas fa-tags"></i>
                人気タグから探す
              </button>
              <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                <a class="dropdown-item" href="#">#泣ける<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">#抱腹絶倒<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">#怒涛のラスト<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">#切ない<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">#幸せな未来<i class="far fa-chevron-right"></i></a>
              </div>
            </div>        
          </div>
          
    <!-- ここからヘッダー右側コンテンツ -->
          <div class="col-lg-6">
            <div class="dropdown nav_right_info">
              <button class="btn btn-light dropdown-toggle table-hover nav_right_info btn-sm" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><i class="fas fa-bell"></i>
                お知らせ
              </button>
              <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                <a class="dropdown-item" href="#">いいね一覧<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">出品した一覧<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#"><i class="far fa-chevron-right"></i></a>
              </div>
            </div>

            <div class="dropdown nav_right_mypage">
              <button class="btn btn-light dropdown-toggle table-hover nav_right_mypage btn-sm" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><i class="fas fa-home"></i>
                マイページ
              </button>
              <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                <a class="dropdown-item" href="#">ホーム<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">マイページ<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">プロフィール設定<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">アカウント設定<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">ヘルプページ<i class="far fa-chevron-right"></i></a>
                <a class="dropdown-item" href="#">ログアウト<i class="far fa-chevron-right"></i></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</header>        
</template>

<style>
* {
  margin: 0;
  padding: 0;
}

header {
  background: white;
  height: 130px;
}

ul {
  list-style: none;
}

h2 {
  line-height: 1.4;
  font-size: 17px;
}

/**/
.nav_left {
  float: left;
}

.nav_left_category {
  float: left;
}

.nav_left_poptag {
  float: right;
  margin-right: 40px;
}

.nav_right {
  float: right;
  background: yellow;
}

.nav_right_info {
  float: left;
  margin-left: 75px;
}

.nav_right_mypage {
  float: right;
}



/**/

.pc_header {
  position: relative;
}

.pc_header_inner {
  width: 850px;
  margin: 0 auto;
  padding: 8px 0 0;
}

.pc_header_top {
  display: flex;
  -webkit-box-align: center;
  align-items: center;
}

.pc_header h1 a {
  display: block;
  color: black;
  text-decoration: none;
}

.pc_header_nav h2 a {
  text-decoration: none;
}

.pc_header_form {
  margin-left: 45px;
  position: relative;
  width: 100%;
  -webkit-box-flex: 1;
  flex: 1;
}

.pc_header_form  .input_default {
  height: 40px;
  width: 100%;
  padding: 0 42px 0 10px;
  border-radius: 4px;
}

.pc_header_form .icon_search {
  position: absolute;
  top: 0;
  right: 0;
  display: flex;
  -webkit-box-align: center;
  width: 40px;
  height: 40px;
  cursor: pointer;
}

.input_default {
  line-height: 1.5;
  font-size: 16px;
}

.pc_header_nav_box {
  margin: 8px 0 0;
}

/*ここからリスト左側*/


.l_left {
  float: left;
  height : 30px;
}

.pc_header_nav {
  font-size: 0;
}

.pc_header-nav>li:first_child {
  padding-left: 0;
}

.pc_header_nav>li {
  position: relative;
  display: inline-block;
  padding: 0 11px;
  cursor: pointer;
}

.pc_header_nav h2 {
  font-size: 14px;
  font-weight: 400;
}

.pc_header_nav_root .list_parent {
  font-weight: bold;
}

.pc_header_nav a {
  display: block;
  color: black;
}


.pc_header_nav_root {
  position: relative;
  height: 21.2px;
  line-height: 32px;
}

.pc_header_nav_parent_wrap {
  position: absolute;
  top: 44px;
  left: -33px;
}

.pc_header_nav_parent {
  display: none;
  width: 224px;
}

.pc_header_nav>li:first_child {
  padding-left: 0;
}

.pc_header_nav>li {
  position: relative;
  display: inline-block;
  padding: 0 11px;
  cursor: pointer;
}

.pc_header_nav_root span {
  vertical-align: middle;
}

.pc_header_nav>li:last_child {
  padding-right: 0;
}


/* ここからリスト右側 */

.l_right {
  float: right;
}

.user_nav_left {
  float: left;
  background: yellow;
}

.user_nav_right {
  float: right;
  background: green;
}
</style>
