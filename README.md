# Описание:
Данное API создано для проекта Yatube, социальная сеть для блогеров.
Сам проект можно посмотреть [здесь](https://github.com/8Vadim8/hw05_final)

## Технологии:
- Python
- Django
- DRF
- JWT
- Djoser

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке


Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
source venv/Scripts/activate
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```
Cоздать файл .env и прописать SECRET_KEY
```
echo "SECRET_KEY=YourSecretKey" > .env
```
Секретный ключ Джанго можно сгенерировать [здесь](https://djecrety.ir)

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
После запуска проекта документация по API будет доступна по адресу  http://127.0.0.1:8000/redoc/
