<template>
      <!-- ハンバーガーリスト -->
    <!-- <b-breadcrumb :items="items"></b-breadcrumb> -->
  <div class="container">
    <!-- メイン -->
    <main class="main">
      <div class="book-contents col-lg-9">
      <!-- いいねが多い作品一覧 -->
        <section class="main-like">
          <h5 class="card-header-title"><a href="#">スキ！が多い作品</a></h5>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt="風の歌を聴け"></a>
            <div class="column-title">
              <h6><a href="#">風の歌を聴け</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="asai_nanimono.jpeg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">何者</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="jikkennshikou_koumoto.jpeg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">実験思考</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="kirawareruyuuki_kishimi.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">嫌われる勇気</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="ippunndehanase_itoh.png" alt=""></a>
            <div class="column-title">
              <h6><a href="#">メモの魔力</a></h6>
            </div>
          </div>    
        </section>

        <!-- おすすめ投稿が多い作品一覧 -->
        <section class="main-like-post sec-header">
          <h5 class="card-header-title"><a href="#">おすすめ投稿が多い作品</a></h5>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">1分で話せ</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">「学力」の経済学</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">7つの習慣</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">妻のトリセツ</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">英単語の語源図鑑</a></h6>
            </div>
          </div>                                
        </section>

        <!-- 映画・ドラマ化された作品一覧 -->
        <section class="main-dramatization sec-header">
          <h5 class="card-header-title"><a href="#">映画・ドラマ化された作品</a></h5>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">キングダム</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">空母いぶき</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">偽装不倫</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">ラジエーションハウス</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">きのう何食べた？</a></h6>
            </div>
          </div>                        
        </section>

        <!-- 文学賞作品一覧 -->
        <section class="main-winner sec-header">
          <h5 class="card-header-title"><a href="#">文学賞作品</a></h5>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">火花</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">夜は短し歩けよ乙女</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">そして、バトンは渡された</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">陸王</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">コンビニ人間</a></h6>
            </div>
          </div>                                
        </section>

        <!-- 運営会社おすすめ作品一覧 -->
        <section class="main-our-recomend sec-header">
          <h5 class="card-header-title"><a href="#">運営会社おすすめ作品</a></h5>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">君たちはどう生きるか</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">その日の前に</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">世界で一番やさしい会議の教科書</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">昨夜のカレー、明日のパン</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">かばん屋の相続</a></h6>
            </div>
          </div>                                
        </section>

        <!-- あなたへのおすすめ作品一覧 -->
        <section class="main-your-recomend sec-header">
          <h5 class="card-header-title"><a href="#">あなたへのおすすめ作品</a></h5>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">反・日本語論</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">こころ</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">金閣寺</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">潮騒</a></h6>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="haruki_murakami_kaze.jpg" alt=""></a>
            <div class="column-title">
              <h6><a href="#">春の雪</a></h6>
            </div>
          </div>                                
        </section>
      </div>
          <!-- サイドバー -->
      <div class="sidebar col-lg-3">
        <div class="sidebar-item">
          <div class="user-rank-title">ランキング</div>
          <!-- 今月のおすすめ投稿上位ユーザー -->
          <section class="youser-post-rank">
            <p>おすすめ投稿数</p>
            <ul>
              <li>
                  <p class="user-rank-first">1</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">田中しょうた</a></div>
                  </div>
              </li>
              <li>
                  <p class="user-rank-second">2</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">田中しょうた</a></div>
                  </div>
              
              </li>
              <li>
                  <p class="user-rank-third">3</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">田中しょうた</a></div>
                  </div>              
              </li>
            </ul>
          </section>

          <!-- 今月のいいね獲得数上位ユーザー -->
          <section class="youser-get-like-rank">
            <hr class="rank-horizon">
            <p>スキ！獲得数</p>
            <ul>
              <li>
                  <p class="user-rank-first">1</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">田中しょうた</a></div>
                  </div>
              
              </li>
              <li>
                  <p class="user-rank-second">2</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">田中しょうた</a></div>
                  </div>
               
              </li>
              <li>
                  <p class="user-rank-third">3</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">田中しょうた</a></div>
                  </div>
               
              </li>
            </ul>
          </section>

          <!-- 今月のお気に入られ数上位ユーザー -->
          <section class="youser-liked-rank">
            <hr class="rank-horizon">
            <p>お気に入られ数</p>
            <ul>
              <li>
                  <p class="user-rank-first">1</p>
                  <div class="user-rank-contents">
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">田中しょうた</a></div>
                  </div>             
              </li>
              <li>
                  <p class="user-rank-second">2</p>
                  <div class="user-rank-contents">                  
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">田中しょうた</a></div>
                  </div>               
              </li>
              <li>
                  <p class="user-rank-third">3</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">田中しょうた</a></div>
                  </div>               
              </li>
            </ul>
            <div class="rank-btn-more">
              <b-button variant="light" class="btn-sm"><a href="#">もっとみる<span class="view-more"> ></span></a></b-button>
            </div>
          </section>
        </div>
      </div>
  </main>
</div>
</template>

<script>

</script>

<style>
.main {
  width: 100%;
}

.main a{
  color:black;
  text-decoration: none;
}

.main li {
  text-decoration: none;
  list-style: none;
}

.book-contents {
  float: right; 
}

.book-contents > section {
  height: 300px;
}

.sec-header {
  margin-top: 50px;
}

.column {
  float: right;
  width: 20%;
}

.column img {
  width: 150px;
  height: 200px;
  background-color: orange;
}

.column-title h6{
  font-size: 14px;
  width: 140px;
}

.sidebar {
  float: left;
  margin-top: 20px;
  position: sticky;
  z-index: 1;
}

.rank-btn-more {
  text-align: right;
  margin-top: 30px; 
}

.rank-btn-more a {
  color: #8A8F93;
}

.view-more {
  line-height: 20px;
}
.card-header-title {
  margin-bottom: 20px;
  margin-top: 20px;
  font-weight:bold;
  font-size: 18px;
}

.user-rank-title {
  font-size: 18px;
}

.youser-post-rank {
  margin-top: 20px;
}

.user-rank-first {
  border: solid 2px #F1F839;
  background: black;
  border-radius: 50%;
  height: 27px;
  width: 27px;
  line-height: 25px;
  text-align: center;
  color: white;
}

.user-rank-second {
  border: solid 2px #DBD5D5;
  background: black;
  border-radius: 50%;
  height: 27px;
  width: 27px;
  line-height: 25px;
  text-align: center;
  color: white;
  margin-top: 20px;
}

.user-rank-third {
  border: solid 2px #F0BF37;
  background: black;
  border-radius: 50%;
  height: 27px;
  width: 27px;
  line-height: 25px;
  text-align: center;
  color: white;
  margin-top: 20px;
}

.user-rank-icon {
  background: skyblue;
  border-radius: 50%;
  height: 35px;
  width: 35px;
  float: left;
  margin-right: 20px; 
}

.user-rank-name {
  line-height: 27px;
  font-size: 12px;
}

.rank-horizon {
  margin-top: 40px;
  margin-bottom: 20px;
}
</style>
