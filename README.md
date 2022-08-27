>>> O que é REACT?

* Uma biblioteca/framework para criação de interfaces;
* Utilizado para cocnstruir SPAs (Single Page Application) - Um arquivo index;
* Baseado em componentes;
* Utiliza o JSX para renderizar HTML;
* Aplica o VIRTUAL DOM para realizar as alterações de DOM;
* Pode-se ADICIONAR A UM PROJETO ou CRIAR UM PROJETO com ele.

>>> Como instalar o REACT?

* Para instalar o REACT vamos utilizar uma ferramenta chamada CREATE REACT APP;
* Recebemos todos os arquivos da biblioteca e TEMOS COMO EXECUTÁ-LA;
* Para utilizar precisamos do NODE e também NPM;
* Esta ferramenta também otimiza o app gerado papra PRODUÇÃO;
* É possível iniciar a aplicação com NPM START.

>>> Alguns comandos:

npx create-react-app my-app

npm START
Starts the development server;
Inicia o servidor de desenvolvimento;

npm run build
Bundles the app into static files for production;
Agrupa o app em arquivos estáticos para produção;

npm test
Starts the test runner;
Inicia a execução de testes;

npm run eject
Removes this tool and copies build dependencies, configuration files
and scripts into the app directory. If you do this, you can't go back!

>>> Entendendo o JSX

* O JSX é como um HTML, porém dentro do código JavaScript;
* É a principal maneira de escrever HTML com o React;
* Podemos INTERPOLAR VARIÁVEIS, inserindo ela entre {};
* É possível também EXECUTAR FUNÇÕES em JSX;
* Inserir VALORES EM ATRIBUTOS DE TAGS também é válido em JSX.

>>> Componentes

* Permite DIVIDIR A APLICAÇÃO em partes;
* Os componentes RENDERIZAM JSX, assim como App.js (que é um componente);
* Precisamos CRIAR UM ARQUIVO de componente;
* E IMPORTÁ-LO onde precisamos utilizar;
* Normalmente ficam em uma pasta chamada COMPONENTS.