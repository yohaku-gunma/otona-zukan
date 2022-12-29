<template>
<ul>
  <li>
    <div class="img"></div>
    <h3>いい感じの肩書を持つ男　田中太郎</h3>
    <div class="tag">#サンプルハッシュタグ#自由人#よくいる人</div>
  </li>
  <li>
    <div class="img"></div>
    <h3>かくれんぼおじさん　豊川　雄太</h3>
    <div class="tag">#リモートワーカー</div>
  </li>
  <li>
    <div class="img"></div>
    <h3>革命家高校教師　千明　俊太</h3>
    <div class="tag">#Nativeしぶかわん</div>
  </li>
</ul>
</template>

<style scoped>
ul {
 display: flex;
 flex-direction: row;
 position: absolute;
}

.img {
 width: 520px;
 height: 292.5px;
 background-color: black;
 margin-top: 120px;
 margin-bottom: 15px;
 margin-left: 40px;
}

h3 {
 width: 375px;
 height: 29px;
 font-family: 'Noto Sans JP';
 font-style: normal;
 font-size: 20px;
 line-height: 29px;
 letter-spacing: 0.1em;
 color: #000000;
}

.tag {
 width: 162px;
 height: 20px;
 font-family: 'Noto Sans JP';
 font-style: normal;
 font-weight: 400;
 font-size: 14px;
 line-height: 20px;
 letter-spacing: 0.1em;
 color: #000000;
}

</style>