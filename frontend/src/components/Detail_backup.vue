<template>
 <!-- html -->
    <div id="detailPage" style="overflow:scroll;width:auto;height:auto;">
      <div class="content">
          <div class="container">
              <div class="bookImage_box">
                  <img src="../assets/img/book-img.png" />
              </div>
              <div class="text_area">
                  <div class="bookName"><h1>자바 ORM 표준 JPA 프로그래밍</h1></div>
                  <h2 id="authorName">저자 김영한</h2>
                  <br>
                  <h1 id="price">43,000원</h1>
                  <h2 id="condition">상태 : 중</h2>
                  <div class="text">
                    <p>스프링 공부하면서 jpa도 더 공부하려고 샀는데 프론트 개발자로 취업하게 되어 팝니다. 상태 좋습니다~</p>
                    <p>010-1234-5678</p>
                    <p>네고 안받습니다. (쿨거래시 3000원 네고)</p>
                  </div>
              </div>
          </div>
        </div>
    </div>
</template>

<script>
export default {
    //Javascript - 인스턴스
};
</script>

<style scoped>
/* 기본 폰트 */
@font-face {
  font-family: "tway";
  src: url("../assets/fonts/tway_sky.ttf") format("truetype");
}
@font-face {
  font-family: "elice-bold";
  src: url("../assets/fonts/EliceDigitalBaeum_Bold.ttf") format("truetype");
}
@font-face {
  font-family: "elice-regular";
  src: url("../assets/fonts/EliceDigitalBaeum_Regular.ttf") format("truetype");
}
:root {
  /* 기본 테마 색상 */
  --color-ivory: #faf3e0;
  --color-beige: #eabf9f;
  --color-brown: #b68973;
  --color-dark: #1e212d;
  --color-green: #9eb998;
  --color-khakii: #67917d;

  /* 폰트 사이즈 */
  --font-size-mega: 40px;
  --font-size-large: 35px;
  --font-size-medium: 25px;
  --font-size-regular: 20px;
  --font-size-small: 15px;
  --font-size-micro: 10px;
}
/* CSS */

.bookName{
  color: red;
}
.bookImage_box{
  /* float: left; */
  display: grid;
  place-content: center;
  width: auto;
  height: auto;
  padding: 5px;
  /* background-color: red; */
}

.container{
  display: flex;
  width: 80%;
  height: 80%;
  padding: 8%;
  /* background-color: blue; */
}

.content{
  display: grid;
  place-content: center;
  /* background-color: lightseagreen; */
}

.text_area{
  display: grid;
  place-content: center;
  width: auto;
  height: auto;
  padding: 0px 30px;
  font-family: "elice-regular";
  /* background-color: plum; */
}

.bookName{
  width: auto;
  height: auto;
  /* background-color: yellow; */
}

.text{
  width: auto;
  height: auto;
  /* background-color: lightsalmon; */
}
</style>
