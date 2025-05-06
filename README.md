# Docker Lab

Проект `docker-lab` — это учебная среда для практики работы с Docker и Docker Compose. Сборка разворачивает несколько сервисов (MySQL, phpMyAdmin, Nginx) и демонстрирует их взаимодействие в одной сети.

## 📦 Сервисы

- **MySQL** — база данных.
- **phpMyAdmin** — веб-интерфейс для работы с MySQL.
- **Nginx** — обратный прокси для маршрутизации запросов к phpMyAdmin.

## 🚀 Быстрый старт

> Требования: установленный `docker` и `docker-compose`.

```bash
git clone https://github.com/yourname/docker-lab.git
cd docker-lab
docker-compose up -d
