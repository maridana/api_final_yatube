# API для YaTube
Социальная сеть Yatube - это блог для публикации личных записей. По желанию посты можно опубликовать в группах, подписываться на других авторов и оставлять комментарии к записям. 
### Запуск в dev-режиме
Клонировать репозиторий и перейти в него в командной строке:
```
git clone 
```
```
cd api_final_yatube
```
Установить виртуальное окружение, затем активировать его:
```
python -m venv venv
```
```
source venv/scripts/activate
```
Установить зависимости из файла requirements.txt:
```
python -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
Выполнить миграции:
```
python manage.py migrate
```
Запустить проект:
```
python manage.py runserver

