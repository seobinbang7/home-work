![이미지 2023  6  15  오후 9 33](https://github.com/seobinbang7/home-work/assets/45528125/ede90a1e-e4bd-4ed8-9694-341a7cd19a83)


## HTML
``` <section class="site-box"></section> ```
 - 요소들을 묶기위해 section 태그를 사용했습니다.
 
```<h4></h4> ```
  - 제목을 줬습니다.

```<span class="pularity"></span>```
 - 사이트와 더보기와 inline 두기위해 span 태그 했습니다. 그리고 인기 사이트 텍스트의 굵기가 더보기와 달라서 굵기를 주기위해 클래스를 줬습니다.

 ```<span class="site"></span> ```
  - 인기와 더보기와 inline 두기위해 span 태그 했습니다. 색상이 달라 따로 클래스를 줬습니다.

  ```<ol class="rank-box"></ol>```
  - 순서있는 리스트를 주기위해 ol 태그를 사용했습니다.

  ```<li></li> ```
  - 리스트를 사용했습니다.

  ##CSS
  
  .site-box {
  box-sizing:border-box;
  width: 195px;
  height: auto;
  padding: 15px;
  margin: 10px;
  border: 2px solid #A3A3A3;
  border-radius: 10px;
  background: linear-gradient(#D1D1D1, #E6E6E6);
}
 - padding을 줘도 사이즈가 바뀌지 않게 box-sizing:border-box;를 줬습니다. 

 .popularity {
  font-weight: bold;
}
 - 굵기를 bolde로 줬습니다.

 ol {
  margin: 0;
  counter-reset: index;
}
 - 스크린리더에 읽히면서도 숫자가 보이지 않게 margin:0;을 줬습니다. 그리고 css counter을 사용하기위해 초기값을 줬습니다.

 li::before {
  counter-increment: index;
  content: counter(index);
}
 - list 순서대로 숫자를 주기위해 사용했습니다.

 .w3c-rank::before,
.standards-rank::before,
.mdn-rank::before,
.zengarden-rank::before {
  width:30px;
  hight:16px;
  padding:3px 7px;
  background-color: #A3A3A3;
  border-radius: 5px;
  margin-right:10px;
}

 - 숫자를 감싸는 상자를 만들었습니다.

 .sprite {
  background: url("./../imges/rank.png") no-repeat;  
}

 - li 태그마자 배경 이미지를 줬습니다.

 .increase {
  background-position: right top;
  height:24px;
  margin-bottom:10px;
  line-height: 15px;
}

.degradation {
  background-position: right -43px;
  line-height: 15px;
  margin-bottom: 20px;
}

.nochange {
  background-position: right center;
}

 - background-position을 사용해서 이미지 노출 위치를 조정했습니다. line-height를 사용해서 텍스트와 이미지가 세로로 중앙에 맞게 맞췄습니다.
