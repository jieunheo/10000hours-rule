# 10000hours-rule

1만 시간의 법칙.
어떤 분야에서든 전문가가 되려면 해당 분야에 1만 시간 이상 투자해야 한다는 이론.
즉, 꾸준한 노력과 연습을 통해 특정 분야의 숙련자가 될 수 있다는 의미.

## 1. 목표와 기능

---

### 1.1 목표

- 기간 안에 페이지 완성하기
- HTML, CSS 만을 이용한 1만 시간의 법칙 페이지 만들기
- 시멘틱 마크업, 접근성, SEO, CSS 네이밍 방법론 고려하기
- 여러가지 화면에서도 문제 없는 반응형으로 작업하기

### 1.2 기능

특수한 기능은 없으나 고려해야 할 부분을 정리

1. HTML
   - 시맨틱 마크업 준수
   - 접근성 고려
   - SEO 고려
2. CSS
   - 반응형 제작
   - CSS 네이밍 방법론 고려

### 1.3 팀 구성

개인 프로젝트로 1인 개발.

## 2. 개발 환경 및 배포 URL

---

### 2.1 개발 환경

- VSCode

### 2.2 배포 URL

- https://jieunheo.github.io/10000hours-rule/

## 3. 요구사항 명세와 기능 명세

---

1. 피그마를 참고하여 페이지 구현을 합니다.
2. 모바일 화면도 고려하여 페이지 구현을 합니다.
3. 시멘틱 마크업, 반응형 웹, 접근성, SEO, CSS 네이밍 방법론 등을 고려해서 작업해주세요.
4. 모달창의 경우 퍼블리싱 해주신 후 화면에서 보이지 않게 숨김처리 해주시고 발표할 때 노출로 전환해서 보여주세요.
5. 자바스크립트로 추후 구현할 리스트
   1. `훈련하기 GO! GO!` 버튼 클릭시 모달창이 뜨도록 구현합니다.

[피그마 참고](https://www.figma.com/design/rbi8px4O2GrnXN4gK0ZaLv/WENIV_FE_%EC%8B%A4%EC%8A%B5-%EC%98%88%EC%A0%9C?node-id=116293-2&p=f&t=LFaLMLvHlLQi5l2R-0)

## 4. 프로젝트 구조와 개발 일정

---

### 4.1 프로젝트 구조

```
10000hours-rule
├─ images
│  ├─ click.png
│  ├─ clock.png
│  ├─ favicon.ico
│  ├─ licat.png
│  ├─ loading.png
│  ├─ logo.png
│  ├─ quotes.png
│  ├─ readme
│  │  ├─ desktop.png
│  │  └─ mobile.png
│  └─ title.png
│  └─ title@2x.png
│  └─ title@3x.png
├─ index.html
├─ README.md
└─ styles
   ├─ font.css
   ├─ reset.css
   └─ style.css
```

### 4.2 개발 일정

25.08.07(목) ~ 25.08.08(금), 평일 기준 총 2일

## 5. 화면

---

### 5.1 pc 화면

[desktop](./images/readme/desktop.png)

### 5.2 mobile 화면

[mobile](./images/readme/mobile.png)

## 6. 메인 기능

---

- 시멘틱 태그 사용 (header, main, footer, h1, h2, ...)
- flex 사용
- input 태그에 텍스트 필수 입력 체크 (required)
- 팝업 (JavaScript 없이 팝업 위치만 스타일링)
- CSS 방법론 - BEM 방식으로 진행
- 가상요소와 backgroung-image 사용
- 반응형 웹 테스트 (pc/mobile 2단계)
  - 데스크톱 퍼스트 형식으로 진행
  - pc 화면에서 배경색 확장

## 7. 에러와 에러 해결

---

### 7.1

### 7.2

### 7.3

## 8. 개발하며 느낀점

---
