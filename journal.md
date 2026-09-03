## 2026-09-04
- Настроил Postgres + DBeaver через Docker Desktop (Docker уже был, спасибо докер-компоуз стенду с n8n и Metabase)
- Столкнулся с ошибкой "connection refused" — оказалось, Docker Desktop не был запущен
- Настроил .wslconfig, ограничил WSL2 до 4GB — сработало
- Первый успешный запрос: SELECT version() — PostgreSQL 16.15
