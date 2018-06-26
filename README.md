# node-2
Chat real-time with WebSockets

---> step-by-step

- mkdir 'x';
- npm init;
- npm install express --save
- npm install ejs --save
- npm install consign --save
- npm install body-parser --save
- npm install express-validator --save


---> Dependences necessary:

-> Express: framework para desenvolvimento de aplicações web;

-> EJS: engine de views - possibilida a escrita de javascript no html '<% "CÓDIGO EM JAVASCRIPT" %>';

-> Consign: autoloader (reinicia o server ao salvar alterações nos códigos);

-> Body-parser: middle que popula a variável body que contém os elementos de formulário transitados em requisições
express validator

-> Express-validator: módulo que valida as informações digitadas em formulários;

---> Criação de arquivos e diretórios:

-> Na raíz do diretório principal criar o diretório "config" -> arquivo -> "server.js"
-> Na raíz do diretório principal criarrquivo "app.js";
-> Na raíz do diretório principal criar o diretório "app" -> criar os diretórios com base no design patterns MVC -> diretorios: views, models, controllers, routers, public (diretório que irá conter os assets no lado do cliente -> images, css, js); 
