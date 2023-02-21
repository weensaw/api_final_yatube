**YATUBE_API**

Этот проект был создан для пользователей, которые хотят делиться с миром своими записями.

##Установка
Клонировать этот репозиторий себе на устройство можно несколькоми способами:
- Можно использовать HTTPS, SSH или GitHub CLI.
- Можно скачать архивом.
- git clone git@github.com:wensaw/api_final_yatube.git
```

```
cd yatube_api
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

##Вот несколько примеров запросов к API:

- Запрос к API Yatube
```
Например по адресу http://127.0.0.1:8000/redoc/ будет доступна документация для API Yatube.
```
Данные об id пользователя можно получить по этому адресу http://127.0.0.1:8000/api/users/me/
```
