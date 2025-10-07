# VibeCraft

AI 기반 데이터 분석 및 시각화 플랫폼. 자연어 대화를 통해 데이터를 업로드하고 최적의 시각화를 자동 생성합니다.

## 프로젝트

### [VibeCraft-Agent](https://github.com/vibecraft25/VibeCraft-Agent)
SQLite 데이터베이스에서 React 시각화 앱을 자동 생성하는 CLI 도구. Gemini CLI 기반으로 원샷 프롬프트만으로 즉시 실행 가능한 앱을 생성합니다(90%+ 성공률).

### [vibecraft-code](https://github.com/vibecraft25/vibecraft-code)
LangChain과 MCP 기반 AI 엔진. 주제 정의, 데이터 처리, RAG 기반 인과관계 분석, 시각화 추천, 코드 생성 파이프라인을 제공합니다.

### [vibecraft-backend](https://github.com/vibecraft25/vibecraft-backend)
FastAPI 기반 SSE 서버. 프론트엔드와 AI 엔진을 연결하며 실시간 스트리밍 API를 제공합니다.

### [Vibecraft-Frontend](https://github.com/vibecraft25/Vibecraft-Frontend)
React 18 + TypeScript 프론트엔드. SSE 실시간 스트리밍과 동적 컴포넌트 렌더링을 지원합니다.

## 기술 스택

- **AI**: Claude, GPT, Gemini
- **프레임워크**: LangChain, MCP, RAG
- **프론트엔드**: React, TypeScript, Vite
- **백엔드**: Python, FastAPI
- **시각화**: Recharts, React Leaflet

<!-- ## 빠른 시작

```bash
# CLI 도구
npm install -g vibecraft-agent
vibecraft-agent --sqlite-path data.sqlite --visualization-type kpi-dashboard

# 전체 시스템 (로컬)
# 1. Frontend
cd Vibecraft-Frontend && npm install && npm run dev

# 2. Backend
cd vibecraft-backend && uv venv && source .venv/bin/activate && uv sync && python main.py
``` -->

## 라이선스

Apache License 2.0
