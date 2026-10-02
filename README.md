# 함승주 | Frontend Developer

### 실사용자 2,900명 서비스를 혼자 개발부터 운영까지 책임져 온 프론트엔드 개발자

##### 실서비스 2개 기획, 개발, 배포, 운영 | 활성 사용자 2,900명+ | 누적 이벤트 23,000회+ | SEO 100점 | 정보처리기사

---

## Profile

| 구분 | 내용 |
| --- | --- |
| 성명 | 함승주 (HAM SEUNGJOO) |
| 이메일 | printseungjoo@gmail.com |
| 자격 · 어학 | 정보처리기사, OPIc IH (영어) |
| GitHub | [github.com/printseungjoo](https://github.com/printseungjoo) |

---

## SUMMARY

React와 TypeScript를 기반으로 실제 사용자가 이용하는 웹 서비스를 개발해 온 프론트엔드 개발자입니다. 기능 구현에 그치지 않고 사용자 경험과 프론트엔드 구조를 함께 개선하는 데 집중해 왔습니다.

지도 중심의 탐색 UI 재설계, 렌더링 구조 개선, SSE 기반 실시간 응답 UI, 디자인 시스템을 구축하였으며, 배포 이후에도 베타 테스트를 바탕으로 문제를 발견하고 개선한 경험이 있습니다.

메타데이터와 구조화 데이터 리팩토링을 통해 **Lighthouse SEO 83 → 100점, Best Practices 31 → 92점**으로 품질을 향상시켰습니다.

현재는 **활성 사용자 2,900명 이상**이 이용하는 단독 기획, 개발 서비스를 운영하고 있습니다.

사용자에게 보이는 화면부터 이를 안정적으로 동작하게 만드는 구조까지 책임지는 프론트엔드 개발자를 지향하고 있습니다.

---

## 기술 스택

| 구분 | 기술 |
| --- | --- |
| **프론트엔드** | React, TypeScript, JavaScript, HTML, CSS |
| **스타일, 빌드** | Emotion, styled-components, Vite |
| **백엔드, 배포** | Node.js, Express, MongoDB, Railway |
| **AI 활용** | Cursor, ChatGPT - 구현 방향 탐색, 반복 코드 작성, 코드 리뷰, 리팩터링 후보 탐색에 활용 |

---

# 프로젝트 경력

**실서비스 2개 기획, 개발, 유지보수, 운영**

## Outstanding Spots

**단독 기획, 디자인, 풀스택 개발, 배포, 유지보수, 운영**  
`2024.12 ~ 2026.09 (개발 8개월, 운영 중)`

**위치 기반 대학 제휴 매장 할인 지도 서비스**

제휴 매장 **50곳+** | 활성 사용자 **2,900명+** | 누적 이벤트 **23,000회+** (2025.02.26 ~ 2026.09.29, GA 기준)


`React` `TypeScript` `Vite` `styled-components` `React Router` `React Leaflet` `Node.ts` `Express` `MongoDB`

[서비스](https://outstandingspots.com/) | [GitHub](https://github.com/printseungjoo/outstandingspots) | [화면별 기능 매뉴얼](https://drive.google.com/file/d/1rhclYA0KqOUFmDs2RTQgxbaqRmm63uq5/view?usp=sharing)

### 역할

- 학생, 점주, 관리자 **3개 사용자군의 웹 서비스 기획, 디자인, 풀스택 개발, 배포, 유지보수, 운영까지 단독 개발, 개편 2회**

### 성과

#### [서비스 운영 자동화] 역할 기반 관리 화면 도입으로 매장 정보 수정 절차 3단계 → 1단계

- **문제 |** 운영 병목: **점주 요청 → 개발자 확인 → DB 직접 수정**의 3단계 구조로 개발자 반복 개입
- **판단 |** 권한 분리: 점주, 관리자가 직접 수정하되 오남용은 서버에서 통제하는 셀프서비스 구조 설계
- **실행 |** 점주, 관리자 관리 화면 구현, 역할별 쿠키 3종(12시간) 분리 및 Rate Limit 3종 적용
- **결과 |** 점주, 관리자의 직접 수정 1단계로 단축, 개발자 개입 없는 매장 정보 갱신 구축

#### [지도 렌더링 구조 개선] Kakao Maps SDK를 React Leaflet으로 전환해 중복 로드와 재초기화 제거

- **문제 |** 지도 생명주기: 여러 컴포넌트가 SDK를 각자 로드하고, 상태가 바뀔 때마다 지도가 재생성
- **판단 |** 라이브러리 선정: SDK 유지 최적화와 Leaflet 전환을 번들 크기, 운영 비용, 유지보수로 비교
- **실행 |** SDK 로드 Promise 캐싱, useRef 인스턴스 재사용, 마커 갱신 분리 후 React Leaflet 전환
- **결과 |** 지도와 마커를 React 컴포넌트 단위로 관리, 필터링은 useMemo로 조건 변경 시에만 재계산

#### [UI/UX 개선]

지도와 카테고리가 분리된 탐색 구조를 **전체 화면 지도 중심으로 재설계**하고, 지도 위 카테고리 필터, 자동완성 검색, 한영 전환을 적용해 매장 탐색 흐름 개선

#### [SEO, 웹 표준]

메타데이터와 구조화 데이터 정비로 **Lighthouse SEO 83 → 100점, Best Practices 31 → 92점**

---

## MBTInduce

**프론트엔드 전담, UI UX 디자인, 유지보수 (2인 팀)**  
`2026.03 ~ 2026.06 (개발 4개월)`

**MBTI 성향별 말투로 응답하는 AI 대화 서비스**

베타 테스트 **14명** | **영어 기반** UI와 버전 관리


`React` `TypeScript` `Vite` `Emotion` `React Router` `Node.js` `Express` `Prisma` `PostgreSQL` `OpenAI API`

[서비스](https://www.mbtinduce.com/) | [GitHub](https://github.com/printseungjoo/MBTInduce) | [화면 정의서](https://drive.google.com/file/d/11kU227K9eItTz7KiAYHeTyBycoPvBwxE/view?usp=sharing)

### 역할

- **React, TypeScript, Emotion 기반 프론트엔드 전담:** 기획, UI UX 디자인, 프론트엔드, 배포, 유지보수 (기획, 백엔드는 팀원)
- **API 명세 협의, 코드 리뷰:** 백엔드 개발자와 연동 방식 협의, 백엔드 코드 리뷰 참여, Git 사용 가이드 공유

### 성과

#### [비동기 처리, 실시간 스트리밍] SSE 도입으로 AI 응답을 생성과 동시에 출력

- **문제 |** 사용자 대기 경험: 응답 생성이 끝난 뒤 한꺼번에 표시해 진행 여부를 알 수 없음
- **판단 |** 통신 방식 선정: 서버에서 클라이언트로만 흐르는 데이터라 WebSocket 대신 SSE 채택
- **실행 |** API 계층 설계: apiFetch(REST), apiStream(SSE) 분리, 이벤트 3종별 처리
- **결과 |** 응답 토큰 누적 렌더링으로 첫 글자부터 즉시 표시, 비정상 종료 스트림도 오류 처리

#### [QA, 장애 대응] 베타 테스트 14명 운영으로 출시 전 결함 2건 발견, 해결

**결함 1. 인증 장애:** 회원가입은 성공하는데 이어지는 로그인이 실패한다는 테스터 제보

- **원인 |** 배포 환경 분석: 회원 데이터 저장은 정상, HTTPS 프록시 뒤에서 세션 쿠키가 전달되지 않음
- **실행 |** 쿠키 정책 수정: Express session 프록시 신뢰 설정, 환경별 Secure, SameSite 분리, 제보자 재검증

**결함 2. UI 가독성:** 다크 모드에서 색상 미지정 텍스트가 배경과 겹쳐 읽히지 않는 문제

- **실행:** 색상 미지정 텍스트에 명시적 색상 값을 적용하고, 다크 모드 등 시스템 테마 환경에서 대비와 가독성을 재검증

#### [디자인 시스템]

Emotion ThemeProvider로 **색상 토큰 일원화, UI 컴포넌트 63개 적용, 하드코딩 색상 0건**

---

# 자격, 어학, 수상

| 구분 | 명칭 | 발급기관 | 취득 |
| --- | --- | --- | --- |
| 자격 | **정보처리기사** | 한국산업인력공단 | 2026.09 |
| 어학 | **OPIc 영어 IH (Intermediate High)** | ACTFL, 멀티캠퍼스 | 2026.08 |
