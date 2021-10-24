---
layout: default
permalink: /download/sheet/this_world_is_not_my_home
---
<meta http-equiv="refresh" content="0; url=https://drive.google.com/uc?export=download&id=1Cjm9-9_9OKIFtbAVcP1E1OIjk1RzW7Og">

<!-- 본문 -->
<div class="container">
  <img src="/assets/img/download.gif" width="100%" alt="{{ site.translations.error_404.image_alt | default: 'Download' }}">
  <p><strong>{{ site.translations.error_404.title | default: "자동으로 다운로드합니다!" }}</strong></p>
  <p>{{ site.translations.error_404.message | default: "다운로드가 되지 않았다면 아래버튼을 클릭해 주세요!😊😊" }}</p>
  <span><a href="https://drive.google.com/uc?export=download&id=1Cjm9-9_9OKIFtbAVcP1E1OIjk1RzW7Og"></a></span>
</div>

<!-- ------------------------------------------------- -->

<!-- 설명글 Style -->
<style type="text/css" media="screen">
  @font-face {
    font-family: 'IM_Hyemin-Bold';
    src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2106@1.1/IM_Hyemin-Bold.woff2') format('woff');
    font-weight: normal;
    font-style: normal;
  }
  .container {
    font-family: 'IM_Hyemin-Bold', cursive;
    margin: 0px auto;
    max-width: 600px;
    text-align: center;
    padding-top: 60px;
    font-size: 20px;
  }
</style>

<!-- 버튼 Style -->
<style>
  @import url('https://fonts.googleapis.com/css?family=Montserrat:600&display=swap');
  span{
    position: relative;
    display: inline-flex;
    width: 180px;
    height: 55px;
    margin: 0 15px;
    perspective: 1000px;
  }
  span a{
    font-size: 19px;
    letter-spacing: 1px;
    transform-style: preserve-3d;
    transform: translateZ(-25px);
    transition: transform .25s;
    font-family: 'Montserrat', sans-serif;

  }
  span a:before,
  span a:after{
    position: absolute;
    content: "Download";
    height: 55px;
    width: 180px;
    display: flex;
    align-items: center;
    justify-content: center;
    border: 5px solid black;
    box-sizing: border-box;
    border-radius: 5px;
  }
  span a:before{
    color: #fff;
    background: #000;
    transform: rotateY(0deg) translateZ(25px);
  }
  span a:after{
    color: #000;
    transform: rotateX(90deg) translateZ(25px);
  }
  span a:hover{
    transform: translateZ(-25px) rotateX(-90deg);
  }

</style>