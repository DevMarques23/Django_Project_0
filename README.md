# Django_Project_0

Este é um projeto de exploração da linguagem Django!

Deixo abaixo o passo para inicialização desse prjeto, no qual todos os passos,
foram extraidos do canal Pythonando no Youtube!

1- Crie um novo projeto.

2 - Instale o django pelo "Terminal" com o comando: pip install django

3 - Crie o conjunto do projeto Django com o comando: django-admin startproject nome_projeto

4 - Após criar a estrutura do projeto sercriada, ajuste no settings.py as informações abaixo:
LANGUAGE_CODE = 'pt-br'
TIME_ZONE = 'America/Sao_Paulo'

5 - Agora podemos startar um SERVER para acesso web, clique no menu
"Terminal" no Pycharm, acesse o local onde está o manage.py e digite: 
python manage.py sunserver

6 - Com o Link disponibilizado, acesse-o no navegador

7 - Acesse o terminal novamente e pare o serviço com ctrl + c

8 - Vamos startar um app Djando, acesse o terminal e digite: python manage.py startapp no_do_produto_que_quiser

OBS: Estrutura de requisições e retornos do server web é:
CLIENT -> envia request -> SERVER  
CLIENT <- recebe response <- SERVER

9 -  Sempre que criar um novo app, deverá acessar o settings.py e na linha INSTALLED_APPS, adicionar no final o nome do novo aap criado no passo acima.
