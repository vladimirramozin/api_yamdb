# api_yamdb
api_yamdb

## Как запустить:

Клонировать репозиторий:

```
git clone git@github.com:vovamkr/api_yamdb.git

```

Перейти в него в командной строке:

```
cd api_yamdb
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
source env/bin/activate
```

Установить pip и далее зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

Перейти в папку проекта:

```
cd api_yamdb
```

Выполнить миграции:

```
python3 manage.py migrate
```

Завести тестового суперпользователя admin с паролем admin:

```
python3 manage.py createsuperuser
> admin
>                 (на запрос email)
> admin
> admin           (повтор пароля)
> y               (ответ на вопрос что пароль слишком простой) 
```

Запустить проект:

```
python3 manage.py runserver
```
