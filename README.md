# Необходимый стек технологий: Ngnix, Docker/Docker Compose, Markdown, PHP - Laravel, Postgres

Описание и схема архитектуры сервиса
![Architecture](architecture.png)

---
# Задание - создать RESTful API сервис
- Создать конфигурационный файл `docker-compose.yml` для запуска данного сервиса.
- Создать документацию в формате **Markdown** в файле `README.md`, которая описывает процесс настройки и запуска данного сервиса, а также описание и примеры работы API.
- Создать RESTful API для одной сущности - **Пост**, который обладает следующими атрибутами: ID, Заголовок, Дата публикации, Текст.

Пример структуры поста в формате JSON
```
{
  "id": 1,
  "title": "Hello World",
  "updated_at": "2020-10-15T07:20:42.000000Z",
  "content": "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
}
```
Реализовать следующие RESTful API операции для поста:
|  Название                    |HTTP Метод|  Маршрут (URL)      | 
|------------------------------|----------|---------------------|
| Получение списка постов      | `GET`    | `/api/posts`        |
| Получение конкретного поста  | `GET`    | `/api/posts/{post}` |
| Создание поста               | `POST`   | `/api/posts`        |
| Изменение поста              | `PUT`    | `/api/posts/{post}` |
| Удаление поста               | `DELETE` | `/api/posts/{post}` |

Готовое задание разместить публичным репозиторием на Github и прислать ссылку на этот репозиторий (очень просим проверить доступность и корректность ссылки на репозиторий)

При выполнении данного задания будет большим плюсом, если вы примените лучшие практики, чтобы выполненнное задание было не только рабочим, но и качественным. Проявите профессионализм, чтобы показать уровень вашей компетенции. 
