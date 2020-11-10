[![Build Status](https://travis-ci.com/ffabiorj/django_store.svg?branch=master)](https://travis-ci.com/ffabiorj/voluntario_app)

[![codecov](https://codecov.io/gh/ffabiorj/django_store/branch/master/graph/badge.svg)](https://codecov.io/gh/ffabiorj/voluntario_app)

# Api de um Ecommerce

## Ferramentas Utiliadas

- Django
- Postgres
- Heroku
- Django rest framework

## Roda o projeto localmente:

1. Clone o repositório.
2. Entre na pasta.
3. Crie um ambiente de desenvolvimento com python 3.8.
4. Ative o ambiente.
5. Instale as dependências.
6. Crie um arquivo .env
7. Rode as migrações
8. Rode o projeto
9. Acesse o link

```
- git clone git@github.com:ffabiorj/django_store.git
- cd django_store
- python3 -m venv .venv
- source .venv/bin/activate
- pip install -r requirements-dev.txt
- python contrib/env_gen.py
- python manage.py migrate
- python manage.py runserver
- http://127.0.0.1:8000/api/v1/
```

### Endpoints da api

- http://127.0.0.1:8000/api/v1/ # retorna todos os emprestimos do usuario
- http://127.0.0.1:8000/api/v1/ # retorna um emprestimo pelo id

### Exemplos de entrada para os endpoints

```
Dados para cadastrar empresa na api
{

}

```

### Rodar os testes

```

pytest

```

### Links para as ferramentas utilizadas

[Django](https://docs.djangoproject.com/)

[Postgres](https://www.postgresql.org/)

[Heroku](https://www.heroku.com/)

[Codecov](https://codecov.io/)

[Travis](https://travis-ci.com/)

[Django Rest Framework](https://www.django-rest-framework.org/)
