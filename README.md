# API "Yatube"
## Описание проекта
API для социальной сети блогеров Yatube.


## Возможности API
- Авторизованным пользователям доступно:
  - создавать, редактировать и удалять записи в социальной сети Yatube
  - просматривать и комментировать записи других авторов
  - подписываться на других авторов
- Анонимным пользователям доступно:
  - чтение чужих записей и комментариев

## Технологии
- Python 3.7
- Django 2.2.16
- Django REST Framework 3.12.4
- JWT + Djoser



### Запуск приложения
- Установите и активируйте виртуальное окружение
```
python -m venv venv
```
- Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
```
- Выполните миграции:
```
python manage.py migrate
```
- Запустите проект:
```
python manage.py runserver
```

### Спецификация API будет доступна после запуска проекта по адресу
```
http://localhost:8000/redoc/
```

#### Автор
Антон Молчанов
