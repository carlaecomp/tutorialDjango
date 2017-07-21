# Entrar no ambiente env:
$ . myvenv/bin/activate
# Criar as tabelas:
$ python manage.py makemigrations blog
$ python manage.py migrate blog
# Rodar a aplicação:
$ python manage.py runserver

# Tutorial base:
https://tutorial.djangogirls.org/pt/django/ 