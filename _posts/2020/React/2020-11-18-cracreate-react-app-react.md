---
title: CRA(create-react-app)을 이용해서 React 프로젝트 시작하기
categories:
- React
---

## 목표: create-react-app을 이용해 React 프로젝트를 시작해보자 ❗
### 1. Node.js 설치하기
1. https://nodejs.org/ko/ 에서 설치를 한다.
2. cmd에서 아래와 같이 나오면 정상적으로 설치가 된 것 이다. *(필자와 버전이 다를 수 있음)*
```
> node --version
v12.16.0
```

---
### 2. CRA로 React 프로젝트 만들기
```
> create-react-app my-react-app
```

---
### 3. 생성된 React 프로젝트를 실행하기
```
> cd my-react-app
> npm start
```
실행 후 http://localhost:3000/ 에 접속하면

<img src="/assets/images/cra_project_1.png" width="100%">

위에 사진처럼 보인다.

*💬 IE에서 CRA로 만든 React 프로젝트를 열면 정상적으로 동작하지 않습니다. (**제발 크롬...**)*

---
### 4. 폴더 구조 📁
```
my-react-app
│ .gitgnore
│ package.json
│ package-lock.json
│ README.md
└─ node_modules
└─ public
│  │ favicon.ico
│  │ index.html
│  │ logo192.png
│  │ logo512.png
│  │ manifest.json
│  │ robots.txt
│
└─ src
│  │ App.css
│  │ App.js
│  │ App.test.js
│  │ index.css
│  │ index.js
│  │ logo.svg
│  │ reportWebVitals.js
│  │ setupTests.js
```
