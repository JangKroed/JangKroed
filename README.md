# 장용호 | Backend Developer

Node.js와 TypeScript를 중심으로 **실시간 메신저와 기업 내부 데이터 플랫폼**을 개발했습니다.
요구사항이 바뀌었을 때 수정할 위치가 보이고, 변경 결과를 확인할 수 있는 코드를 지향합니다.

[Email](mailto:didlsdydgh@gmail.com) · [공개 프로젝트](#공개-프로젝트)

## 실무에서 다룬 문제

- **실시간 통신** — 병원 그룹웨어의 메신저를 주도적으로 개발했습니다. 서로 다른 Socket.IO 서버에 연결된 사용자 간 통신 문제를 Redis Adapter 적용으로 해결했습니다. 적용·확인 범위는 개발·테스트 환경입니다.
- **고객사별 데이터 처리** — 조건문과 하드코딩이 모여 있던 Excel 처리 로직에서 컬럼명·한글 표시명·타입·단위를 개발자가 관리하는 설정 파일로 분리하고, 정해진 양식에 맞게 업로드·다운로드 매핑을 정리했습니다.
- **데이터 플랫폼** — 검색, 접근 권한, 다운로드 요청·승인, 감사 정보와 외부 데이터 수집·동기화 기능을 개발했습니다.
- **개발 환경과 배포** — 고객사 개발·테스트 환경은 Docker Compose로 구성하고, 사내 개발 서버에서는 Jenkins와 GitHub를 연동한 배포 작업을 설정했습니다.

## 사용 기술

| 영역 | 기술 |
| --- | --- |
| Backend | Node.js, JavaScript, TypeScript, NestJS, Express |
| 실시간 통신 | Socket.IO, Redis Adapter |
| 데이터 | MongoDB, Redis, PostgreSQL, Elasticsearch |
| 실행 환경·배포 | Docker, Docker Compose, AWS, Nginx, Jenkins |
| 화면 구현 경험 | Vue.js |

Jest는 개인적인 기본 테스트 작성 학습 수준이며, Artillery는 간단한 실시간 통신 테스트 경험이 있습니다.

## 공개 프로젝트

아래 저장소는 교육·학습 과정에서 진행한 프로젝트입니다. 회사 업무와 최근 비공개 프로젝트는 별도로 구분합니다.

| 프로젝트 | 내용 | 살펴볼 부분 |
| --- | --- | --- |
| [MUD](https://github.com/Hanghae-GREATGREAT/MUD) | 항해99 팀 프로젝트 · 텍스트 기반 온라인 게임 | Socket.IO 기반 통신, 서버 구성, 팀의 기술 선택과 트러블슈팅 기록 |
| [Cyworld Refactoring](https://github.com/refactoring-CyworldCloneCoding/BE-TypeScript) | TypeScript 기반 싸이월드 클론 리팩터링 · 백엔드 담당 | 미니홈피 기능, 프로젝트 구조와 API 문서 |
| [Wanted Backend Assignment](https://github.com/JangKroed/wanted-pre-onboarding-backend) | 개인 백엔드 과제 · 회원 인증과 게시판 API | 계층 분리, 인증·작성자 권한 처리, 실행·테스트 안내 |

팀 프로젝트 저장소의 설명은 팀 전체의 구현을 포함합니다. 공개 프로젝트는 당시의 학습 기록이며, 현재 운영 중인 서비스라는 의미는 아닙니다.

## 최근 개발 활동

최근 개인 작업은 주로 비공개 저장소에서 진행하고 있습니다.

**ARCANISTER**에서는 Swift로 macOS 화면 캡처, ROI 기반 인식, OCR 결과 안정화와 상태 변화 표시를 개발하고 있습니다. Codex를 코드 탐색·반복 구현·디버깅에 활용하며 학습을 이어가고 있습니다.

## 개발할 때 중요하게 생각하는 것

- 함께 바뀌는 업무 규칙은 모으고, 공통 처리와 고객사별 차이는 구분합니다.
- 기술 이름보다 문제와 선택 이유, 직접 담당한 범위를 설명하려고 합니다.
- 실제로 확인한 결과와 앞으로 개선할 아이디어를 구분합니다.
