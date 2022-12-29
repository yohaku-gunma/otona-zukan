<template>
<div>
  <div class="gray"></div>
  <footer>
    <div class="footer-title">
      渋川おとな図鑑
    </div>
    <div class="footer-subtitle">
      渋川の大人と身近につながるメディア
    </div>
    <div class="footer-box">
      <div class="footer-list li">
        <ul>
          <li>
            渋川おとな図鑑について
          </li>
          <li>
            運営団体
          </li>
          <li>
            お問い合わせ
          </li>   
        </ul>   
      </div>
      <div class="site-number">
        ©YOHAKU2022
      </div>
    </div>
  </footer>
</div>
</template>

<style scoped>
.gray{
  width: 100%;
  height: 780px;
  background-color: #C4C4C4;
}

footer{
  margin: 50px;
  background-color: white;
}
.footer-title{
  font-size: 48px;
  font-weight: 400;
  background-color: white;
  letter-spacing: 0.1em;
}

.footer-subtitle{
  font-size: 19px;
  line-height: 28px;
  background-color: white;
  letter-spacing: 0.1em;
  margin-bottom: 60px
}

.footer-list ul{
  padding: 0;
  margin: 0;
}

.footer-list li{
  margin-right: 30px;
  display: inline-block;
  background-color: white;
}

.footer-box{
  display:flex;
  justify-content:space-between;
  font-size: 14px;
  font-weight: 400;
}

.site-number{
  font-size: 14px;
  font-weight: 400;
  background-color: white;
}
</style>