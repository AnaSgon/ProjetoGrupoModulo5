# ProjetoGrupoModulo5

## Tecnologias atreladas

1. NODE Js
2. XAMPP
3. WORK BENCH
4. VSCode

Instalações:

```
npm init -y
npm install nodemon
npm install express
npm install sequelize
npm install express-handlebars
npm install express-session
npm install express-flash
npm install cookie-parser
npm install cookie-session
npm install session-file-store
npm install bcryptjs
npm install connect-flash
npm install mysql2 
```


## Dependências

 1. npm init -y
 2. Express
 3. Sequelize
 4. Express-Handlebars
 5. express-session
 6. express-Flash
 7. cookie-parser
 8. cookie-session
 9. session-File-Store
 10. bcryptjs;
 11. connect-flash
 12. mysql2 
 
## Passo a Passo de como iniciar o MARKET LIST

1. É necessário realizar o download dos programas: XAMPP, WORK BENCH, VS CODE, NODE JS.

2. Após as instalações, inicie o programa XAMPP, start MYSQL, anotar a porta e abrir o terminal SHELL.

3. Abrir o programa Work Bench, criar um MySQL connections clicando no símbolo de +, coloque o nome "bancodedados", utilize a porta que anotou do XAMPP, depois "ok".
Quando estiver na tela do work bench, crie o banco com o comando "CREATE DATABASE bancodedados;" e clique no raio ou CTRL+ENTER, na linha abaixo utilize o comando "USE bancodedados;" e mais uma vez clica no raio, pronto o banco de dados está criado e você já está utilizando!

4. No VSCode abrir a pasta do projeto: file > open folder... > marketlist.TOP

5. No terminal do VSCode é necessário realizar as instalações dos pacotes de extenções, comando:

5.1 - npm init - y  > ENTER - aguarde instalar o package json.

5.2 - npm install bcryptjs connect-flash express express-flash express-session express-handlebars mysql2 sequelize nodemon cookie-parser cookie-session session-file-store  - aguarde realizar todas as instalações pode demorar um pouco.

Solução 1: Caso dê algum erro de instalação, saia do terminal clicando em CTRL+C > depois escreva o comando: exit, abra o terminal de novo, trate o erro antes de instalar as dependencias digite "npm set strict-ssl false" depois clique em ENTER, depois prossiga com a instalação das dependências de uma vez.

Solução 2: Se persistir o erro, saia do terminal clicando em CTRL+C > depois escreva o comando: exit, abra o terminal de novo, e  instale um de cada vez, sempre iniciando com "npm install + nome da dependencia.

5.3 - npm start

5.4 - Abra o seu navegador e digite: localhost:3000 e clique em ENTER. 

Pronto esta é o site do projeto, utilize as funcionalidades.. faça login.. faça sua lista de compras!!!



Equipe:
Ana Caroline
Jenifer Arruda
Raysa Reis
Turno: Tarde
Unidade: Senac Bonsucesso
