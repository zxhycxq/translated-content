---
title: Number.MAX_VALUE
slug: Web/JavaScript/Reference/Global_Objects/Number/MAX_VALUE
tags:
  - JavaScript
  - Number
  - Property
translation_of: Web/JavaScript/Reference/Global_Objects/Number/MAX_VALUE
---
{{JSRef}}

**`Number.MAX_VALUE`** 속성은 JavaScript가 표현할 수 있는 제일 큰 양의 숫자 값을 나타냅니다.

{{EmbedInteractiveExample("pages/js/number-maxvalue.html")}}{{js_property_attributes(0, 0, 0)}}

## 설명

`MAX_VALUE`의 값은 약 `1.79E+308`, 2^1024입니다. `MAX_VALUE`보다 큰 값은 {{jsxref("Infinity")}}로 표현됩니다.

`MAX_VALUE`는 {{jsxref("Number")}}의 정적 속성이기 때문에, 직접 생성한 {{jsxref("Number")}} 객체의 속성이 아니라 `Number.MAX_VALUE` 형식으로 사용해야 합니다.

## 예제

### `MAX_VALUE` 사용하기

다음 코드는 두 개의 수를 곱합니다. 만약 결과가 `MAX_VALUE` 이하면 `func1`을 호출하고, 그렇지 않으면 `func2`를 호출합니다.

```js
if (num1 * num2 <= Number.MAX_VALUE) {
  func1();
} else {
  func2();
}
```

## 명세

{{Specifications}}

## 브라우저 호환성

{{Compat}}

## 참고

- {{jsxref("Number.MIN_VALUE")}}
