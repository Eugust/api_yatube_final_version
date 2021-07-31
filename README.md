# api_final
## Описание
Проект учебного курса Яндекс.Практикум
Проект предназначен для оттачивания навыков программирования API на примере социальной сети
## Установка
Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Eugust/api_final_yatube.git
```

```
cd kittygram
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

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
## Примеры запросов
Запрос GET `http://127.0.0.1:8000/api/v1/posts/`
```
[
  {
    "id": 0,
    "author": "string",
    "text": "string",
    "pub_date": "2019-08-24T14:15:22Z",
    "image": "string",
    "group": 0
  }
]
```
