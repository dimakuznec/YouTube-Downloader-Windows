# VideoVault - Сервис для скачивания видео с YouTube

## О проекте
**VideoVault** — это веб-приложение, которое позволяет скачивать видео с YouTube, используя URL-адрес. Сервис поддерживает выбор качества видео и аудио, отображает прогресс скачивания и автоматически сохраняет файлы в папку "Загрузки" на компьютере пользователя.

## Основные возможности
- 🔹 Вставка ссылки на видео с YouTube
- 🔹 Выбор качества видео (720p, 1080p, 4K и другие)
- 🔹 Скачивание видео в формате MP4 и WEBM
- 🔹 Поддержка скачивания аудио в MP3
- 🔹 Отображение прогресса скачивания
- 🔹 Уведомления о завершении загрузки

## Используемые технологии
### Frontend:
- React + TypeScript
- Material-UI
- Чистый CSS

### Backend:
- Python + FastAPI
- yt-dlp (альтернатива youtube-dl)
- **zapret-discord-youtube** ([GitHub](https://github.com/Flowseal/zapret-discord-youtube)) — библиотека, позволяющая обходить блокировки YouTube.

## Установка и запуск проекта

### 1. Клонирование репозитория
```sh
git clone https://github.com/dimakuznec/video-downloader.git
cd VideoVault
```

### 2. Установка зависимостей
#### Frontend:
```sh
cd frontend
npm install
```

#### Backend:
```sh
cd backend
pip install -r requirements.txt
```

### 3. Запуск проекта
#### Запуск Frontend
```sh
 npm start
```

#### Запуск Backend
```sh
python -m uvicorn main:app --reload
```

## Использование библиотеки zapret-discord-youtube
Библиотека **zapret-discord-youtube** позволяет загружать видео с YouTube, обходя ограничения и блокировки. В нашем проекте она используется для обработки запросов на скачивание.

### Установка
```sh
pip install git+https://github.com/dimakuznec/video-downloader.git
```
