## Considerando que:
<pre><code> if (instalacao == ok and so == linux)
	print(“pode copiar aqui de boas”)
elif
    https://tutorial.djangogirls.org/pt/python_installation/ 
</code></pre>
## Criar o projeto
```
$ python3 -m venv myvenv
$ . myvenv/bin/activate
$ pip install django==1.8.5 whitenoise==2.0
$ django-admin startproject mysiteprogramacaoredes
```
## Configurando o projeto
#### Em settings.py :
<pre><code> 
    TIME_ZONE = 'America/Sao_Paulo'<br>
    STATIC_URL = '/static/'<br>
    STATIC_ROOT = os.path.join(BASE_DIR, 'static'<br>
</code></pre>

## Criando uma aplicação 
$ python manage.py startapp blog
* Em settings.py :
<pre><code> 
`INSTALLED_APPS = (
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'blog',
)`
</code></pre>

## Criando um model e colocando no banco de dados
#### Criar model em 'blog/models.py'
#### No terminal rodar as migrations
```
$ python manage.py makemigrations blog
$ python manage.py migrate blog
```

## Configurando admin
#### Abrir arquivo 'blog/admin.py' e configurar o novo model
#### No terminal criar superuser
```
$ python manage.py createsuperuser
```

## Configurando as urls
#### Incluir as urls do blog nas urls do site

## Configurar as views
#### Organizar chamadas das urls

## Primeiros templates (html)
#### Criar a pasta blog/templates/blog para ficar mais organizado

## Formulários
#### Criar 'blog/forms.py'

## Rodar a aplicação:
```
$ python manage.py runserver
```

## Tutorial base:
https://tutorial.djangogirls.org/pt/django/ 