# Hi there, I'm von1336 👋

Full-Stack разработчик и системный инженер. Специализируюсь на надежных серверных архитектурах на Python (FastAPI, Django, Celery), реалтайм-системах, десктопе на C# .NET/WPF и интерактивной веб-графике на Canvas 2D/3D.

[![Live Showcase Hub](https://img.shields.io/badge/LIVE%20SHOWCASE-INTERACTIVE%20HUB-00f0b5?style=for-the-badge&logo=githubpages&logoColor=000000)](https://von1336.github.io/interactive-web-showcase/)
[![Telegram](https://img.shields.io/badge/Telegram-@simulcra-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/simulcra)

> 🚀 **[Интерактивное портфолио и лаборатория архитектуры](https://von1336.github.io/interactive-web-showcase/)**  
> Интерактивный хаб со всеми проектами, живым поиском, 3D Canvas, процедурным звуком и глубоким разбором архитектуры:  
> 👉 **[von1336.github.io/interactive-web-showcase](https://von1336.github.io/interactive-web-showcase/)**

![banner](assets/banner.svg)

---

## ⚡ Ключевые компетенции

- **Backend & High-Load:** Python (FastAPI, Django 5, Celery), Node.js (Express), Redis, PostgreSQL, Docker Compose. Атомарные транзакции (`select_for_update`), ликвидация N+1 запросов, асинхронные очереди и отказоустойчивые кэши.
- **AI & Real-Time:** RAG-архитектуры (векторный поиск ChromaDB / Qdrant), потоковая генерация SSE с низкой задержкой, многопользовательские WebSockets с шиной Redis Pub/Sub.
- **Desktop & Автоматизация:** C# / .NET / WPF десктоп-лаунчеры с автообновлением через GitHub Releases API, Telegram-боты на aiogram 3.x, устойчивые парсеры данных (BS4, HTTP-пулы, ретраи).
- **Frontend & Интерактив:** React 18/19, чистый JavaScript (ES6+ Zero-Build), интерактивный 2D/3D Canvas (60 FPS, физика Кеплера, системы частиц) и процедурный синтез Web Audio API.

---

## 🏛️ Проекты и репозитории

| Проект | Стек | Описание |
| :--- | :--- | :--- |
| **[fastapi-rag-ai-assistant](https://github.com/von1336/fastapi-rag-ai-assistant)** | `FastAPI` `ChromaDB` `SSE` `Docker` | AI-ассистент с RAG-поиском по базе знаний, потоковыми ответами (SSE) и rate limiting |
| **[fastapi-kanban-board-realtime](https://github.com/von1336/fastapi-kanban-board-realtime)** | `FastAPI` `WebSockets` `Redis` `PostgreSQL` | Real-time канбан-доска с мгновенной синхронизацией через WebSockets и шину Redis Pub/Sub |
| **[django-ecommerce-api-backend](https://github.com/von1336/django-ecommerce-api-backend)** | `Django 5` `DRF` `Celery` `PostgreSQL` | Энтерпрайз e-commerce бэкенд: атомарный резерв товаров (`select_for_update`), Celery-очереди |
| **[aiohttp-celery-news-aggregator](https://github.com/von1336/aiohttp-celery-news-aggregator)** | `aiohttp` `Celery` `Redis` `PostgreSQL` | Асинхронный конвейер сбора новостей: параллельный сбор фидов, дедупликация в Redis |
| **[tg-ads-parser](https://github.com/von1336/tg-ads-parser)** | `Python` `aiogram 3` `GPT-5` `SQLite WAL` | Бот-охотник за заказами с 10+ бирж с ИИ-генерацией откликов через GPT-5 по кнопке |
| **[interactive-web-showcase](https://github.com/von1336/interactive-web-showcase)** | `Canvas 2D/3D` `Web Audio` `Vanilla JS` | Сюита из 5 веб-миров: 3D частицы, турбийон 4Hz, орбиты Кеплера и процедурное аудио |
| **[hermes-installer](https://github.com/von1336/hermes-installer)** | `C#` `.NET` `WPF` `GitHub API` | Десктопный Windows-лаунчер с автообновлением версий через GitHub Releases API |
| **[autogit_pro](https://github.com/von1336/autogit_pro)** | `Python` `CustomTkinter` `Git CLI` | GUI-комбайн для автоматизации GitHub: массовая загрузка папок, коммиты, управление ветками |
| **[von-procurement-platform](https://github.com/von1336/von-procurement-platform)** | `Django 5` `Celery` `Redis` `Docker` | B2B платформа корпоративных закупок: тендеры, импорт прайсов и аудит документов |
| **[cbr-currency-tracker-bot](https://github.com/von1336/cbr-currency-tracker-bot)** | `Python` `aiogram 3` `XML API` `SQLite` | Мониторинг курсов ЦБ РФ с алертами при резких скачках волатильности и дайджестами |
| **[hh-vacancy-parser](https://github.com/von1336/hh-vacancy-parser)** | `Python` `HH.ru API` `PostgreSQL` `Asyncio` | Парсер вакансий hh.ru с нормализацией мультивалютных вилок и идемпотентным upsert в БД |
| **[telegram-task-manager-bot](https://github.com/von1336/telegram-task-manager-bot)** | `python-telegram-bot` `JobQueue` `SQLAlchemy` | Персональный таск-менеджер в Telegram с напоминаниями точно в срок через JobQueue |
| **[fastapi-shop-catalog-api](https://github.com/von1336/fastapi-shop-catalog-api)** | `FastAPI` `SQLAlchemy 2.0` `Pydantic v2` | Асинхронный каталог товаров с фасетной фильтрацией, пагинацией и OpenAPI 3.1 |
| **[django-blog-rest-api](https://github.com/von1336/django-blog-rest-api)** | `Django 5` `DRF` `PostgreSQL` `Token Auth` | REST API для медиа: древовидные комментарии, драфты, объектные права доступа |
| **[react-dashboard](https://github.com/von1336/react-dashboard)** | `React 18` `Vite` `Recharts` `Tailwind` | Аналитический дашборд с интерактивными графиками финансовых показателей и темной темой |
| **[web-scraper](https://github.com/von1336/web-scraper)** | `BeautifulSoup4` `Pandas` `OpenPyXL` | Модульный скрапер с обходом пагинации, ретраями и экспортом в CSV/Excel |
| **[vk-to-yadisk-backup](https://github.com/von1336/vk-to-yadisk-backup)** | `Python` `VK API` `Yandex.Disk REST` | Облачный бэкап медиа из VK в Яндекс.Диск с сохранением максимального качества |
| **[ecommerce-api](https://github.com/von1336/ecommerce-api)** | `Node.js` `Express` `SQLite` `JWT` | Легковесный e-commerce микросервис: авторизация по токенам, каталог, корзина |
| **[contact-manager-cli](https://github.com/von1336/contact-manager-cli)** | `Python` `PostgreSQL` `Psycopg2` | CLI адресной книги с защитой от SQLi (параметризованные запросы) и экспортом |
| **[flask-notes-jwt-api](https://github.com/von1336/flask-notes-jwt-api)** | `Flask` `JWT` `Flask-Limiter` `SQLite` | Защищенный API заметок с тегами, поиском и ограничением нагрузки (Rate Limiting) |
| **[flask-url-shortener](https://github.com/von1336/flask-url-shortener)** | `Flask` `Base62` `SSRF Defense` | Сервис коротких ссылок с Base62-кодированием, защитой от SSRF и счетчиками кликов |
| **[portfolio-site](https://github.com/von1336/portfolio-site)** | `Vanilla JS` `CSS3` `HTML5` | Адаптивный сайт-портфолио в темной теме с терминальной hero-секцией |

---

## 🛠️ Стек технологий

**Backend & Storage:**  
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=celery&logoColor=white)

**Frontend & Visuals:**  
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5 Canvas](https://img.shields.io/badge/-HTML5%20Canvas-E34F26?style=flat-square&logo=html5&logoColor=white)
![Web Audio](https://img.shields.io/badge/-Web%20Audio%20API-9333EA?style=flat-square)
![Tailwind](https://img.shields.io/badge/-TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Systems & Automation:**  
![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![.NET / WPF](https://img.shields.io/badge/-.NET%20%2F%20WPF-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Telegram Bots](https://img.shields.io/badge/-Telegram%20Bots-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📊 Статистика активности

<p align="center">
  <a href="https://github.com/von1336?tab=repositories">
    <img src="assets/github-stats.svg" alt="Статистика репозиториев von1336" width="410" />
  </a>
  <a href="https://github.com/von1336?tab=repositories">
    <img src="assets/top-languages.svg" alt="Распределение языков программирования von1336" width="410" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/von1336">
    <img src="https://streak-stats.demolab.com/?user=von1336&theme=tokyonight&hide_border=true" alt="Активность GitHub Streak" width="830" />
  </a>
</p>

---

## 📬 Контакты

- **Telegram:** [@simulcra](https://t.me/simulcra)
- **GitHub:** [@von1336](https://github.com/von1336)
- **Live Showcase:** [von1336.github.io/interactive-web-showcase](https://von1336.github.io/interactive-web-showcase/)
