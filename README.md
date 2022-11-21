# bvoid 자체 웹사이트 제작

bvoid 브랜드 성격에 맞춰 웹사이트를 자체 제작해야할 필요성을 느껴 자체 개발을 시작했습니다.

미팅 시 브랜딩이 좋다라는 평을 지속적으로 받으며 더 이상 미룰 수 없다는 판단이 들어 일단 만들고 보는 식으로 구성하며 진행 중입니다.

<br>

---

## 1. 개요

### 🚫 문제점

- 이전 웹사이트는 간편 솔루션의 의존하여 제작되어 웹 프로젝트 생성 시 그리드 시스템, 디자인 등 많은 리소스가 이미지 파일로 이루어졌으며 재사용성이 현저히 떨어짐
  <br>

- 반응형 웹으로 디자인 적용이 어려워 유저 사용성을 떨어트림
  <br>
- 솔루션 기능 한계로 인한 실무자의 과한 반복 작업이 요구됌

<br>

---

## 2. 기술스택

### Back-end

- node JS
- express

### Front-end

- pug
- Javascript

### Database

- MongoDB (mongoose)

<br>

---

## 3. URL

### 페이지 구조

/

/artwork  
/artwork/frame  
/artwork/object  
/artwork/textile  
/artwork/toy  
/artwork/homeware  
/artwork/edition

/artist

### 유저 로그인 관련

/join  
/login
