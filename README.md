# Youtube clone coding

## 목적

Youtube 클론코딩하는 프로젝트입니다. 리액트 라우터를 사용하여 라우팅하는 것과 오픈 api를 사용하여 외부 네트워크에서 데이터를 받아오는 실습을 위한 프로젝트입니다.

## 주요 기능

1. 처음 페이지에서는 현재 인기있는 영상 목록들을 보여줍니다.
2. 영상목록을 클릭하게되면 동영상과 채널명, 채널로고, 영상에 대한 설명을 보여줍니다.
3. 우측에는 영상과 관련된 영상 목록들을 보여줍니다.
4. 검색을 하게 되면 검색어와 관련된 영상 목록들이 나오고 영상 목록을 클릭하게 되면 2,3번의 과정이 발생합니다.

## 사용기술

React, tailwindcss, Youtube api, postman, React Router, React Query(Tanstack Query)

## 배운 점

- 기존의 fetch -> axis (일일이 데이터를 json으로 반환할 필요가 없다 + 400대 에러를 throw등으로 따로 처리하지 않아도 자동으로 처리된다.
- React Router의 navigate 또는 Link로 페이지 이동
- api키 등 중요한 정보 env파일에 보관
- timeago.js 라이브러리
- useLocation()
- mock 데이터처리 (오픈 api는 하루에 무한정 받아올 수 없다.)
- useQuery()
- 오픈 api 동적으로 받아오기
- postman을 이용한 api관리

## 어려운 점

- 네트워크 통신
- 다양한 페이지에서 공유하는 상태처리

## 더 공부할 점

- 오픈 api이외에 실시간 데이터베이스를 활용한 프로젝트

## Deploy

https://hilarious-gaufre-e8a528.netlify.app
