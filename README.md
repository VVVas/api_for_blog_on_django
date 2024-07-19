# API для Блога  
Позволяет пользователям регистрироваться, создавать и редактировать публикации, оставлять к ним комментарии, подписываться на других авторов.  

## Стек технологий  
Python, Django, Django REST framework, djoser, Simple JWT, Pillow, SQLite  

## Как развернуть API для Блога  

Создать окружение  
```  
python -m venv venv  
```  

Активировать окружение, обновить pip и установить зависимости  
```  
source venv/Scripts/activate  
python -m pip install --upgrade pip  
pip install -r requirements.txt  
```  

Применить миграции и запустить сервер  
```  
python yatube_api/manage.py migrate  
python yatube_api/manage.py runserver  
```  

По окончании использования деактивировать окружение  
```  
deactivate  
```  

[Мишустин Василий](https://github.com/vvvas), v@vvvas.ru  
