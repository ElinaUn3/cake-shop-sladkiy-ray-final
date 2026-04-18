# Сладкий рай — Кондитерская

Веб-приложение тортиков кондитерской «Сладкий рай».

## Стек

- **Backend:** Python 3.9, Django 4.2
- **БД:** PostgreSQL
- **Frontend:** HTML/CSS (Times New Roman, цвета: `#FC34C8`, `#31EBFF`)

## Роли

| Роль | Возможности |
|------|------------|
| Гость | Просмотр каталога |
| Клиент | Каталог с фильтрами/поиском + свои заказы |
| Менеджер | Все заказы, смена статусов |
| Администратор | Полный CRUD товаров, заказов, пользователей |

## Запуск

```bash
python -m venv venv         
source venv/Scripts/activate         
python -m pip install --upgrade pip   
 
pip install Django==5.2  
 
 
pip freeze > requirements.txt                        
pip install -r requirements.txt   
 
 
django-admin startproject <имя проекта> 
python manage.py startapp <имя приложения>   
 
 
python manage.py runserver 
 
python manage.py migrate                                                 
python manage.py makemigrations   
 
python manage.py createsuperuser
```

Приложение будет доступно на `http://127.0.0.1:8000`

## Аккаунты

| Роль сотрудника          | ФИО                                 | Логин                          | Пароль     |
|--------------------------|-------------------------------------|--------------------------------|------------|
| Администратор            | Кондратьева Алиса Михайловна        | kondratieva@cake-shop.ru       | AdCk76#    |
| Администратор            | Волошин Игорь Сергеевич             | voloshin@cake-shop.ru          | XyZ$89p    |
| Администратор            | Сладкоежкина Виктория Павловна      | sladkoezhkina@cake-shop.ru     | T0rt!k45   |
| Менеджер                 | Кремов Артем Дмитриевич             | kremov@cake-shop.ru            | Mn7@gP23   |
| Менеджер                 | Бисквитов Петр Владимирович         | biskvitov@cake-shop.ru         | Rt5#fH67   |
| Менеджер                 | Ягодная Елена Игоревна              | yagodnaya@cake-shop.ru         | Ber3ry$1   |
| Авторизированный клиент  | Сахарова Анна Викторовна            | saharova.client@mail.ru        | Cli3nt#9   |
| Авторизированный клиент  | Вафельный Максим Олегович           | waffle.client@gmail.com        | WafFl3$5   |
| Авторизированный клиент  | Шоколадов Кирилл Александрович      | chocolate.client@yandex.ru     | Ch0c0L8*   |
| Авторизированный клиент  | Фруктовская Ольга Сергеевна         | fruit.client@outlook.com       | FrU1t%22   |
