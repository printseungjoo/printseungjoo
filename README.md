# 프론트엔드 개발자 함승주

사용자 경험(UX) 최적화에 몰입하며 서비스의 완성도를 높이는 성장형 개발자
 
printseungjoo@gmail.com  
https://github.com/printseungjoo

활성 사용자 2,700명 이상을 유치한 웹 서비스 개발 및 리팩토링 경험이 있으며, LCP 로딩 속도를 52.6% 단축하고 불필요한 JavaScript 코드를 대폭 감소시키는 등 웹 성능 최적화 역량을 보유하고 있습니다. 컴퓨터과학 전공 지식과 영어 소통 능력을 바탕으로 팀 내 기술적 이슈를 해결하고 싶습니다.

---

## SKILLS

**LANGUAGE:** JavaScript, TypeScript, HTML, CSS  
**FRAMEWORK:** React, Styled-component, Emotion  
**BACKEND, DB:** Node.js, MongoDB

---

## PROJECTS

### OUTSTANDING SPOTS (위치 기반 대학 제휴 매장 할인 정보 서비스)

**2024.12 - 현재**

1인 기획, 디자인, 풀스택 개발, 운영

**GitHub 링크:** https://github.com/printseungjoo/outstandingspots  
**웹 링크:** https://outstandingspots.com/

#### 기술 스택

**FRONTEND:** React, TypeScript, Styled-component, Vite  
**BACKEND, DB:** Node.js, MongoDB  
**MAP:** Leaflet, OpenStreetMap  
**AUTHENTICATION:** Firebase, SMTP

#### 핵심 서비스 성과

단발성 이벤트 이후 1년 동안 정체되었던 서비스의 공백 원인을 분석하고, UX 및 성능 리팩토링을 단행함.  
그 결과 방학임에도 한 달 내내 유저가 찾아오고 활발한 인터랙션(이벤트 3,300회 이상,사용자당 조회수 46회)이 일어나는 지속 가능한 웹 서비스로 부활  
(전체 활성 사용자 2,700명 이상, 조회수 6,600회 이상, 이벤트 수 19,000회 이상)

#### 사용자 경험(UX) 및 인터페이스(UI) 전면 개편

- **지도 중심의 공간 활용성 극대화** : 지도와 카테고리가 분리되어 시인성이 떨어졌던 구조를 개선하기 위해 지도를 화면 전체에 꽉 차게 배치하고 하단 퀵 카테고리 필터를 도입함. 사용자가 지도 위에서 제휴 매장 위치를 한눈에 파악하고 즉시 필터링할 수 있도록 동선 최적화
- **타겟 맞춤형 다국어(KOR/ENG) 지원** : 글로벌 캠퍼스(외국인 학생 비중이 높은 학업 환경)의 특성을 반영한 한/영 토글 전환 기능을 신규 구현하여 캠퍼스 내 모든 유저의 접근성과 편의성 제고
- **통합 검색 기능 도입** : 매장 이름 혹은 테마로 매장을 검색할 수 있는 실시간 검색바를 구축하여 원하는 제휴 정보나 할인 혜택에 도달하는 탐색 시간 단축

#### 리팩토링 후 성능 최적화(LIGHTHOUSE 지표 기반) 2025.05 → 2026.03

**개선 이유:** 지도 중심 서비스 특성상 초기 로딩 과정에서 지도 SDK 중복 초기화, 반복적인 API 호출 및 불필요한 마커 갱신이 발생해 렌더링 비용과 미사용 JavaScript가 증가하는 문제를 확인

**개선 방법:** 지도 인스턴스 재사용 및 마커 갱신 로직을 최적화하고 SDK 중복 초기화를 제거했으며, API 응답 캐싱과 Kakao Maps → Leaflet 전환을 통해 지도 렌더링 구조를 경량화. Vite 기반 모듈 구조로 재구성하고 불필요한 외부 스크립트와 비표준 HTML 구조를 함께 정리

**개선 결과**

| 성능 지표 및 항목 | Before | After | 개선 효과 |
|---|---:|---:|---|
| 최대 콘텐츠 페인트(LCP) | 1.9초 | 0.9초 | 로딩 속도 52.6% 단축 |
| Performance 점수 | 92점 | 99점 | 전반적인 성능 점수 7점 향상 |
| 미사용 JavaScript 예상 용량 (Dead Code) | 303KiB | 131KiB | Dead Code 172 KiB 절감 |
| 웹 표준/보안(Best Practices) | 31점 | 73점 | 신뢰성 및 보안 지표 42점 향상 |
| 웹 접근성(Accessibility) | 96점 | 100점 | 접근성 지표 만점 달성 |

---

### MBTINDUCE(MBTI 기반 맞춤형 AI 에이전트 서비스)

**2026.03 - 2026.06**

본인의 역할: 기획, 디자인, 프론트엔드 개발, 배포  
팀원 A의 역할: 기획, 백엔드 개발, AI 튜닝

**GitHub 링크:** https://github.com/printseungjoo/MBTInduce  
**웹 링크:** https://www.mbtinduce.com/

#### 기술 스택

**FRONTEND:** React, TypeScript, Emotion  
**BACKEND:** Node.js, Express.js  
**AUTHENTICATION:** Google OAuth  
**AI:** OpenAI API, Prompt Engineering, Personality-based response tuning

#### 프론트엔드 디자인 시스템 개선

Emotion ThemeProvider 기반 디자인 시스템 구축 및 적용: Emotion ThemeProvider를 활용해 색상 토큰을 중앙 관리하여 하드코딩된 색상 코드를 0건으로 유지. 총 65개의 UI 컴포넌트에 일관된 디자인 시스템을 적용하여 코드 유지보수성 및 확장성 향상 (총 231회의 theme.colors 참조 활용)

#### 글로벌 타겟 서비스를 고려한 프론트엔드 및 콘텐츠 구축

서비스 내 모든 UI 텍스트와 콘텐츠를 영어로 기획·구현하여 향후 해외 사용자 확장성을 고려한 아키텍처 설계

프로젝트 전반의 문서화 및 버전 관리를 영어 기반으로 수행하여 글로벌 개발 프로세스 정립

#### 14인 베타 테스트를 통해 UI 시인성 개선 및 장애 대응

다크/라이트 모드 전환 시 색상 미지정으로 인한 텍스트 가인성 이슈를 발굴 및 수정

회원가입 후 로그인 과정에서 발생한 비정상 장애를 추적하여 해결하고 테스터 재검증을 통해 서비스 안전성 확보

---

## LANGUAGE PROFICIENCY

- OPIC IH (INTERMEDIATE HIGH) - English
