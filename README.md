# sisgee

Instruções de instalação:

1.Instale as dependências utilizando o comando:
```
pip install requirements.txt
```
2.Crie um banco de dados no postgres com o nome sisgee e ajuste o login e senha no settings.py do projeto.
3.Execute os scritps de migração utilizando o comando:
```
python manage.py migrate
```
4.Execute o servidor do django utilizando o comando:
```
python manage.py runserver
```
5.Acesse a aplicação no browser no endereço http://localhost:8000/estagio/

