# AI Agent Engineering

LLM 시대의 자율 AI 시스템 설계와 구현

이 저장소는 한국어 기반의 **AI Agent Engineering** 책 프로젝트를 위한 공개 아카이브입니다. 목표는 AI 에이전트의 개념부터 프레임워크, 아키텍처, 프로덕션 운영까지 하나의 흐름으로 정리하는 것입니다.

## 이 저장소의 목표

- AI 에이전트의 핵심 개념을 체계적으로 정리한다
- 실무 중심의 Agent Engineering 방법론을 문서화한다
- Python 기반 예제 코드를 함께 제공한다
- 책, 강의, 워크숍으로 확장 가능한 공개 아카이브를 만든다

## 대상 독자

- AI 엔지니어
- 백엔드/플랫폼 개발자
- LLM 기반 제품을 설계하는 PM/테크 리드
- 멀티 에이전트 시스템과 Agentic RAG를 실무에 적용하려는 사람

## 책 구성

### Part 1. Foundations
- AI 패러다임의 변화
- 챗봇 vs 에이전트
- 에이전트의 뇌
- Tool 사용
- Memory 시스템
- MCP

### Part 2. Frameworks
- Claude Agent SDK
- OpenAI Agents SDK
- LangGraph
- CrewAI
- No-code Agent Builders
- Google A2A

### Part 3. Architecture
- Single vs Multi Agent
- Orchestrator Pattern
- ReAct & 추론 패턴
- Agentic RAG
- Human-in-the-Loop
- Guardrails & Safety

### Part 4. Production
- Agent Testing
- 배포 & 운영
- 실전 프로젝트: Research Agent
- 실전 프로젝트: Multi-Agent Pipeline
- 2026 트렌드 총정리
- Agent Engineer 커리어 전략

## 저장소 구조

- `book/` : 책 원고
- `examples/` : Python 예제 코드
- `diagrams/` : 아키텍처 및 워크플로 다이어그램
- `templates/` : 챕터/프로젝트 템플릿
- `docs/` : 참고 문서 및 출판 관련 문서

## 작업 원칙

- 문서는 한국어로 작성한다
- 예제 코드는 Python 기준으로 작성한다
- 챕터는 개념 → 구조 → 사례 → 실습 → 요약 순서로 정리한다
- 실무 적용 가능성을 항상 우선한다

## 시작하기

```bash
git clone https://github.com/scottnaddle/ai-agent-engineering.git
cd ai-agent-engineering
```

## 기여 방식

기여 전에는 `CONTRIBUTING.md`를 확인하세요.
주요 변경은 챕터 단위 브랜치에서 작업한 뒤 Pull Request로 합치는 것을 권장합니다.

## 로드맵

프로젝트 진행 계획은 `ROADMAP.md`에 정리합니다.

## 라이선스

이 저장소는 [MIT License](LICENSE)를 따릅니다.
