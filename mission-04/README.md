## HTML

  ```<section></section>```

  - 독립적으로 사용하기위해 사용했습니다.

  ```<a target="_blank" href="#"></a>```

  - 더보기 클릭 시 이동할 수 있도록 a태그를 사용했습니다.target="blank"으로 새창이 열립니다.

  ```<div class="introduce">```

  - 설명을 담는 div 태그입니다. figure, div, p태그들을 묶습니다.

  ```<figure></figure> ```

  - 사진 콘텐츠를 담기 위해 사용했습니다.

  ```<img alt="W3C 사이트" src="./img/news1.png">```

  - 이미지 태그이며, W3C 사이트 이미지임을 표현하기위해 alt="W3C 사이트"라고 지었습니다. 

  ```<figcaption class="w3c-figcaption">W3C 리뉴얼<figcaption>```

  - 이미지를 설명하는 태그입니다.

  ```<div></div> ```

  - p 태그들을 묶기위해 사용했습니다.

  ``` <p class="w3c-p1">W3C 사이트가 리뉴얼 되었습니다.</p>```

  - block 속성인 p태그를 사용했습니다.

  ```<p class="w3c-p2" datetime="2022-07-18">2022.07.18</p>```

  - block 속성인 p태그를 사용했습니다. 스크린리더에 읽힐 수 있게 datetime 속성을 작성했습니다.

  ``` <p class="w3c-p3"> ```

  - block 속성인 p태그를 사용했습니다.

## CSS

section {
  width:380px;
  height:200px;
  padding: 20px;
  display:grid;
  grid-template-columns: reqeat(1, 1fr);
  grid-template-areas:
    "h2 span"
    "intoduce intoduce";
}
  - 태그들을 묶고 있는 section에 grid를 줬습니다.

 
