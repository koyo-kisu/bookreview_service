<template>
<div class="post_contents">
<!--  header部分  -->
  <div class="post_navbar">
    <div class="post_navbar_brand">
      <div>
        <a href="#" class="navbar_item">
          <nuxt-link to="detail"><i class="far fa-times-circle"></i></nuxt-link>
        </a>
        <div class="post_navbar_center">
          <h2>おすすめ投稿</h2>
        </div>
      </div>
    </div>
  </div>  

 
    <div class="card_content">
      <p class="text_body">この本の好きなところを書いてください！</p>  
    </div>

    <div class="post_field">
      <textarea name="comment" id="" cols="30" rows="5" placeholder="あなたのお友達におすすめする気持ちで書いてください(200字まで)" class="textarea"></textarea>
    </div>
    <div class="option_container">
      <span class="counter_current">0</span>
      <span class="counter_mark">/</span>
      <span class="counter_max">200文字</span>
    </div>

    <div class="post_hashtag_form">
      <div class="post_hashtag_title">ハッシュタグをつけよう！</div>
      <div class="post_hashtag">
          <textarea name="hashtag" id="" cols="30" rows="3" placeholder="#推理小説 #冒険 #涙のラスト(100字まで)" class="textarea"></textarea>
      </div>
      <div class="option_container">
        <span class="counter_current" id="count" maxlength="100">0</span>
        <span class="counter_mark">/</span>
        <span class="counter_max">100文字</span>
      </div>
    </div>
    <nuxt-link to="detail"><button type="submit" class="post_btn">投稿する</button></nuxt-link>
</div>

</template>




<style>
a {
  color: black;
  text-decoration: none;
}

.post_contents {
  text-align: center;
  margin: 0 auto;
  width: 900px;
  height: 700px;
}

.post_navbar {
  margin-top: 30px;
}

.post_navbar_center h2{
  border-bottom: 1px solid gray;
  padding-bottom: 10px;
  text-align: center;
}

.navbar_item {
 float: left; 
}

.cansel {
  float: left;
}

.text_body {
  float: left;
}

.textarea {
  width: 100%;
}

.option_container {
  float: right;
}

.post_hashtag_title {
  float: left;
  margin-top: 30px;
  margin-bottom: 15px;
}

.counter_current {
  color: green;
}

.post_btn {
  background: #fbd605;
  margin-top: 20px;
  padding: 10px;
  width: 100%;
  border: none;
}

.post_btn:hover {
  background: yellow;
}
</style>


<script>


</script>
