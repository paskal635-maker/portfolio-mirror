# Parser MSP

> Бизнес-MVP: входящие письма → структурированные поля → заказ в МойСклад + SaaS-кабинет.

## Demo
- **Live URL:** нет публичного URL в витрине (*деплой/доступ — по запросу*)  
- **Исходники:** private (`paskal635-maker/parser-msp`) — walkthrough / invite / test task

## Стек (названия)
Python · FastAPI · SQLAlchemy · Alembic · PostgreSQL · Redis · React · Vite · Docker Compose · GitHub-related deploy docs (Timeweb)

## UI (описание без скринов исходников)
- React-кабинет оператора/SaaS: статусы писем и заказов, настройки интеграций  
- Backend API на FastAPI; фоновая обработка в Compose-стеке (Postgres, Redis, worker-сервис)  
- Observability-контур (health / метрики) как часть hardening после AI-ускорения

## Роль автора
Fullstack + infra: API, модели/миграции, AI-extract, React UI, Docker Compose, деплой-документация.

## AI-практика (одна фраза)
OpenAI structured extract из писем с кэшем/retry — плюс дисциплина доводить AI-черновик hardening’ом (secrets, bind, observability).

## Честность
- Коммерческих пользователей/метрик точности AI **не заявляем**.  
- Известные gaps (security consistency) обсуждаю открыто на walkthrough — это часть AI-first дисциплины, не «прячем».
