# 권혁호 | Frontend Developer

[![Tokscale Stats](https://tokscale.ai/api/embed/hyukhogwon/svg?theme=light&compact=1)](https://tokscale.ai/u/hyukhogwon)

[Email](mailto:hyukho.career@gmail.com) · [GitHub](https://github.com/hyukhogwon)

5년 이상의 프론트엔드 개발 경험을 가진 개발자입니다. 레거시 현대화, 프론트엔드 아키텍처 설계, 디자인 시스템, 모노레포/Micro Frontend 환경의 공통 모듈 설계에 관심을 두고 일해왔습니다.

React/Vue가 공존하는 환경, 여러 배포 구조가 섞인 서비스, 공통 패키지 기반의 UI/도메인 모듈처럼 서로 다른 기술 스택과 실행 환경 사이에서 일관된 사용자 경험과 개발 구조를 만드는 작업에 강점이 있습니다.

최근에는 Claude Code Channels 공개 프로토콜을 참고해 Slack을 통해 원격으로 Claude Code 세션에 작업을 요청하고 결과를 확인할 수 있는 도구를 만들고 있습니다.

---

## Experience

### 여기어때컴퍼니 · Frontend Developer

2024.10 ~ 현재

숙박 플랫폼과 항공 서비스의 프론트엔드 개발을 담당하고 있습니다.

- 항공 서비스 검색 경험 확장을 위한 프론트엔드 기능 개발
- 여러 서비스 도메인에서 사용할 수 있는 검색 모듈 구조 설계
- React/Vue 양쪽에서 사용할 수 있는 크로스 프레임워크 디자인 시스템 개선
- 신규 광고 관리 플랫폼의 프론트엔드 아키텍처 설계 및 런칭 참여
- Quill Editor 기반 공통 에디터 모듈 개발

### 현대카드 · Frontend Developer

2021.12 ~ 2024.10

AI 기반 마케팅 플랫폼 Universe의 프론트엔드 개발을 담당했습니다.

- TrueNorth 마케팅 타겟 추출 서비스 프론트엔드 개발
- Elasticsearch 검색 조건 payload 개선을 통한 응답시간 약 30% 단축
- Google Maps API 기반 커스텀 드로잉 인터랙션 구현
- GalaxyNorth 일반 사용자/관리자 프로젝트의 모노레포 통합
- REST API 통신 레이어와 데이터 페칭 패턴 표준화
- Lighthouse 기반 모니터링을 통해 주요 페이지의 Lighthouse 점수 80점 이상 관리

### KT · Frontend Developer

2021.03 ~ 2021.11

정보보안팀 사내 서비스 개발에 참여해, 메일 기반 비정형 업무 프로세스를 웹 애플리케이션으로 전환하는 프로젝트의 프론트엔드 기능 개발을 수행했습니다.

---

## Projects

### [channel-slack](https://github.com/hyukhogwon/channel-slack)

Claude Code Channels용 Slack 채널 플러그인입니다.

- Claude Code Channels 공개 프로토콜을 참고해 Slack 기반 채널 플러그인 구현
- Slack Socket Mode 기반 양방향 메시징 흐름 구성
- Claude Code 세션 응답을 Slack으로 전달하는 인터페이스 구현
- allowlist 기반 접근 제어와 DM 중심 운영 구조 적용

**Tech Stack**: TypeScript, Node.js, Slack Socket Mode, Claude Code Channels MCP

### [claude-news](https://github.com/hyukhogwon/claude-news)

Claude Code 및 Anthropic 관련 소식을 자동 수집·요약해 Slack으로 전달하는 개인 운영 시스템입니다.

- GitHub Actions cron 기반 RSS 수집 파이프라인 구성
- GitHub Releases, Anthropic Blog, Reddit, Hacker News 등 여러 소스 수집
- LLM 요약 후 Slack Block Kit 카드로 발송
- `--dry-run`, `--since` 등 운영용 CLI 옵션 제공

**Tech Stack**: TypeScript, Node.js, GitHub Actions, Groq API, Slack Block Kit

---

## Skills

**Frontend**: TypeScript, React, Next.js, Vue

**Architecture**: Design System, Monorepo, Micro Frontend, npm package

**State & Data**: Recoil, React Query, Zustand

**Build & Automation**: Vite, Webpack, Turborepo, GitHub Actions

**Quality**: Jest, React Testing Library, Vitest, Lighthouse
