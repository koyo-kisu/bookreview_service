<template>
<div>
    <div class="container">
        <div class="registerlist">
            <h3 class="register-title">新規ユーザー登録</h3>
            <form class="registerform">
                <div class="form-row">
                    <div class="form-group col-md-6">
                    <label for="inputName" class="form-title">姓<span class="badge badge-danger">必須</span></label>
                    <input type="text" class="form-control" id="inputName">
                    </div>
                    <div class="form-group col-md-6">
                    <label for="inputName" class="form-title">名<span class="badge badge-danger">必須</span></label>
                    <input type="text" class="form-control" id="inputName">
                    </div>
                </div>

                <div class="form-row">
                    <div class="form-group col-md-6">
                    <label for="inputName" class="form-title">姓（フリガナ）<span class="badge badge-danger">必須</span></label>
                    <input type="text" class="form-control" id="inputName">
                    </div>
                    <div class="form-group col-md-6">
                    <label for="inputName" class="form-title">名（フリガナ）<span class="badge badge-danger">必須</span></label>
                    <input type="text" class="form-control" id="inputName">
                    </div>
                </div>

                <div class="form-group">
                    <div>
                        <label for="inputEmail" class="form-title">メールアドレス<span class="badge badge-danger">必須</span></label>
                        <input type="email" class="form-control" id="inputEmail">
                    </div>
                </div>

                <div class="form-group">
                    <div>
                        <label for="inputEmail">確認のためもう一度ご入力ください</label>
                        <input type="email" class="form-control" id="inputEmail">
                    </div>
                </div>

                <div class="form-group">
                    <label for="" class="form-title">パスワード<span class="badge badge-danger">必須</span>
                    <br>＊英数字6文字以上で登録してください</label>
                    <input type="password" class="form-control" id="inputPassword">
                </div>
                
                <div class="form-group">
                    <label for="">確認のためもう一度ご入力ください</label>
                    <input type="password" class="form-control" id="inputPassword6">
                </div>

                <div class="form-title">性別</div>
                <div class="form-check form-check-inline">
                    <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio1" value="option1">
                    <label class="form-check-label" for="inlineRadio1">女性</label>
                </div>
                <div class="form-check form-check-inline">
                    <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio2" value="option2">
                    <label class="form-check-label" for="inlineRadio2">男性</label>
                </div>
                <div class="form-check form-check-inline">
                    <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option3">
                    <label class="form-check-label" for="inlineRadio3">その他</label>
                </div>

                <button type="submit" class="btn btn-primary nextpage">次へ</button>
            </form> 
        </div>  
    </div>
</div>    
</template>

<style>
* {
    padding: 0;
    margin: auto;
}

.register-title {
    text-align: center;
    margin-top: 30px;
    margin-bottom: 30px;
}

.form-title {
    font-weight: bold;
}

.registerform {
    width: 600px;
    margin: 0 auto;
}

.nextpage {
    width: 600px;
    margin-top: 40px;
}

</style>

<script>
export default {
    
}
</script>
