# Задание: Логика добавления и обновления жанра для списка книг

## 1. Маршруты

Реализуйте следующие маршруты:

- `POST /api/genres` —добавляет новый жанр;
- `PUT /api/genres/:id` — обновляет жанр по `id` и возвращает обновленный жанр или ошибку 404, если жанр не найден.

Для каждого маршрута добавьте валидацию тела запросу через Yup.


