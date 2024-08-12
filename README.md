Note-Taking App

Описание
Это веб-приложение для создания и управления заметками, разработанное с использованием Node.js, Express, MongoDB для серверной части и React для клиентской части. Приложение поддерживает регистрацию и аутентификацию пользователей с использованием JWT.

Функциональные возможности

- Регистрация пользователей
- Вход и выход пользователей
- Создание, чтение, обновление и удаление заметок
- Безопасное хранение паролей с использованием bcrypt
- Аутентификация с помощью JWT

Установка

Серверная часть

1. Клонирование репозитория:

   git clone https://github.com/yourusername/note-taking-app.git
   cd note-taking-app

2. Установка зависимостей:

   cd server
   npm install

3. Настройка переменных окружения:

   Создайте файл `.env` в директории `server` и добавьте следующие переменные:

   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   PORT=5000

4. Запуск сервера:

   npm start
   

Клиентская часть

1. Установка зависимостей:

   cd client
   npm install

2. Запуск клиента:

   npm start

Использование

После запуска клиентская часть будет доступна по адресу `http://localhost:3000`, а серверная часть будет работать на `http://localhost:5000`.

Регистрация и вход

- Перейдите на страницу регистрации для создания нового аккаунта.
- После регистрации войдите в систему для управления вашими заметками.

 Управление заметками

- Добавляйте новые заметки через интерфейс приложения.
- Редактируйте или удаляйте существующие заметки.

 Развертывание

Проект можно развернуть на платформах Vercel (для фронтенда) и Heroku (для бэкенда).

 Автор

- Эльсид Саргсян (https://github.com/elsid1997)

 Лицензия

Этот проект лицензирован под MIT License.
