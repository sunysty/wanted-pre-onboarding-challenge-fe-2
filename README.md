# Challenge-fe-2 : typescript-todo

#### 소개

신입 프론트엔드 개발자입니다. 타입스크립트를 프론트엔드 환경에서 잘 써보고 싶어서 이번 챌린지에 도전했습니다.

- <a href="https://gist.github.com/pocojang/3c3d4470a3d2a978b5ebfb3f613e40fa">요구사항</a>

- <a href="https://sunysty.github.io/wanted-pre-onboarding-challenge-fe-2/">배포</a>

#### CREATE

```
@function addTodo
@description 할 일을 추가할 수 있다.
@param {string} content - 내용
@param {string} category - 카테고리
@param {string[]} tags - 태그들(optional)

const addTodo = (content, category, tags) => {};
```

#### READ

```
@function getTodoById
@description 모든 할 일을 조회
@returns {Todo[]}

const getTodo = (id) => {};
```

```
@function getTodo
@description ID를 기반으로 특정 할 일을 조회
@param {number} id - 아이디
@returns {Todo}

const getTodoById = (id) => {};
```

#### UPDATE

```
@function updateTodo
@param {number} id - 아이디
@todo 특정 할 일의 특정 태그를 수정
@todo ID를 제외한 모든 속성을 수정

const updateTodo = (id) => {};
```

#### DELETE

```
@function deleteId
@todo 모든 할 일을 제거

const deleteTodo = () => {};
```

```
@function deleteTodoById
@param {number} id - 아이디
@todo ID를 기반으로 특정 할 일을 삭제
@todo 특정 할 일의 특정 태그를 삭제
@todo 특정 할 일의 모든 태그를 제거

const deleteTodoById = (id) => {};
```

#### Modeling (Shape)

```
@typedef {Object} Todo
@property {number} id - 아이디
@property {string} content - 내용
@property {boolean} complete - 완료 여부
@property {string} category - 카테고리
@property {string} tags - 태그들(optional)
```
