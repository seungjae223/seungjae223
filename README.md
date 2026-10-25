# 안녕하세요, seungjae223입니다.

React를 중심으로 웹서비스의 화면과 사용자 흐름을 구현해 왔습니다.
API 연동과 인증 상태 관리, 비동기 요청·오류 처리를 다루며 기능의 동작을 코드와 테스트로 확인합니다.

## 대표 프로젝트

### 너만 오면 GO

장소 탐색, 여행 일정 구성, 지도 확인과 일정 저장을 연결한 여행 계획 웹서비스의 프론트엔드 프로젝트입니다.

- 삭제 응답이 유실되거나 결과가 불확실할 때 서버 목록을 재조회해 반영 여부를 확인하고, 미확정 상태의 중복 삭제 요청을 제한했습니다.
- 일정·계정 변경 시 요청 취소와 현재 요청 확인을 적용해 이전 응답이 화면 상태를 덮어쓰지 않도록 처리했습니다.
- Kakao·Google 지도를 연동하고 화면 크기 변경에 대응하며, 이벤트와 마커를 정리하는 지도 생명주기를 관리했습니다.

[개발 코드 (dev)](https://github.com/seungjae223/Graduation_project_front/tree/dev) · [삭제 처리](https://github.com/seungjae223/Graduation_project_front/blob/dev/src/utils/useTripDeletion.js) · [비동기 요청 처리](https://github.com/seungjae223/Graduation_project_front/blob/dev/src/RouteResult/useTripResult.js) · [지도 연동](https://github.com/seungjae223/Graduation_project_front/blob/dev/src/RouteResult/RouteResult.jsx)

### MalGo

상황과 관계를 고려한 대화·번역 흐름을 제공하는 AI 문화 번역 서비스의 프론트엔드 프로젝트입니다.

- 로그인 성공 후 상위 React 인증 상태도 갱신되도록 수정하고, 인증 상태 갱신 콜백을 확인하는 테스트를 추가했습니다.
- 모바일 세션 유지 문제에 대응하기 위해 배포 환경의 API 요청을 Netlify의 동일 출처 프록시로 전달하도록 변경했습니다.
- 공통 API 클라이언트에서 세션 만료와 오류 응답을 처리하고, 요청 필드·응답 형식·헤더를 확인하는 테스트를 작성했습니다.

[프로젝트](https://github.com/seungjae223/MalGo_Front) · [인증 상태 갱신 기여](https://github.com/seungjae223/MalGo_Front/commit/4582ba9d5bd7eab40edb4be6809753796fd007b1) · [세션 프록시 기여](https://github.com/seungjae223/MalGo_Front/commit/1e5d1fddd3197ad033563cb054d6aadf2bfd6c18) · [API 테스트](https://github.com/seungjae223/MalGo_Front/blob/main/src/api/malgoApi.test.js)

### 서산 이슈

지역 정보를 탐색하는 서비스에서 메인 화면과 탐색 기능 개발에 참여한 팀 프로젝트입니다.

- 카테고리·페이지·목록/상세보기 상태를 URL 쿼리와 연결한 탐색 화면을 구현했습니다.
- 서로 다른 날씨 API 응답 구조를 화면에서 사용하는 공통 카드 형식으로 변환했습니다.
- 메인 화면에 TypeScript를 적용하고, 트렌딩 키워드와 공지사항의 비동기 데이터 처리를 구현했습니다.

[원본 프로젝트](https://github.com/jaemin-devlog/Seosan-Issue-front) · [탐색 화면 기여](https://github.com/jaemin-devlog/Seosan-Issue-front/commit/8042559b8327538f8a1d8c884dfc4732d5e5cdfd) · [메인 화면·날씨 API 기여](https://github.com/jaemin-devlog/Seosan-Issue-front/commit/f3af9c4ba727e6eb9e68ad9f99da078d42301800)

## 기술 스택

프로젝트에서 사용한 기술입니다.

- **Frontend**: JavaScript, TypeScript, React, React Router, HTML/CSS
- **API**: Axios, Fetch API
- **Testing**: Jest, React Testing Library
- **Collaboration**: Git, GitHub

## 연락처

- [이메일: joyfull0223@gmail.com](mailto:joyfull0223@gmail.com)
- [Instagram: tmdwo_._223](https://www.instagram.com/tmdwo_._223)
