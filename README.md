# Teste Laravel

Projeto criado para um processo seletivo de estágio.

### Configurações:
- Servidor utilizado: Wamp64
- Para rodar, descompactar o arquivo em qualquer diretório apropriado de algum servidor PHP
- No caso do WAMP, coloquei o projeto na pasta `www`.
- Para rodar em ambiente de desenvolvimento, basta colocar o cmd no diretório `wamp64/www` e rodar `php artisan serve`

### Rotas:
- Login: http://localhost:8000/login
- Lista de Escolas: http://localhost:8000/teste - A partir desta rota, consegue-se acessar as demais funcionalidades de CRUD e navegar pela aplicação.
- Feito com o auxílio de alguns tutoriais e documentação.
- Banco de dados utilizado - MySQL no phpMyAdmin.

Algumas considerações:
enfrentei alguns problemas com as migrations. Elas produziam algumas tabelas, outras não. Em virtude disso, acabei tendo que criar algumas tabelas a partir do phpMyAdmin.

A funcionalidade de login ficou com alguns problemas, apesar do código relacionado fazer sentido.

 

