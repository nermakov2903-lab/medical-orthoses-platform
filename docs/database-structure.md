# Структура базы данных

## СУБД

PostgreSQL

## Таблицы

### users
Хранит информацию о пользователях.

### orthosis_categories
Хранит категории ортезов.

### orthoses
Хранит информацию об ортезах.

### applications
Хранит заявки пользователей.

### reviews
Хранит отзывы пользователей.

## Связи

orthosis_categories 1:N orthoses (Одна категория - много ортезов)

users 1:N applications (Один пользователь - много заявок)

orthoses 1:N applications (Один ортез - много заявок)

users 1:N reviews (Один пользователь - много отзывов)

orthoses 1:N reviews (Один ортез - много отзывов)
