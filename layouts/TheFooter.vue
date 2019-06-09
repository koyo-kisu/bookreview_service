<template>
<footer class="footer">
    <div class="footer-container">
        <hr class="footer-hrizon">
        <nav>
            <ul class="footer-list">
                <li><nuxt-link to="#">利用規約</nuxt-link></li>
                <li><nuxt-link to="#">ガイドライン</nuxt-link></li>
                <li><nuxt-link to="#">運営会社</nuxt-link><li>
                <li><nuxt-link to="#">FAQ</nuxt-link></li>
             </ul>
        </nav>
        <div class="copy-right">© my-portfolio.</div>
    </div>
</footer>
</template>

<style>
footer {
    background: white;
    height: 100px;
}

.footer-container {
    height: 50px;
    line-height: 50px;
}

.footer-list {
    float: left;
    text-decoration: none;
    list-style: none;
    padding: 10px 0px 0 80px;     
}

.footer-list li {
    float: left;
    padding-right: 20px;
}

.footer-list a:hover {
    color: #B2B0B0;
}

.footer-list a {
    color:black;
    text-decoration: none;
}

.copy-right {
    float: right;
    padding-right: 80px;
    padding-top: 10px;
}
</style>