# API для Yatube
Чтоб было круто!

Создать окружение
```
python -m venv venv
```

Активировать окружение
```
source venv/Scripts/activate
```

Обновить pip
```
python -m pip install --upgrade pip
```

Установить зависимости
```
pip install -r requirements.txt
```

Запустить pytest
```
pytest
```

Применить миграции
```
python yatube_api/manage.py migrate
```

Запустить сервер
```
python yatube_api/manage.py runserver
```

Деактивировать окружение
```
deactivate
```
