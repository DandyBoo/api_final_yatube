# api_final_yatube

## Api для социальной сети yatube

### Технологии:
![Python](https://img.shields.io/badge/-Python-8fcfd1?style=flat&logo=Python)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/Django-REST-ff1709?style=flat&logo=django&logoColor=white&color=ff1709&labelColor=gray)


- Python 3.7.0 
- Django 2.2.16
- Django REST framework 3.12.4

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
Обратиться к проекту:
http://127.0.0.1:8000
Документация по API:
http://127.0.0.1:8000/redoc