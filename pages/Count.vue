<template>
    <div id="app">
        <input v-model.trim="message" maxlength="20" placeholder="入力してください">
        <p>{{ message.length }}/20</p>
        <p>最大文字数20文字</p>
    </div>    
</template>


<script>
new Vue({
 el: "#app",
 data: { message: "" }
});
</script>

<style>
/* body {
 text-align: center;
 padding: 10%;
}

p {
 line-height: 1.4;
 padding: 0;
 margin: 0;
}
input,textarea {
 width: 90%;
 height: auto;
 border: 2px teal solid;
 border-radius: 10px;
 padding: 10px;
 margin: 0;
 font-size: 20px;
 color: gray;
 outline: none; */

</style>