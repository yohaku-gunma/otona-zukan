<template>
<div class="gray">
</div>

<footer>
<div class="footer-title">
    <p>
        渋川おとな図鑑
    </p>
</div>

<div class="footer-subtitle">
    <p>
        渋川の大人と身近につながるメディア
    </p>
</div>

<div class="footer-nav">
</div>

<div class="footer-box">
    <div class="footer-list li">
        <p>
            渋川おとな図鑑について
        </p>
        <p>
            運営団体
        </p>
        <p>
            お問い合わせ
        </p>   
    </div>

    <div class="wrapper">
    </div>

    <div class="site-number">
        <p>
            ©YOHAKU2022
        </p>
    </div>
</div>
</footer>

</template>

<style scoped>
.gray{
  width: 1920px;
  height: 780px;
  background-color: #C4C4C4;
}

footer{
  padding: 30px 0;
  background-color: red;
}

.wrapper{
  width: 80%;
  margin: 0 auto;
  background-color: black;
}

.footer-title{
  font-size: 2rem;
  background-color: yellow;
}

.footer-subtitle{
  line-height: 1.5rem;
  background-color: yellowgreen;
}

.footer-nav{
  margin-top: 60px;
  display: flex;
  justify-content: space-between;
  background-color: blue;
}

.footer-list li{
  display: inline-block;
  margin-right: 20px;
  background-color: pink;
}

.footer-list li p{
  display:inline-block;
}

.footer-box{
  display:flex;
  justify-content:space-between;
}

.site-number{
  background-color: gold;
}
</style>