# TradeSystem

> Paper trading + multi-agent research + operator UI; LIVE по умолчанию выключен.

## Demo
- **Режим:** paper / local operator glass (не публичный trading endpoint)  
- **Исходники:** private (`paskal635-maker/trade-system`) — walkthrough / invite по запросу

## Стек (названия)
Python · FastAPI · LangGraph · React · Vite · pytest · GitHub Actions

## UI (описание)
- Operator UI (React): статусы, pause/resume/kill, approval-потоки  
- Control API отдельно от execution path  
- Акцент UX: fail-visible баннеры, подтверждения опасных действий, read-mostly поверхность

## Роль автора
Fullstack Python + UI + safety: agents, гейты, control API, operator glass, CI admission, human-veto на LIVE.

## AI-практика (одна фраза)
LLM только advisory; исполнение и лимиты — за детерминированными гейтами и human veto (AI-first ≠ AI-executes).

## Честность
- LIVE disabled by default; paper / SimBroker.  
- Отрицательные результаты валидации не «подкручиваются» под зелёный CI.  
- Детали стратегий, промптов агентов и внутренней политики **не публикуются** в витрине.
