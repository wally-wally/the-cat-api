# :cat: THE CAT API

<br>

## :one: Overview

- THE CAT API를 이용해서 HTML, CSS, Vanilla Javascript 사용 능력을 기르기 위해 간단한 미니 프로젝트를 진행했다.

<br>

## :two: Getting Started

- 해당 repository를 clone 받은 후 `index.html`을 열면 볼 수 있다.
- 만약 안 되는 경우 visual studio code로 연 후 `Live Server` extensions이 설치되어 있다는 가정 하에 `index.html`에서 `Live Server`로 열면 볼 수 있다.

<br>

## :three: Description

### (1) 기능

- 가져올 고양이 데이터 개수를 정한 후 `GET DATA!` 버튼을 누르면 해당 개수만큼 고양이 정보를 볼 수 있다.
- 랜덤 고양이 데이터 가져오기의 `GET DATA!` 버튼을 누르면 랜덤 고양이 데이터 60개를 가져오고 스크롤을 맨 아래로 내리면 자동으로 60개의 데이터를 더 가져온다.

<br>

### (2) 상세 구현 내용

- 입력 값이나 버튼이 눌렸을 때 데이터 가져오는 로직 수행하도록 기본 form 구성
- THE CAT API 이용해서 데이터 가져오기
- 가져온 데이터를 DOM에 그리기
  - 추가로 Event Delegation을 이용해서 고양이 정보를 담은 container tag에 클릭 이벤트 리스너 부여하기
- Modal 만들기
  - Modal이 보였다 안 보였다 구현하고 Modal 안의 `CLOSE` 버튼 누르면 Modal 닫기
- 무한 스크롤을 통해 랜덤 고양이 데이터 가져온 후 스크롤을 맨 아래로 내리면 60개의 데이터 추가로 가져오도록 구현
- 이미지에 대한 Lazy Loading 구현
- Loading Spinner 만들기

<br>

## :four: Screenshot

![01](https://user-images.githubusercontent.com/52685250/90858598-8226de00-e3c1-11ea-8917-d84d32e6d066.PNG)

<img src="https://user-images.githubusercontent.com/52685250/90858603-83f0a180-e3c1-11ea-92eb-8e934021166e.PNG" width="600px">

<br>

## :five: API List

- TheCatAPI : https://thecatapi.com/