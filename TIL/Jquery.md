<h1>1. Jquery 문법</h1>

```js
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
// jquery 및 ajax 사용
```

1) 기본 문법 

```js
$(선택자).동작함수();
```
- $기호는 제이쿼리 접근 식별자 

```js
$("#id").func();
$(".class").func(); // 형식으로 사용할 수 있음
```

- 선택자 : HTML요소 / 동작함수 : 선택 요소 동작 함수

```js
window.onload = function(){
    // 자바스크립트 코드
}; // 문서가 모두 로드된 후 실행

$(document).ready(function(){
    // 제이쿼리 코드
}); // 위와 동일함
```
<h1>2. Ajax</h1>

- 메소드

```js
$.ajax(); // jquery ajax의 핵심이자 통합 메소드 .. HTTP 요청
// 메소드 사용방법
$.ajax({
    url : ,
    data : {} ,
    type: "GET / POST",
    success: ,
    error : ,
})
// 아래는 메소드 체이닝 -> done, fail, always
.done(){
    // HTTP 요청 성공 시.. success
}
.fail(){
    // HTTP 요청 실패 시.. error
}
.always(){
    // 항상
}
```

