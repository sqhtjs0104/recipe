# 창밖의 레시피
> 현재 시간과 현위치의 날씨를 바탕으로 저장된 레시피를 추천해주는 프로젝트

## 팀원
이젠아카데미 풀스택 수강생 2조 - 서보선, 유지인, 조준희

## 사용 스킬
- HTML, CSS, JS
- Axios
- OpenAPI(식품안전나라 공공데이터활용 식품 레시피 DB)
- OpenWeaterMap OpenAPI(날씨 데이터)
- Google Developers Youtube API

## 프로젝트 개요
Axios 라이브러리를 활용한 Ajax 처리
1) OpenWeatherMap에 현 Geolocation 객체를 전달해 현 위치의 날씨 요청
2) 식품안전나라 OpenAPI에 공개된 레시피 데이터 요청
3) 저장된 레시피 JSON에서 현 시간 및 온도에 맞게 랜덤한 레시피를 추천
4) 레시피 목록 구현 및 각 레시피 클릭 시 단계별 상세 조리법 제시
5) 각 식품 이름으로 유튜브에 검색한 결과 중 조회수 상위 3개 컨텐츠 제시

## 링크
[예시 사이트](https://sqhtjs0104.github.io/recipe)
[보고서 문서](./2조_세미프로젝트_보고서.pdf)
