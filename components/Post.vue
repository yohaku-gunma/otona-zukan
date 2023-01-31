<template>
<li class="post">
  <div class="img"></div>
  <h3>いい感じの肩書を持つ男　田中太郎</h3>
  <ul class="tags">
    <li class="tag">#サンプルハッシュタグ</li>
    <li class="tag">#よくいる人</li>
    <li class="tag">#自由人</li>
  </ul>
</li>
</template>

<style scoped>
.post {
  list-style: none;
  width: 100%;
  margin-right: 20px;
}

.post:last-child {
  margin-right: 0;
}

.img {
 width: 100%;
 aspect-ratio: 16/9;
 background-color: lightgrey;
 margin-bottom: 15px;
}

h3 {
 font-size: 20px;
 margin-bottom: 10px;
}

.tags {
  list-style: none;
 font-size: 14px;
 display: flex;
 padding: 0;
}

.tag {
  margin-right: 10px;
}
</style>