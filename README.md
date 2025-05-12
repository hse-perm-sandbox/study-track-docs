# study-track-docs
Документация web-приложения для управления задачами 

Study Track — web-приложение, ориентированное на студентов, с функциями, специально адаптированными под учебный процесс: задачи, категории, приоритеты, напоминания, календарное отображение.

## Функции приложения

- Регистрация и вход в аккаунт
- Создание, редактирование, просмотр и удаление задач
- Классификация задач по категориям
- Установка дедлайнов
- Настройка уведомлений (email)
- Отображение задач в календаре

Приложение реализуется с использованием клиент-серверной архитектуры:
- Клиентская часть - React-приложение, написанное на TypeScript, репозиторий [study-track-front](https://github.com/hse-perm-sandbox/study-track-front/tree/main).
- Серверная часть - REST API, написанное на Python с использованием FastAPI, репозиторий [study-track-api](https://github.com/hse-perm-sandbox/study-track-api/tree/main).

Для разработки диаграмм можно использовать библиотеку [mermaid](https://mermaid.js.org/) и [онлайн-редактор диаграмм](https://mermaid.live/edit).

Для работы с диаграммами в VS Code рекомендуется установить расширения:
- Markdown Preview Mermaid Support
- Code Spell Checker
- Russian - Code Spell Checker, после установки активировать проверку орфографии через Commands (use F1 or View -> Command Palette...):
    * Enable Russian Spell Checker Dictionary
    * Enable Russian Spell Checker Dictionary in Workspace