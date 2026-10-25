![seungjae223 · Frontend Development — 네이비 배경의 프론트엔드 개발자 프로필 배너](assets/profile-banner.svg)

# seungjae223

React를 중심으로 웹서비스의 화면과 사용자 흐름을 구현하는 프론트엔드 개발자입니다.
API 연동과 인증 상태 관리, 비동기 요청·오류 처리를 다루며 기능의 동작을 코드와 테스트로 확인합니다.

![React](https://img.shields.io/badge/React-0F172A?style=flat-square&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-0F172A?style=flat-square&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=3178C6)

---

## 대표 프로젝트

### 01. 너만 오면 GO

장소 탐색, 여행 일정 구성, 지도 확인과 일정 저장을 연결한 여행 계획 웹서비스의 프론트엔드 프로젝트입니다.

![React](https://img.shields.io/badge/React-0F172A?style=flat-square&logo=react&logoColor=61DAFB)
![Axios](https://img.shields.io/badge/Axios-0F172A?style=flat-square&logo=axios&logoColor=A78BFA)
![Kakao Maps](https://img.shields.io/badge/Kakao_Maps-0F172A?style=flat-square&logo=kakao&logoColor=FEE500)
![Google Maps](https://img.shields.io/badge/Google_Maps-0F172A?style=flat-square&logo=googlemaps&logoColor=34A853)

- 삭제 응답이 유실되거나 결과가 불확실할 때 서버 목록을 재조회해 반영 여부를 확인하고, 미확정 상태의 중복 삭제 요청을 제한했습니다.
- 일정·계정 변경 시 요청 취소와 현재 요청 확인을 적용해 이전 응답이 화면 상태를 덮어쓰지 않도록 처리했습니다.
- Kakao·Google 지도를 연동하고 화면 크기 변경에 대응하며, 이벤트와 마커를 정리하는 지도 생명주기를 관리했습니다.

[![Source Code](https://img.shields.io/badge/Source_Code-0F172A?style=flat-square&logo=github&logoColor=38BDF8)](https://github.com/seungjae223/Graduation_project_front/tree/dev)

실제 개발 소스는 **dev 브랜치**에 있습니다.
구현 코드: [삭제 처리](https://github.com/seungjae223/Graduation_project_front/blob/dev/src/utils/useTripDeletion.js) · [비동기 요청 처리](https://github.com/seungjae223/Graduation_project_front/blob/dev/src/RouteResult/useTripResult.js) · [지도 연동](https://github.com/seungjae223/Graduation_project_front/blob/dev/src/RouteResult/RouteResult.jsx)

---

### 02. MalGo

상황과 관계를 고려한 대화·번역 흐름을 제공하는 AI 문화 번역 서비스의 프론트엔드 프로젝트입니다.

![React](https://img.shields.io/badge/React-0F172A?style=flat-square&logo=react&logoColor=61DAFB)
![Fetch API](https://img.shields.io/badge/Fetch_API-0F172A?style=flat-square)
![Jest](https://img.shields.io/badge/Jest-0F172A?style=flat-square&logo=jest&logoColor=F8FAFC)

- 로그인 성공 후 상위 React 인증 상태도 갱신되도록 수정하고, 인증 상태 갱신 콜백을 확인하는 테스트를 추가했습니다.
- 모바일 세션 유지 문제에 대응하기 위해 배포 환경의 API 요청을 Netlify의 동일 출처 프록시로 전달하도록 변경했습니다.
- 공통 API 클라이언트에서 세션 만료와 오류 응답을 처리하고, 요청 필드·응답 형식·헤더를 확인하는 테스트를 작성했습니다.

[![Source Code](https://img.shields.io/badge/Source_Code-0F172A?style=flat-square&logo=github&logoColor=38BDF8)](https://github.com/seungjae223/MalGo_Front)
[![My Contributions](https://img.shields.io/badge/My_Contributions-0F172A?style=flat-square&logo=github&logoColor=3B82F6)](https://github.com/seungjae223/MalGo_Front/commit/4582ba9d5bd7eab40edb4be6809753796fd007b1)

프론트엔드 소스와 본인 기여 기록입니다.
기여·검증 코드: [인증 상태 갱신](https://github.com/seungjae223/MalGo_Front/commit/4582ba9d5bd7eab40edb4be6809753796fd007b1) · [세션 프록시](https://github.com/seungjae223/MalGo_Front/commit/1e5d1fddd3197ad033563cb054d6aadf2bfd6c18) · [API 테스트](https://github.com/seungjae223/MalGo_Front/blob/main/src/api/malgoApi.test.js)

---

### 03. 서산 이슈

지역 정보를 탐색하는 서비스에서 메인 화면과 탐색 기능 개발에 참여한 팀 프로젝트입니다.

![React](https://img.shields.io/badge/React-0F172A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=3178C6)
![React Router](https://img.shields.io/badge/React_Router-0F172A?style=flat-square&logo=reactrouter&logoColor=F87171)

- 카테고리·페이지·목록/상세보기 상태를 URL 쿼리와 연결한 탐색 화면을 구현했습니다.
- 서로 다른 날씨 API 응답 구조를 화면에서 사용하는 공통 카드 형식으로 변환했습니다.
- 메인 화면에 TypeScript를 적용하고, 트렌딩 키워드와 공지사항의 비동기 데이터 처리를 구현했습니다.

[![Source Code](https://img.shields.io/badge/Source_Code-0F172A?style=flat-square&logo=github&logoColor=38BDF8)](https://github.com/jaemin-devlog/Seosan-Issue-front)
[![My Contributions](https://img.shields.io/badge/My_Contributions-0F172A?style=flat-square&logo=github&logoColor=3B82F6)](https://github.com/jaemin-devlog/Seosan-Issue-front/commit/8042559b8327538f8a1d8c884dfc4732d5e5cdfd)

원본 팀 저장소와 본인 기여 기록입니다.
기여 코드: [탐색 화면](https://github.com/jaemin-devlog/Seosan-Issue-front/commit/8042559b8327538f8a1d8c884dfc4732d5e5cdfd) · [메인 화면·날씨 API](https://github.com/jaemin-devlog/Seosan-Issue-front/commit/f3af9c4ba727e6eb9e68ad9f99da078d42301800)

---

## 기술 스택

### Frontend

![JavaScript](https://img.shields.io/badge/JavaScript-0F172A?style=flat-square&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=3178C6)
![React](https://img.shields.io/badge/React-0F172A?style=flat-square&logo=react&logoColor=61DAFB)
![React Router](https://img.shields.io/badge/React_Router-0F172A?style=flat-square&logo=reactrouter&logoColor=F87171)
![HTML](https://img.shields.io/badge/HTML-0F172A?style=flat-square&logo=html5&logoColor=E34F26)
![CSS](https://img.shields.io/badge/CSS-0F172A?style=flat-square&logo=css&logoColor=38BDF8)

### API & Testing

![Axios](https://img.shields.io/badge/Axios-0F172A?style=flat-square&logo=axios&logoColor=A78BFA)
![Jest](https://img.shields.io/badge/Jest-0F172A?style=flat-square&logo=jest&logoColor=F8FAFC)
![React Testing Library](https://img.shields.io/badge/React_Testing_Library-0F172A?style=flat-square&logo=testinglibrary&logoColor=E33332)

### Tools

![Git](https://img.shields.io/badge/Git-0F172A?style=flat-square&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-0F172A?style=flat-square&logo=github&logoColor=F8FAFC)

---

## 연락처

[![Email](https://img.shields.io/badge/Email-0F172A?style=flat-square&logo=gmail&logoColor=38BDF8)](mailto:joyfull0223@gmail.com) joyfull0223@gmail.com

[![Instagram](https://img.shields.io/badge/Instagram-0F172A?style=flat-square&logo=instagram&logoColor=38BDF8)](https://www.instagram.com/tmdwo_._223) @tmdwo_._223

---

<details>
<summary>GitHub Activity</summary>

![GitHub 통계 — seungjae223의 공개 활동 요약](https://github-readme-stats.vercel.app/api?username=Seungjae223&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1)

[GitHub 프로필에서 활동 보기](https://github.com/seungjae223)

</details>
