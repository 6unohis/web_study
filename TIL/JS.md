- 변수 선언 : let, var => 자료형 선언은 따로 필요 없음

```js
let a = 10;
let b = "문자열";
let c = true;
```

- 변수 연산 : 문자 + 문자 -> 문자 // 문자 + 숫자 -> 문자 가능

```js
let a = "문자열의 길이는";
let b = 8;
let c = a + b;
```

- 문자열에 변수 참조 : ${} 이러한 표현을 사용하기 위해서는 백틱을 사용해야함 ``

```js
let a = 100;
let b = 200;

console.log(a + '+' + b + '=' + (a + b));
// 이런 코드를 아래처럼 바꿀 수 있음
console.log(`${a} + ${b} = ${a + b}`);
```

- 배열 선언 : 배열의 요소들은 각각 자료형이 달라도(객체 포함) 상관없음

```js
let arr = [1, 2, true, '문자'];
```

- 객체 : key : value의 형태

```js
let obj = {"key" : "value",
            "key2" : "value2"};
let obj2 = {"key3" : "value3"};

let dic = [obj, obj2];
```