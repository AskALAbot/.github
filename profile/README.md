# AskALA 🤖

SK SKALA 과정에서 사용하는 AI 학습/프로젝트 지원 챗봇 **AskALA**입니다.

## What AskALA does
- 과정/프로젝트 Q&A: 과제 요구사항, 개념, 기술 선택을 빠르게 정리
- 실습 가이드: 구현 순서, 체크리스트, 예시 코드/구조 제안
- 문서화 지원: README, 회고, 발표자료(초안) 구조 생성
- 트러블슈팅: 에러 메시지 기반 원인 추정 및 해결 가이드

## Goals
- “질문 → 실행 가능한 답”을 빠르게 제공
- 팀 프로젝트 진행 속도 향상 (설계/구현/문서화)
- 지식 공유가 누적되는 실무형 레포 운영

## Tech Stack (planned)
- Backend: Spring Boot / Java
- Frontend: React 
- AI: LLM API + RAG(벡터DB)
- Infra: Docker / Nginx / Cloud (TBD)

## Repository Guide
- `askala-ai`: 챗봇 핵심 로직 (RAG/프롬프트/대화흐름)
- `askala-server`: 서버 API (인증/대화/로그/관리)
- `askala-front`: FrontEnd

## Contributing
- 이슈/PR 환영합니다.
- 작은 단위로 PR을 올리고, 기능별 README를 함께 업데이트합니다.
