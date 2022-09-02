# C#

쇼핑몰 웹 애플리케이션

- Language : JavaScript
- Framework : React.js
- State Manage : Redux, Redux Saga
- Style : Styled-components


## TDD (Test Driven Development)

테스트 코드 작성 -> 실제 코드 작성 -> 테스트 성공 순으로 구현

## Code Convention

### 1. 컴포넌트 네이밍

표기법 : Pascal Case

확장자 : .jsx

```js
// bad case
componentName.jsx

// good case
ComponentName.jsx
```

### 2. 변수명, props

표기법 : Camel Case

```js
// bad case
const UserName = 'string';
const user-name = 'string';
const user_name = 'string';

// good case
const userName = 'string';
```

### 3. 함수

함수명 : handle로 시작하여 동작에 대해 자세히 표기

표기법 : Camel Case

화살표 함수 사용

```js
// bad case
function handle_button() {};

// good case
const handleButton = () => {};
```

### 4. 클래스명

표기법 : Kebab Case

```jsx
// bad case
<Component className="userName" />;

// good case
<Component className="user-name" />;
```

---

## Git Convention

work structure
```bash
pmorigin
  ├── origin
  └── origin
```

### 1. commit Convention

| 종류     | 설명                       |
| -------- | -------------------------- |
| feat     | 새로운 기능 추가           |
| test     | 테스트 코드 추가, 리팩토링 |
| fix      | 버그 수정                  |
| docs     | 문서 수정                  |
| style    | 스타일 수정                |
| refactor | 코드 리팩토링, 코드 삭제   |
| chore    | 설정 변경                  |
| remove    | 불필요 코드 삭제                  |

```bash
git commit -m '종류 : 내용'
```

### 2. Issue Convention

Issue Template 사용

```md

> template content
## Description
설명을 입력하세요.

## Todo
- [ ] todo1
- [ ] todo2

```

### 3. PR Convention

제목 : 요청에 대한 간략한 정보 요약

설명 : PR에 대한 상세한 설명

reolved : #issue

---
