## 201215

1. React Context를 이용해서 State를 구독할때, setState가 동시에 2번이 호출되면 기존 State를 엎어쓰는 race condition 발생
> setState(prev=>next)로 해결

2. sass의 경우에 nested인 경우 styles.[nested-selector]로 참조가능
3. css 우선순위 참조(https://ofcourse.kr/css-course/%EC%A0%81%EC%9A%A9-%EC%9A%B0%EC%84%A0%EC%88%9C%EC%9C%84)
```
  속성 값 뒤에 !important 를 붙인 속성
  HTML에서 style을 직접 지정한 속성
  #id 로 지정한 속성
  .클래스, :추상클래스 로 지정한 속성
  태그이름 으로 지정한 속성
  상위 객체에 의해 상속된 속성
  같은 우선 순위에 있는 경우, 부모-자식 관계가 많은 경우가 우선되며, 모든 설정이 같은 경우 나중에 선언한 것이 우선되어 적용됩니다.
  ```
