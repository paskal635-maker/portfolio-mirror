# Никита Ажгибесов — AI-first Fullstack / Vibe Coder

Публичная **витрина проектов** (не исходники).

Собираю MVP end-to-end (бэк + фронт + деплой) с Cursor и LLM, с обязательной проверкой сгенерированного кода: fail-closed на деньгах/LIVE, тесты, security review.

| | |
|--|--|
| **ФИО** | Ажгибесов Никита Игоревич |
| **GitHub** | [paskal635-maker](https://github.com/paskal635-maker) |
| **Телефон** | +79920078448 |
| **Live demo** | [VibeBase → vibehub-topaz.vercel.app](https://vibehub-topaz.vercel.app) |

> **Исходники private.** По запросу рекрутера/компании: Zoom walkthrough, временный invite collaborator, или test task. Этот репозиторий намеренно **без** бизнес-логики, схем БД, промптов и секретов.

---

## Проекты за 30 секунд

| Проект | Что это | Live | Стек (названия) |
|--------|---------|------|-----------------|
| [**VibeBase**](./projects/vibebase.md) | Каталог vibe/AI-проектов | [Demo](https://vibehub-topaz.vercel.app) | Next.js, React, TypeScript, Prisma, PostgreSQL, Docker, GitHub Actions, Vercel |
| [**Parser MSP**](./projects/parser-msp.md) | Письма → структура → МойСклад (SaaS) | — (по запросу) | Python, FastAPI, SQLAlchemy, PostgreSQL, Redis, React, Vite, Docker |
| [**TradeSystem**](./projects/trade-system.md) | Paper trading + AI agents + operator UI | Paper / local | Python, FastAPI, LangGraph, React, Vite, pytest, GitHub Actions |

---

## Карточки

### 1. VibeBase
Каталог vibe-code / AI-проектов с поиском, фильтрами и production-деплоем.  
**Роль:** fullstack + деплой + UX.  
**AI-практика:** продукт про vibe coding; CI/security/compliance доведены end-to-end.  
**Demo:** https://vibehub-topaz.vercel.app · **исходники private**

### 2. Parser MSP
Бизнес-MVP: почта → AI-извлечение полей → заказ во внешней системе + кабинет.  
**Роль:** fullstack + worker/infra + AI-extract.  
**AI-практика:** OpenAI structured extract + кэш/retry; коммиты с Cursor.  
**Исходники private** · walkthrough / test task по запросу

### 3. TradeSystem
Исследовательская торговая платформа: agents, гейты, operator UI; LIVE выключен по умолчанию.  
**Роль:** fullstack Python + UI + safety gates.  
**AI-практика:** LLM только advisory; ордера и лимиты — за детерминированными гейтами.  
**Исходники private** · paper demo / walkthrough по запросу

---

## Как получить доступ глубже

1. **Этот репозиторий / витрина** — публично, без кода продуктов.  
2. **Live demo VibeBase** — без логина: https://vibehub-topaz.vercel.app  
3. **Zoom / screen share** — 15–20 мин walkthrough по любому из трёх.  
4. **Invite collaborator** (read) на конкретный private репо — временно, под NDA/по запросу.  
5. **Test task** компании — предпочтительный формат «гипотеза → кликабельный результат».

---

## Что намеренно скрыто

- Исходный код приложений  
- Схемы БД, миграции, внутренние API-контракты  
- Промпты, ключи, `.env`, платежные/OAuth секреты  
- Детальная архитектура / adversarial surface trading-системы  

Стек указан **на уровне названий технологий** — достаточно для скрининга, недостаточно для копирования продукта.

---

Витрина для отклика: Fullstack (AI-first) и похожие роли.
