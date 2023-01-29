# Проект «API для Yatube»
### Описание проекта:
API для сайта Yatube.

### Доступный функционал 
- Посты 
- Группы 
- Комментарии
- Подписки

### Как запустить проект:

1. Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Dave-YP/api_final_yatube.git
```

```
cd api_final_yatube
```

2. Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

3. Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

4. Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
#### Пример запроса
Все примеры доступны в документации:
```
http://127.0.0.1:8000/redoc/
```
