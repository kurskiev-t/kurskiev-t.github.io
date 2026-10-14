# C# / .NET Backend Developer (Middle+)

**Открыт к предложениям** — удалённо / гибрид · Москва · самозанятый

### Кратко

Middle+ Backend-разработчик с **9+ лет** опыта в IT и **5+ лет** коммерческой разработки на .NET. Специализируюсь на высоконагруженных микросервисах: ASP.NET Core 8, GraphQL, RabbitMQ, PostgreSQL, Docker. Работал на проектах для Билайн/Amdocs и Столото. Ускорял production ETL в 2 раза.

Выпускник **МГТУ им. Баумана** (ИУ3). Английский — C1.

---

## Навыки

- **Языки и платформы:** C#, .NET 8, ASP.NET Core
- **Архитектура:** микросервисы, REST API, GraphQL (HotChocolate), CQRS, Event Sourcing, Clean Architecture, MediatR
- **Данные:** PostgreSQL, MS SQL, MongoDB, EF Core
- **Инфраструктура:** RabbitMQ, Quartz.NET, Docker, GitLab CI/CD
- **Тесты:** xUnit, unit / модульные тесты
- **Прочее:** Git, Scrum/Agile, PowerShell

---

## Опыт работы

### Software Development Specialist — Amdocs / Билайн  
*Ноябрь 2023 — Июнь 2025 · 1 год 8 месяцев*

Backend высоконагруженной системы учёта сетевой инфраструктуры (Билайн) на .NET 6 / ASP.NET Core 8.

- GraphQL API (HotChocolate) + EF Core, решение N+1 через DataLoader
- RabbitMQ и Quartz.NET для очередей и фоновых задач
- Unit-тесты (xUnit), оптимизация запросов PostgreSQL
- MediatR, Docker, GitLab CI/CD
- ETL-конвейер синхронизации сетевой инфраструктуры: сверка через стейджинговые таблицы, маппинг сущностей, асинхронная дистрибуция через RabbitMQ
- Рефакторинг production ETL — ускорение загрузки данных **в 2 раза** (с 30–60 до 15–30 минут)

**Стек:** .NET 6 / ASP.NET Core 8, GraphQL, EF Core, MediatR, RabbitMQ, Quartz.NET, PostgreSQL, Docker, xUnit, GitLab

---

### Разработчик — Столото  
*Август 2020 — Январь 2021 · 6 месяцев*

Backend нового веб-сервиса лотерей на ASP.NET Core.

- CQRS + Event Sourcing, MediatR
- REST API, пагинация, фильтрация, интеграции
- Unit- и модульные тесты, рефакторинг legacy
- Валидация JSON Schema (Newtonsoft.Json.Schema), генерация документации
- Доработки WPF-клиента терминалов (MVVM)

**Стек:** ASP.NET Core, WPF, MediatR, CQRS, Event Sourcing, EF Core, GitLab, Jira, Confluence

---

### Back-end программист — Школа дизайна НИУ ВШЭ  
*Ноябрь 2019 — Август 2020 · 10 месяцев*

Проектирование и разработка микросервисов продукта.

- Сервисы на .NET Core 3.1 и Node.js (Express) для генерации PDF
- Структура БД MongoDB, Docker-скрипты деплоя
- REST API для внутренних проектов, миграция с Web Forms на API
- Самостоятельное проектирование архитектуры сервисов

**Стек:** .NET Core, ASP.NET Core, JavaScript, MongoDB, Docker

---

### Ранний IT-опыт — Softline, EY, Hostline, Типография Акура и др.  
*2013 — 2019*

Системный инженер / Helpdesk / младший программист: поддержка инфраструктуры, автоматизация, начало коммерческой разработки на C# / .NET (Windows Forms, Clean Architecture, PostgreSQL).

<details class="chronology">
<summary>Вся хронология — остальные места работы</summary>

<p class="chronology-note">Без повтора блоков выше (Amdocs, Столото, ВШЭ). По убыванию дат.</p>

#### Разработчик C# — Айтик
*Октябрь 2022 — Май 2023 · 8 месяцев*

Backend сервиса акций по продуктам компании (WCF).

#### Разработчик систем предоставления ИТ-сервисов — ВТБ Капитал
*Декабрь 2021 — Январь 2022 · 2 месяца*

Портал самообслуживания, автоматизация ИТ-сервисов и первой линии поддержки.

**Стек:** C#, PowerShell, System Center Service Manager / Orchestrator

#### Младший программист — Типография Акура
*Ноябрь 2018 — Август 2019 · 10 месяцев*

Корпоративное решение для производства: новый функционал, рефакторинг, SQL/триггеры, документация в Confluence, задачи в Jira.

**Стек:** C#, Windows Forms, Clean Architecture, PostgreSQL

#### Инженер-программист C# WPF — Caspel
*Октябрь 2018 — Ноябрь 2018 · 2 месяца*

Доработка функционала, исправление ошибок, настройка MS SQL и модулей ERP под клиентов.

#### Системный инженер — Softline
*Июнь 2016 — Август 2017 · 1 год 3 месяца*

Аутсорс у заказчика (Herbalife): IT-проекты, сети, безопасность (SEP, PGP), поддержка пользователей, обучение, внедрение ПО и онлайн-касс.

#### Специалист IT help desk — EY Russia
*Сентябрь 2014 — Май 2016 · 1 год 9 месяцев*

Поддержка IT-инфраструктуры офиса (~3000 сотрудников): ServiceNow, оборудование, сети, учётные записи.

#### Специалист техподдержки — Hostline
*Январь 2013 — Июнь 2013 · 6 месяцев*

Поддержка клиентов хостинга: сайты, CMS, домены, серверы, биллинг.

</details>

---

## Проекты

### [User Secrets Manager](https://github.com/kurskiev-t/UserSecretsManager)  
Расширение для Visual Studio: удобное переключение секций user secrets (LOCAL / DEV / PROD) между проектами решения.

- В [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=kurskiev-t.userSecretsManager) · **183+ скачиваний**
- Backup / Restore, мультиязычные секции, открытие secrets-файла из IDE

### [BuzzMini](https://github.com/kurskiev-t/BuzzMini)  
Локальная offline push-to-talk диктовка на faster-whisper (Windows, NVIDIA CUDA, PyQt6). Без отправки аудио в облако.

---

## Образование

**Бакалавр** — МГТУ им. Н.Э. Баумана, Москва (2014)  
Факультет информатики и систем управления · Информационные системы и телекоммуникации (**ИУ3**)

---

## Контакты

| | |
| --- | --- |
| **Телефон** | [+7 (903) 500-57-67](tel:+79035005767) |
| **Telegram** | [@kurskievt](https://t.me/kurskievt) |
| **Email** | [kurskievtr@gmail.com](mailto:kurskievtr@gmail.com) |
| **GitHub** | [github.com/kurskiev-t](https://github.com/kurskiev-t) |
| **Город** | Москва |

---

*PDF-резюме можно запросить по контактам выше.*
