# 🍊돌하룻밤🗿 프로젝트
- 시연영상 : https://www.youtube.com/watch?v=wFNZgmsp6rQ
- AWS 배포 링크 : http://dolharufe.s3-website.ap-northeast-2.amazonaws.com/
- 숙박 예약 브랜드 <a href="https://www.airbnb.co.kr/">에어비앤비</a>를 모티브로 한 제주도 지역의 단 '하룻밤' 숙박 예약 웹사이트
- 사이트 UI만 참고, 모든 코드 작성은 직접 진행
- 프론트엔드 깃헙 주소 : https://github.com/wecode-bootcamp-korea/31-2nd-DolHaru-frontend
- 백엔드 깃헙 주소 : https://github.com/wecode-bootcamp-korea/31-2nd-DolHaru-backend

## 1. 개발 기간 및 인원
- 개발 기간 : 2022.04.11 - 2022.04.21 (11일)
- 개발 인원 : 6명 ➡️ Front 4명(김민주, 김보윤, 김동욱, 윤서영) / Back 2명(한상안(PM), 김수훈)

## 2. 사용한 기술 스택
- Front-End : React.js, React Router, Styled-Components, Material UI, Kakao 로그인 및 지도 API, React Slick, Date-Picker
- Back-End : Python, Django, AWS(EC2, S3, RDS), MySQL, Kakao dev(login)
- 협업 툴 : Git, Trello, Slack, Notion

## 3. 구현 기능
- Kakao API를 이용한 소셜 로그인 / 회원가입
- 숙소 위치, 특징, 사진 등 전반적인 정보를 등록 가능한 호스팅 기능 
- 숙소 전체 리스트 페이지 및 다중 필터링, 페이지네이션 기능
- 숙소 상세페이지 보여주기 기능 

## 4. 내가 구현한 기능
**숙소에 대한 위치, 특징, 이름, 사진 등 전반적인 정보를 등록하는 호스팅 기능**을 구현
- pathname과 react router를 이용한 다수의 페이지 간 공통 레이아웃 및 페이지별 변경사항 적용
- 카카오 지도 API를 이용한 주소 검색 기능 구현
- state를 객체로 관리하여 공통된 정보 묶어서 관리 및 다른페이지에서 사용가능하도록 컴포넌트화
- formData를 이용한 여러 장의 사진 업로드 및 Blob 객체를 활용한 사진 미리보기 기능 구현
- useState및 local storage를 이용한 호스팅 정보 전역 관리
- Front 개발 총괄로 프로젝트 초기세팅 및 모든 기능 연결, AWS 배포, 변수명 및 데이터 타입 한 판 정리, 공통 적용 필요핱 지식 문서화 및 공유

