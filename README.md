
# 함승주 | Seungjoo Ham

### Frontend Developer

**활성 사용자 2,900명+ 서비스를 혼자 개발부터 운영까지 책임져 온 프론트엔드 개발자**

실서비스 2개 기획·개발·유지보수·운영 | 누적 활성 사용자 **2,900명+** | 누적 이벤트 **23,000회+** | Lighthouse SEO **100점** | 정보처리기사

---

## About Me

- **이름:** 함승주 (SEUNGJOO HAM)
- **이메일:** printseungjoo@gmail.com
- **GitHub:** https://github.com/printseungjoo
- **자격·어학:** 정보처리기사, OPIc IH (영어)

## Tech Stack

| 구분 | 기술 |
|---|---|
| 프론트엔드 | Next.js, React, TypeScript, JavaScript |
| 스타일 | styled-components, Tailwind CSS (프로젝트 미반영), Emotion |
| 백엔드 | Node.js, SQL (프로젝트 미반영), MongoDB |
| 테스트, 빌드, 배포 | Playwright, GitHub Actions, Vite, Railway |

---

## Projects

### 1. Outstanding Spots

**대학 제휴 매장 할인 지도 서비스**

**2024.12 ~ 2026.10 | 단독 기획·디자인·풀스택 개발·배포·유지보수·운영**

제휴 매장 50곳+ | 누적 활성 사용자 2,900명+ | 누적 이벤트 23,000회+ (GA 기준)

**Tech Stack**

`Next.js` `React` `TypeScript` `styled-components` `Playwright` `Node.js` `Express` `MongoDB` `React Leaflet`

**Links**

- [서비스 바로가기](https://outstandingspots.com/)
- [GitHub Repository](https://github.com/printseungjoo/outstandingspots)

**담당 역할**

학생·점주·관리자 3개 사용자군의 웹 서비스 기획, 디자인, 풀스택 개발, 배포, 유지보수, 운영까지 단독 수행했으며 총 3회 개편했습니다.

#### 주요 성과

**① 프론트엔드 아키텍처 개선 | React SPA → Next.js 16 App Router 마이그레이션**

- **판단:** 라우팅 설정과 화면 구조의 결합을 해소하고, 역할별 공통 레이아웃을 재사용하기 위해 Next.js 선정
- **실행:** App Router 기반 경로 관리 일원화, 3개 역할별 공통 레이아웃 구성 및 브라우저 전용 컴포넌트 분리

**② 지도 렌더링 구조 개선 | Kakao Maps SDK → React Leaflet 전환**

- **판단:** SDK 유지 최적화와 Leaflet 전환을 번들 크기, 운영 비용, 유지보수 관점에서 비교
- **실행:** SDK 로드 Promise 캐싱, useRef 인스턴스 재사용, 마커 갱신 분리 후 React Leaflet 전환
- **개선:** 지도와 마커를 React 컴포넌트 단위로 관리하고, useMemo로 필터 조건 변경 시에만 재계산하도록 구성

**③ E2E 테스트 자동화 | Playwright + GitHub Actions**

- **판단:** 회귀 오류 확인 부담과 오류 발생을 최소화하기 위해 사용자별 핵심 기능 및 API 오류·실패 시나리오 검증
- **실행:** Playwright E2E 테스트 작성 및 GitHub Actions를 통해 Push/PR마다 자동 실행
- **결과:** 7일 기준 오류 수정 커밋 최대 **16건 → 1건 (93.75% 감소)**

**④ UI/UX 개선 | 지도 중심 탐색 구조 재설계**

- **실행:** 지도와 카테고리가 분리된 탐색 구조를 전체 화면 지도 중심으로 재설계
- 지도 위 카테고리 필터, 자동완성 검색, 한영 전환(i18n) 적용
- **결과:** 개편 이후 방학 기간(2026.08)에도 월간 이벤트 **3,300회+**, 사용자당 조회수 **46회** 기록
- 첫 출시 이후 누적 활성 사용자 **2,900명+**, 이벤트 **23,000회+** 달성

**⑤ SEO 및 웹 표준 개선**

- 메타데이터와 구조화 데이터 정비
- Lighthouse SEO **83 → 100점**
- Lighthouse Best Practices **31 → 92점**

---

### 2. MBTInduce

**MBTI 성향별 말투로 응답하는 AI 대화 서비스**

**2026.03 ~ 2026.06 | 프론트엔드 전담·UI/UX 디자인·유지보수 (2인 팀 프로젝트)**

베타 테스트 14명 | 영어 기반 UI 및 버전 관리

**Tech Stack**

`React` `TypeScript` `Emotion` `Vite` `Node.js` `Express` `Prisma` `PostgreSQL` `OpenAI API`

**Links**

- [서비스 바로가기](https://www.mbtinduce.com/)
- [GitHub Repository](https://github.com/printseungjoo/MBTInduce)

**담당 역할**

React, TypeScript, Emotion 기반 프론트엔드 개발 전담. 공동 기획, UI/UX 디자인, 프론트엔드, 배포 및 유지보수를 담당했습니다. 공동 기획, 백엔드 개발은 팀원이 담당했습니다.

#### 주요 성과

**① FE·BE 협업 | API 연동 협의 및 상호 코드 리뷰**

- **기준 통일:** 엔드포인트, 요청·응답 형식 등 API 명세를 합의한 후 구현하고, 해석 차이를 상호 코드 리뷰로 보완
- **영역 경계:** 담당 영역을 넘어 로그인 장애 원인을 서버 세션 설정까지 추적해 직접 수정

**② 비동기 처리·실시간 스트리밍 | SSE 도입**

- **문제:** AI 응답이 모두 생성된 후 한꺼번에 표시되어 사용자가 진행 여부를 확인할 수 없음
- **판단:** 서버에서 클라이언트로 흐르는 단방향 데이터이므로 WebSocket 대신 SSE 채택
- **실행:** apiFetch(REST), apiStream(SSE) 계층 분리
- 이벤트 3종별 처리 및 응답 토큰 누적 렌더링 구현
- 첫 글자부터 즉시 표시하고 비정상 종료 스트림에 대한 오류 처리 적용

**③ QA 및 장애 대응 | 베타 테스트 14명, 결함 2건 해결**

**인증 장애**
- 회원가입은 성공하지만 이후 로그인이 실패하는 문제 발견
- Express session 프록시 신뢰 설정과 환경별 Secure, SameSite 쿠키 정책 수정
- 제보자를 통한 재검증 수행

**UI 가독성 문제**
- 다크 모드에서 일부 텍스트가 배경과 겹쳐 읽히지 않는 문제 발견
- 명시적 텍스트 색상 적용 및 시스템 테마별 대비·가독성 재검증

**④ 디자인 시스템 구축 | Emotion ThemeProvider**

- Emotion ThemeProvider를 활용한 색상 토큰 일원화
- UI 컴포넌트 **63개** 적용
- 하드코딩 색상 **0건**으로 유지보수 간편화

---

## AI 활용 능력

### AI 시대, 저는 프론트엔드 개발자로서 시작(방향성 제시)과 끝(결과 검증)을 주도합니다.

**1. 방향성 제시**

프로젝트의 전체 구조, 기능 요구사항, 기술적 제약조건, 기대 결과를 구체적으로 정의한 후 Cursor를 활용해 구현합니다.

**2. 전문성 확보**

AI의 오류를 식별하고 기술적 판단을 내릴 수 있는 역량을 갖추기 위해 대학교에서 소프트웨어 공학을 포함한 전공 과목을 이수하고, 정보처리기사 취득 및 프론트엔드 전문 강의를 수강했습니다.

**3. 결과 검증**

Cursor의 구현 결과를 ChatGPT로 교차 검증하고, AI가 제안한 코드의 정확성, 설계 적합성 등을 직접 판단하여 수정합니다.


---

## Certifications & Awards

| 구분 | 명칭 | 발급기관 | 취득 |
|---|---|---|---|
| 자격 | 정보처리기사 | 한국산업인력공단 | 2026.09 |
| 어학 | OPIc 영어 IH (Intermediate High) | ACTFL, 멀티캠퍼스 | 2026.08 |

