<template>
    <div class="container">
        <div>
            <h3 class="loginchecktitile">もう一度確認させてください！</h3>
        </div>
        <div class="logincheckform">
            <div>
                <p>以下の内容で登録してよろしいでしょうか？</p>
            </div>
            <div>
                <ul class="list-group">
                    <span>名前</span><li class="list-group-item">テキストテキストテキスト</li>
                    <span>名前（フリガナ）</span><li class="list-group-item">テキストテキストテキスト</li>
                    <span>パスワード</span><li class="list-group-item">テキストテキストテキスト</li>
                    <span>メールアドレス</span><li class="list-group-item">テキストテキストテキスト</li>
                </ul>
            </div>
            <div class="logincheckbtns">
                <div>
                    <nuxt-link to="/loginform">
                        <button type="submit" class="btn btn-primary logincheckreturn"><i class="fas fa-arrow-circle-left"></i>戻る</button>
                    </nuxt-link>
                </div>
                <div>
                    <nuxt-link to="/loginfinish">
                        <button type="submit" class="btn btn-primary logincheckregister">登録<i class="fas fa-arrow-circle-right"></i></button>
                    </nuxt-link>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.loginchecktitile {
    text-align: center;
    margin-top: 30px;
}

.logincheckform p{
    text-align: center;
    margin-top: 30px;
}

.logincheckform {
    width: 600px;
    margin: 0 auto;
}

.logincheckbtns {
    margin-top: 30px;
}

.logincheckreturn {
    width: 100px;
    float: left;
}

.logincheckregister {
    width: 100px;
    float: right;
}

.fa-arrow-circle-left {
    margin-right: 20px;
}

.fa-arrow-circle-right {
    margin-left: 20px;
}
</style>

<script>
export default {
    
}
</script>
