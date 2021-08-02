# API for Yatube
## Description
Draft training course Yandex.Practicum
The project is designed to hone API programming skills on the example of a social network 
## Install
Clone the repository and go to it on the command line: 

```
git clone https://github.com/Eugust/api_final_yatube.git
```

```
cd kittygram
```

Create and activate a virtual environment: 

```
python3 -m venv env
```

```
source env/bin/activate
```

Install dependencies from file requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Run migrations:

```
python3 manage.py migrate
```

Run the project:

```
python3 manage.py runserver
```
## Examples of requests 
GET `http://127.0.0.1:8000/api/v1/posts/`
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
