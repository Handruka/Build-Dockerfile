Вот простой и понятный `README.md` для твоего репозитория [`Build-Dockerfile`](https://github.com/Handruka/Build-Dockerfile):

---

```markdown
# Build Dockerfile

Учебный проект по созданию и сборке Docker-образа для Go-приложения.

## 📌 Описание

Проект демонстрирует процесс контейнеризации Go-приложения с использованием `Docker`. Внутри находится простой HTTP-сервер, который разворачивается внутри контейнера.

## 📁 Содержимое

```
.
├── Dockerfile      # Инструкция для сборки Docker-образа
├── go.mod          # Go-модуль
└── main.go         # Простой HTTP-сервер
```

## 🐳 Сборка и запуск

1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/Handruka/Build-Dockerfile.git
   cd Build-Dockerfile
   ```

2. Соберите Docker-образ:
   ```bash
   docker build -t go-server .
   ```

3. Запустите контейнер:
   ```bash
   docker run -p 8080:8080 go-server
   ```

4. Перейдите в браузере по адресу:
   ```
   http://localhost:8080
   ```

## 🧪 Проверка

В ответ сервер должен вернуть:
```
Hello, Docker!
```

## 📌 Автор

[Rukavishnikov Dmitry (Handruka)](https://github.com/Handruka)
```

---

Если хочешь, я могу помочь тебе улучшить `Dockerfile` (например, сделать multi-stage build) или добавить CI-конфигурацию.
