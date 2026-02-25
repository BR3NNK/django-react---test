# django-react---test
Django + React app for testing...

Sequência (ATENÇÃO):
1. Clone do repositório.
   comando: git clone https://github.com/BR3NNK/django-react---test.git
   
3. Abra o projeto na pasta djangoproject.
   comando: cd django-react---test/djangoproject
   
4. Instale os requirements.txt:
   comando: pip install -r requirements.txt

5. Volte e entre na pasta reactapp.
   comandos: cd..
             cd django-react---test/reactapp
   
6. Instale os requisitos do react.
   comando: npm install

Para fazer o projeto rodar normalmente, você precisará iniciar uma build no react, logo deve usar o comando: npm run build 
Isso demorará algum tempo, mas ao fim disso você poderá, então, voltar para a pasta do djangoproject (cd django-react---test/djangoproject)
e realizar o comando para iniciar seu projeto django: python manage.py runserver

Feito isso, você verá um template padrão react rodando em um único local django, sem precisar, necessariamente, de dois terminais (apesar de ser necessário mais para frente, em futuras mudanças).

Esse programa é apenas um teste para a junção dos dois frameworks, sem terem sido realizados testes com web services e uma comunicação mais ampla entre ambos (backend <-> frontend).
