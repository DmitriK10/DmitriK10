# Дмитрий Куприянюк

**Вайб-кодер и автоматизатор.** Собираю бизнес-процессы на n8n и Python: заявка с сайта → разбор моделью → запись в CRM → счёт клиенту. Пишу веб-приложения на Django и Telegram-ботов с ИИ.

Работаю по принципу «сначала процесс, потом код»: описываю схему, нахожу узкие места, автоматизирую то, что даёт эффект, а не то, что интересно писать.

---

## Что делаю

- **Автоматизация процессов** — n8n: вебхуки, формы, HTTP-ноды, Subworkflow, обработка ошибок, расписание, RAG по своей базе знаний.
- **Интеграции с ИИ** — GigaChat, YandexGPT, ProxyAPI, локальные модели через Ollama; строгий JSON на выходе, а не свободный текст.
- **Веб-приложения** — Django и FastAPI: аутентификация, права доступа, фоновые задачи, уведомления, тесты.
- **Telegram-боты** — aiogram и pyTelegramBotAPI, от простых команд до многоагентных сценариев на CrewAI.

## Стек

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/aiogram-2CA5E0?style=flat-square&logo=telegram&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
</p>

---

## Избранные проекты

### [TaskMentor](https://github.com/DmitriK10/Zerocoder_Python/tree/main/taskmentor) — CRM для коучей и наставников
Django 5.2: клиенты, задачи с приоритетами, цели с автопрогрессом, дневник настроения. Вход через Google OAuth, синхронизация задач с Google Calendar, Web Push и Firebase Cloud Messaging, автоперенос просрочек, 6 миграций, 81 тест.

`Python` `Django` `PostgreSQL` `Google API` `FCM` — [описание и запуск](https://github.com/DmitriK10/Zerocoder_Python/tree/main/taskmentor)

### [Автоматизация на n8n](https://github.com/DmitriK10/Automation_on_n8n) — 15 сценариев от BPMN до центра автоматизации
Сквозной процесс: форма → GigaChat разбирает заявку → запись в NocoDB → ссылка на оплату ЮMoney → письмо клиенту. Плюс центр автоматизации с Subworkflow, Error Workflow и RAG-поиском по Qdrant.

`n8n` `GigaChat` `Qdrant` `NocoDB` `Docker`

### [Вайб-кодинг и автономные агенты](https://github.com/DmitriK10/Zerocode_VibecoderAgents) — 12 проектов
От приложений на Python до многоагентных систем на CrewAI: локальная модель через Ollama, тесты, линтеры, Docker Compose.

`CrewAI` `Ollama` `Flask` `Docker` `pytest`

### [CI/CD: FastAPI → Docker → GHCR → деплой](https://github.com/DmitriK10/test-actions)
Пайплайн на GitHub Actions: сборка образа, публикация в GHCR с тегами по SHA, деплой на сервер по SSH. Две джобы, кэш сборки, секреты.

`GitHub Actions` `Docker` `FastAPI` `SSH`

---

## Как я работаю

| Принцип | Что это значит на практике |
|---|---|
| Процесс раньше кода | Сначала схема и узкие места, потом реализация |
| Проверяю, а не предполагаю | Каждый сценарий прогоняется на реальных данных; расхождения с ТЗ фиксируются |
| Тесты как часть работы | 81 тест в TaskMentor, отдельные прогоны в каждом проекте |
| Документирую | У каждого проекта README с установкой, ограничениями и подводными камнями |

---

## Контакты

- Telegram: [@DmitriiKp](https://t.me/DmitriiKp)
- E-mail: [kupriyanyuk.d@yandex.ru](mailto:kupriyanyuk.d@yandex.ru)

Открыт к задачам по автоматизации процессов, интеграциям с ИИ и разработке на Python.

---

<sub>Здесь собраны учебные проекты курсов Zerocoder и собственные работы. Ключи и токены в репозиториях не хранятся.</sub>
