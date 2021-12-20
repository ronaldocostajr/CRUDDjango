### Iniciando um projeto em Django

Criar uma pasta para o projeto no explorer.

Criar o ambiente virtual. vitualenv venv

Ativar o ambiente virtual. venv/Scripts/activate

Instalar o Django. pip install django

Criar o projeto no django. django-admin startproject nomeProjeto .

Criar o arquivo de dependências. pip freeze > requirements.txt -> sempre atualizar.

Para instalar todos os pacotes do requirements.txt -> pip install -r requirements.txt

Testar se a aplicação está funcionando. python manage.py runserver

Testar -> 127.0.0.1:8000

Criar um repositório no GITHUB.

Iniciar o repositório local conforme comandos do GITHUB<br/>
git init<br/>
git add README.md<br/>
git commit -m "first commit"<br/>
git branch -M main<br/>
git remote add origin git@github.com:ronaldocostajr/CRUDDjango.git<br/>
git push -u origin main<br/>

Criar o gitignore, pode instalar o plugin gitignore template.

F1, escolher Generate.gitignore.

Escolher a linguagem = python. Pronto, está gerado.

Enviar para o repositório.



