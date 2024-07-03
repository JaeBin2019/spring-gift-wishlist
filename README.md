# spring-gift-wishlist

---

## Step1

**요구 사항**<br>
상품을 추가하거나 수정하는 경우, 클라이언트로부터 잘못된 값이 전달될 수 있다. 잘못된 값이 전달되면 클라이언트가 어떤 부분이 왜 잘못되었는지 인지할 수 있도록 응답을 제공한다.

1. 상품 이름은 공백을 포함하여 최대 15자까지 입력할 수 있다.
2. 특수 문자 가능: ( ), [ ], +, -, &, /, _ 그 외 특수 문자 사용 불가
3. "카카오"가 포함된 문구는 담당 MD와 협의한 경우에만 사용할 수 있다.


**필요 조건**<br>
Validation 을 사용해서 진행한다
```
implementation 'spring-boot-starter-validation'
```
----
**구현 기능**<br>
요구 사항에 맞추어 입력값 검증을 추가한다




