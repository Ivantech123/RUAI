<p align="center">
  <a href="https://github.com/Ivantech123/RUAI">
    <img src="client/public/assets/logo.svg" height="256">
  </a>
  <h1 align="center">RUAI</h1>
</p>

<p align="center">
  <strong>🤖 Русский AI чат-ассистент на базе LibreChat</strong>
</p>

## О проекте

RUAI - это русифицированная версия LibreChat, предоставляющая удобный интерфейс для общения с различными языковыми моделями. Проект адаптирован для русскоязычных пользователей и предлагает полностью переведенный интерфейс.

### Основные возможности

- 🌐 Полностью русский интерфейс
- 💬 Поддержка различных языковых моделей
- 📁 Работа с файлами и документами
- 🔍 Встроенный поиск по истории чатов
- 🛠️ Гибкая настройка и конфигурация
- 🔒 Система аутентификации пользователей

## Установка

### Через Docker (рекомендуется)

```bash
git clone https://github.com/Ivantech123/RUAI.git
cd RUAI
docker-compose up -d
```

### Через npm

```bash
git clone https://github.com/Ivantech123/RUAI.git
cd RUAI
npm install
npm run frontend
npm run backend
```

## Конфигурация

Основные настройки находятся в файле `.env`. Создайте его на основе `.env.example` и настройте необходимые параметры:

- API ключи для языковых моделей
- Настройки базы данных
- Параметры аутентификации

## Лицензия

Этот проект является форком LibreChat и распространяется под той же лицензией (MIT).

## Благодарности

- [LibreChat](https://github.com/danny-avila/LibreChat) - оригинальный проект
- Всем контрибьюторам LibreChat
