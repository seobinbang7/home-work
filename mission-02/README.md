![이미지 2023  6  7  오후 7 32](https://github.com/seobinbang7/home-work/assets/45528125/f090abf1-974c-4925-8574-b8b3cab97803)


## 1. HTML

form class="login-form" method="POST"
  - 사용자가 입력한 로그인 정보를 전송하기위해 <form> 태그를 사용했습니다. 그리고 css 적용하기위해 login을 감싼 form이라는 걸 뜻하기위해 login-form라고 class명을 지어줬습니다. method="POST"는 클라이언트에서 서버로 전송하기위해 사용했습니다.

fieldset class="login-container"
  - 여러 요소들을 묶기 위해 <fieldset> 태그를 사용했습니다. login에 관한 태그들을 감싸고 있기에 login-container이라고 class명을 지어줬습니다.
  
h2 class="login-text"
  - 로그인 제목을 주기위해 사용했습니다. class명은 login-text로 login을 뜻하는 text라는 걸 표현했습니다.
  
div class="login-box"
  - input태그인 id와 pw를 묶기위해 <div> 태그를 사용했습니다. login을 묶은 태그라고 표현하기위해 login-box라고 class명을 지어줬습니다.
  
label class="id" for="id
 - 아이디임을 정의하기위해 <label>태그를 사용했고 클릭시 id의 <input>이 활성화되도록 for을 작성했습니다.
  
input id="id" class="id-input" type="email" placeholder="euid@euid.det"
 - 사용자에게 정보를 입력받기위해 <input> 태그를 사용했습니다. id를 <label> 태그의 for과 같은 값을 줘서 <label>을 클릭할 경우 id <input> 요소가 활성화되도록 했습니다. id의 input이라는 걸 표현하기위해 class명을 id-input이라 지었고 email 정보를 받기 때문에 type은 email를. placeholder을 사용해서 사용자에게 무슨 정보를 작성해야하는지 예시를 보였습니다.        
  
label class="pw" for="pw"
  - 비밀번호임을 정의하기위해 <label>태그를 사용했고 클릭시 pw의 <input>이 활성화되도록 for을 작성했습니다.
  
input id="pw" class="pw-input" type="password" placeholder="8자리 이상" 
  - 사용자에게 정보를 입력받기위해 <input> 태그를 사용했습니다. pw를 <label> 태그의 for과 같은 값을 줘서 <label>을 클릭할 경우 pw <input> 요소가 활성화되도록 했습니다. pw의 input이라는 걸 표현하기위해 class명을 pw-input이라 지었고 password 정보를 받기 때문에 type은 password를. placeholder을 사용해서 사용자에게 무슨 정보를 작성해야하는지 예시를 보였습니다.
  
button class="login-button" type="submit"
  - 클릭시 전송이 되도록 submit를 작성했고 다른 페이지 이동이 아니기에 <button> 태그를 사용했습니다. login에 사용되는 button임을 표현하기위해 login-button이라고 class명을 지어줬습니다.
  
div class="line"
  - 선을 만들기위해 <div> 태그를 사용했습니다. 선임을 표현하기위해 line이라고 class명을 지었습니다.
  
a class="join" href="#" target="_brank"
  - 클릭시 href에 작성한 경로로 이동하기 때문에 <a> 태그를 사용했습니다. 회원가입을 위한 태그임을 표현하기위해 join이라고 class명을 지었습니다. target="brank"를 줘서 새로운 창이 열리도록 했습니다.
  
a htef="#" targe="_brank"
  - 클릭시 href에 작성한 경로로 이동하기 때문에 <a> 태그를 사용했습니다. target="brank"를 줘서 새로운 창이 열리도록 했습니다.
   
  
## 2. CSS
  
  설명이 필요할 것같은 코드만 작성했습니다.
  
.login-form
  - width로 크기를 지정하였고 그림자 효과를 주기위해 background-color를 #AAAAAA로 지정했습니다.

.login-container
  - background 그라데이션 효과를 주기위해 background: linear-gradient를 줬습니다. 살짝 높이 띄어 login-form의 background-color가 보여 그림자 효과낼 수 있도록 뷰포트 기준으로 움직이지 않도록 position:relative;를 주고 그리고 top: -5px, left: -10px를 줬습니다.

.login-box
  - 좌측에 위치하도록 float:left를 줬습니다.
  
.line
  - <div>태그인 .line에 width와 border를 줘서 선으로 표현했습니다.
  
.a
  - color은 black으로, 밑줄 선을 없애기위해 text-decoration:none을 줬습니다.
