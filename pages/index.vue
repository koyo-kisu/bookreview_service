<template>
      <!-- ハンバーガーリスト -->
    <!-- <b-breadcrumb :items="items"></b-breadcrumb> -->
  <div class="container">
    <!-- メイン -->
    <main class="main">
      <div class="book-contents col-lg-9">
      <!-- いいねが多い作品一覧 -->
        <section class="main-like sec-header">
          <h5 class="card-header-title"><a href="#">スキ！が多い作品</a></h5>
          <div class="column">
            <nuxt-link to="/detail"><img src="~/assets/img_file/haruki_murakami_kaze.jpg" alt="風の歌を聴け"></nuxt-link>
            <div class="column-body">
              <h6 class="column-title"><nuxt-link to="/detail">風の歌を聴け</nuxt-link></h6>
              
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>

            </div>
          </div>
          <div class="column">
            <nuxt-link to="/detail"><img src="~/assets/img_file/asai_nanimono.jpeg" alt="何者"></nuxt-link>
            <div class="column-body">
              <h6 class="column-title"><nuxt-link to="/detail">何者</nuxt-link></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <nuxt-link to="/detail"><img src="~/assets/img_file/jikkennshikou_koumoto.jpeg" alt="実験思考"></nuxt-link>
            <div class="column-body">
              <h6 class="column-title"><nuxt-link to="/detail">実験思考</nuxt-link></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <nuxt-link to="/detail"><img src="~/assets/img_file/kirawareruyuuki_kishimi.jpg" alt="嫌われる勇気"></nuxt-link>
            <div class="column-body">
              <h6 class="column-title"><nuxt-link to="/detail">嫌われる勇気</nuxt-link></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <nuxt-link to="/detail"><img src="~/assets/img_file/memoma_maedayuji.jpg" alt="メモの魔力"></nuxt-link>
            <div class="column-body">
              <h6 class="column-title"><nuxt-link to="/detail">メモの魔力</nuxt-link></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="main_btn_view_more">
            <a href="#">もっと見る<span> ></span></a>
          </div>              
        </section>

        <!-- おすすめ投稿が多い作品一覧 -->
        <section class="main-like-post sec-header">
          <h5 class="card-header-title"><a href="#">おすすめ投稿が多い作品</a></h5>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/ippunndehanase_itoh.png" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">1分で話せ</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/gakuryokunokeizai_nakamura.jpeg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">「学力」の経済学</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/nanatsunosyuukann_steaven.jpeg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">7つの習慣</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/tsumanotorisetu_kurokawa.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">妻のトリセツ</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/eitangonogengo_shimizu.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">英単語の語源図鑑</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="main_btn_view_more">
            <a href="#">もっと見る<span> ></span></a>
          </div>                                          
        </section>

        <!-- 映画・ドラマ化された作品一覧 -->
        <section class="main-dramatization sec-header">
          <h5 class="card-header-title"><a href="#">映画・ドラマ化された作品</a></h5>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/kingdom.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">キングダム</a></h6>
               <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/kuuboibuki.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">空母いぶき</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/gisoufurin.jpg" alt="偽装不倫"></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">偽装不倫</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/radieitionhouse.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">ラジエーションハウス</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/kinounanitabeta.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">きのう何食べた？</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div> 
          <div class="main_btn_view_more">
            <a href="#">もっと見る<span> ></span></a>
          </div>                                 
        </section>

        <!-- 文学賞作品一覧 -->
        <section class="main-winner sec-header">
          <h5 class="card-header-title"><a href="#">文学賞作品</a></h5>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/hibana.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">火花</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/yoruhamijikashi.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">夜は短し歩けよ乙女</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/baton.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">そして、バトンは渡された</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/rikuou.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">陸王</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/convini.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">コンビニ人間</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="main_btn_view_more">
            <a href="#">もっと見る<span> ></span></a>
          </div>                                        
        </section>

        <!-- 運営会社おすすめ作品一覧 -->
        <section class="main-our-recomend sec-header">
          <h5 class="card-header-title"><a href="#">運営会社おすすめ作品</a></h5>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/kimitatiha.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">君たちはどう生きるか</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/sonohinomaeni.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">その日の前に</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/kaiginokyoukasyo.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">世界で一番やさしい会議の教科書</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/yuubenocurry.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">昨夜のカレー、明日のパン</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/kabannosouzoku.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">かばん屋の相続</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="main_btn_view_more">
            <a href="#">もっと見る<span> ></span></a>
          </div>                                          
        </section>

        <!-- あなたへのおすすめ作品一覧 -->
        <section class="main-your-recomend sec-header">
          <h5 class="card-header-title"><a href="#">あなたへのおすすめ作品</a></h5>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/hannihongo.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">反・日本語論</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/kokoro_natsume.jpeg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">こころ</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/kinnkakuji.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">金閣寺</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/shiosai.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">潮騒</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="column">
            <a href="#"><img src="~/assets/img_file/harunoyuki.jpg" alt=""></a>
            <div class="column-body">
              <h6 class="column-title"><a href="#">春の雪</a></h6>
              <div class="product_buttons container">
                <div>
                  <ul class="row">
                    <li class="col-lg-6 product_fav product_button">
                      <i class="far fa-heart" style="color: gray"></i>
                      <span>500</span>
                    </li>
                    <li class="col-lg-6 product_cart product_button">
                      <i class="far fa-comment-alt" style="color: gray"></i>
                      <span>500</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div> 
          <div class="main_btn_view_more">
            <a href="#">もっと見る<span> ></span></a>
          </div>                                       
        </section>         
      </div>
          <!-- サイドバー -->
      <div class="sidebar col-lg-3">
        <div class="sidebar-item">
          <div class="user-rank-title">ランキング</div>
          <!-- 今月のおすすめ投稿上位ユーザー -->
          <section class="user-post-rank">
            <p>おすすめ投稿数</p>
            <ul>
              <li>
                  <p class="user-rank-first">1</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">aaaa</a></div>
                  </div>
              </li>
              <li>
                  <p class="user-rank-second">2</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">bbbb</a></div>
                  </div>
              
              </li>
              <li>
                  <p class="user-rank-third">3</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">cccc</a></div>
                  </div>              
              </li>
            </ul>
          </section>

          <!-- 今月のいいね獲得数上位ユーザー -->
          <section class="user-get-like-rank">
            <hr class="rank-horizon">
            <p>スキ！獲得数</p>
            <ul>
              <li>
                  <p class="user-rank-first">1</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">dddd</a></div>
                  </div>
              
              </li>
              <li>
                  <p class="user-rank-second">2</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">eeee</a></div>
                  </div>
               
              </li>
              <li>
                  <p class="user-rank-third">3</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">ffff</a></div>
                  </div>
               
              </li>
            </ul>
          </section>

          <!-- 今月のお気に入られ数上位ユーザー -->
          <section class="user-liked-rank">
            <hr class="rank-horizon">
            <p>お気に入られ数</p>
            <ul>
              <li>
                  <p class="user-rank-first">1</p>
                  <div class="user-rank-contents">
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">gggg</a></div>
                  </div>             
              </li>
              <li>
                  <p class="user-rank-second">2</p>
                  <div class="user-rank-contents">                  
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">hhhh</a></div>
                  </div>               
              </li>
              <li>
                  <p class="user-rank-third">3</p>
                  <div class="user-rank-contents"> 
                    <div class="user-rank-icon"></div>
                    <div class="user-rank-name"><a href="#">iiii</a></div>
                  </div>               
              </li>
            </ul>
            <div class="rank-btn-more">
              <a href="#">もっと見る<span class="view-more"> ></span></a>
            </div>
          </section>
        </div>
      </div>
  </main>
</div>
</template>

<script>
export default {
  layout:'default',
  head: {
    title: 'TOP',
    meta: [
      {
        hid: 'description', name: 'description', content: 'トップページです。'
      }
    ]
  },
}
</script>


<style>
* {
  margin: 0;
  padding: 0;
}

body {
  background: #f6f7f8;
  width: 100%;
  margin: 0 auto;
}

.main {
  width: 100%;
  height: 2800px;
}

.main-like {
  margin-top: 20px;
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
  margin-bottom: 150px;
}

.column {
  float: right;
  width: 20%;
}

.column img {
  width: 150px;
  height: 200px;
  /* background-color: orange; */
}

.column-body {
  width: 150px;
  height: 90px;
  padding-top: 10px;
  background: white;
}

.column-body > ul li{
  display: inline;
}

.product_buttons {
  width: 100%;
  height: 40px;
  text-align: center;
  cursor: pointer;
}

.product_fav {
  height: 40px;
  line-height: 40px;
}

.product_fav span {
  font-size: 11px;
}

.product_cart {
  height: 40px;
  line-height: 40px;  
}

.product_cart span {
  font-size: 11px;
}

.column-title {
  width: 150px;
  height: 30px;
  font-size: 14px;
  font-weight: bold;
  overflow: hidden;
}

.column-title a:hover {
  color: #1F35F3;
}

.main_btn_view_more {
  margin-top: 20px;
  float: right;
  border: 1px solid #DBD5D5;
  padding: 5px 10px;
}

.main_btn_view_more:hover {
  background: white;
}

.sidebar {
  float: left;
  margin-top: 20px;
  position: sticky;
  z-index: 1;
  background: white;
  border: 1px solid #EDEDED;
}

.rank-btn-more {
  float: right;
  text-align: center;
  padding: 5px 10px;
  width: 110px;
  font-size: 14px;
  border: 1px solid #DBD5D5;
  margin-top: 30px; 
  margin-bottom: 20px;
}

.rank-btn-more:hover {
  background: #eeeeee;
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
  margin-top: 20px;
}

.user-post-rank {
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
  overflow: hidden;
}

.user-rank-name a:hover {
  color: #1F35F3;
}

.rank-horizon {
  margin-top: 40px;
  margin-bottom: 20px;
}

</style>
