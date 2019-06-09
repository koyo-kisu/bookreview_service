<template>
<div>
  <div class="container">
    <div class="row">
<!--    検索結果左側    -->
      <div class="col-lg-2">
        <div class="left_nav">
          <div class="left_nav_1">
            <h6>在庫状況</h6>
            <select>
              <option>選択してください</option>
              <option>中古品在庫あり</option>
            </select>
          </div>
          <div class="left_nav_2">
            <h6>価格帯</h6>
            <select>
              <option>選択してください</option>
              <option>0-500円</option>
              <option>500-1000円</option>
              <option>1000円-3000円</option>
              <option>3000円-5000円</option>
              <option>5000円以上</option>
            </select>
          </div>
          <div class="left_nav_3">
            <h6>並び替え</h6>
            <select>
              <option>選択してください</option>
              <option>スキ！が多い順</option>
              <option>出版が新しい順</option>
            </select>
          </div>
          <div class="left_nav_4">
            <h6>表示件数</h6>
            <select>
              <option>選択してください</option>
              <option>10-20件</option>
              <option>20-30件</option>
            </select>
          </div>
          <div class="left_nav_5">
            <h6>スキ！数</h6>
            <select>
              <option>選択してください</option>
              <option>0-100</option>
              <option>100-200</option>
              <option>200-300</option>
              <option>300-400</option>
              <option>400-500</option>
              <option>500以上</option>
            </select>
          </div>
          <div class="left_nav_6">
            <h6>フォーマット</h6>
            <input type="checkbox">
                <div>単行本</div>
            
            <input type="checkbox" class="book_sm">
                <div>文庫本</div>
            
          </div>
          <div class="left_nav_7">
            <h6>コンディション</h6>
            <input type="checkbox">
            <div>新品</div>
            
            <input type="checkbox" class="book_used">
            <div>中古本</div>
            
          </div>
          <div>
            <button type="submit" class="left_nav_submit">検索する</button>  
          </div>
        </div>

      </div>
<!--    検索結果右側    -->
      <div class="col-lg-10">
        <section class="items_box_container">
          <div class="item">
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
  <!--       ↑詳細ページへリンク       -->
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
  <!--        ↑詳細ページへリンク        -->
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <a href="#"><i class="icon-like-border">*</i></a>
  <!--        ↑詳細ページおすすめ一覧へリンク          -->
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
  <!--        ↑詳細ページ中古品一覧へリンク            -->
                  </h6>
                </div>
              </div>            
            </section>            
          </div>

          <div class="item">
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <a href="#"><i class="icon-like-border">*</i></a>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>            
          </div>

          <div class="item">  
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <i class="icon-like-border">*</i>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>
          </div>
          
          <div class="item">  
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <i class="icon-like-border">*</i>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>          
          </div> 
        </section>
<!--     ↑items_box_container終わり    -->
        
        <section class="items_box_container">
          <div class="item">
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
  <!--       ↑詳細ページへリンク       -->
            </section>
            
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
  <!--        ↑詳細ページへリンク        -->
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <a href="#"><i class="icon-like-border">*</i></a>
  <!--        ↑詳細ページおすすめ一覧へリンク          -->
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
  <!--        ↑詳細ページ中古品一覧へリンク            -->
                  </h6>
                </div>
              </div>            
            </section>            
          </div>

          <div class="item">
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <a href="#"><i class="icon-like-border">*</i></a>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>            
          </div>

          <div class="item">  
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <i class="icon-like-border">*</i>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>
          </div>
          
          <div class="item">  
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <i class="icon-like-border">*</i>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>          
          </div> 
        </section>
<!--     ↑items_box_container終わり    --> 
                <section class="items_box_container">
          <div class="item">
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
  <!--       ↑詳細ページへリンク       -->
            </section>
            
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
  <!--        ↑詳細ページへリンク        -->
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <a href="#"><i class="icon-like-border">*</i></a>
  <!--        ↑詳細ページおすすめ一覧へリンク          -->
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
  <!--        ↑詳細ページ中古品一覧へリンク            -->
                  </h6>
                </div>
              </div>            
            </section>            
          </div>

          <div class="item">
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <a href="#"><i class="icon-like-border">*</i></a>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>            
          </div>

          <div class="item">  
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <i class="icon-like-border">*</i>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>
          </div>
          
          <div class="item">  
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <i class="icon-like-border">*</i>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>          
          </div> 
        </section>
<!--     ↑items_box_container終わり    --> 
        
                <section class="items_box_container">
          <div class="item">
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
  <!--       ↑詳細ページへリンク       -->
            </section>
            
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
  <!--        ↑詳細ページへリンク        -->
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <a href="#"><i class="icon-like-border">*</i></a>
  <!--        ↑詳細ページおすすめ一覧へリンク          -->
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
  <!--        ↑詳細ページ中古品一覧へリンク            -->
                  </h6>
                </div>
              </div>            
            </section>            
          </div>

          <div class="item">
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <a href="#"><i class="icon-like-border">*</i></a>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>            
          </div>

          <div class="item">  
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <i class="icon-like-border">*</i>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>
          </div>
          
          <div class="item">  
            <section class="items_photo_box">
              <a href="#">
                <figure class="items_photo">
                  <p></p>
                </figure>
              </a>
            </section>
            <section class="items_text_box_container">
              <div class="items_box_body">
                <h6 class="items_box_name"><a href="#">走れメロス<span>(新潮文庫)</span></a></h6>
                <div>
                  <h6 class="items_box_auther"><a href="#">太宰治</a></h6>
                </div>
                <div class="font_1">
                  <i class="icon-like-border">*</i>
                </div>
                <div class="items_box_price">
                  <h6><span class="items_low_price">¥ 200</span>
                    <a href="#">(中古品<span class="items_used_count">5</span>点あり)</a>
                  </h6>
                </div>
              </div>            
            </section>          
          </div> 
        </section>
<!--     ↑items_box_container終わり    --> 
        
        
        
        
        
      </div>
<!-- col-lg-10終わり -->
    </div>
<!--   ↑row終わり   -->
  </div>
<!--   ↑container終わり   -->
</div>    
</template>
