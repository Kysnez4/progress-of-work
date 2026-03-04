# 📁 Портфолио Python-разработчика

## Содержание портфолио

### 1. Проект: Habit Tracker API
**Сервис для отслеживания полезных привычек с Telegram-уведомлениями**

🔗 **Ссылки:**
- [Репозиторий на GitHub](https://github.com/Kysnez4/Habit_Tracker)
- [Документация API (Swagger)](https://github.com/Kysnez4/Habit_Tracker)

**Что реализовано:**
- Регистрация и JWT-авторизация
- CRUD для привычек с валидацией (периодичность 1-7 дней, время ≤120 сек)
- Просмотр публичных привычек
- Telegram-уведомления через Celery
- Пагинация, права доступа, фильтрация

**Стек:** Django, DRF, PostgreSQL, Celery, Redis, JWT, Telegram API

---

### 2. Проект: LMS-сервис API
**LMS-система, в которой каждый желающий может размещать свои полезные материалы или курсы**

🔗 **Ссылки:**
- [Репозиторий на GitHub](https://github.com/Kysnez4/Frest_django)
- [Демо-версия](http://158.160.73.53:8000/) (выключил)

**Что реализовано:**
- Полная контейнеризация (Docker Compose)
- Сервисы: web, db, redis, celery, celery-beat
- CI/CD через GitHub Actions (автодеплой)
- CRUD для урок и курсов.
- Регистрация и JWT-авторизация.
- готовый Docker файл и Docker Compose
  
**Стек:** Docker, Docker Compose, GitHub Actions, Nginx
