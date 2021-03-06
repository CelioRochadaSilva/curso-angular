# App Filmes: Curso Intermediário de Angular: fornecido pelo Digital innovation 2021

# Tela principal
![Tela principal ](https://github.com/CelioRochadaSilva/curso-angular/blob/main/src/tela-principal.png)
Lista os filmes com opção de adicionar e remover filmes

# Tela cadastro filmes
![Tela principal ](https://github.com/CelioRochadaSilva/curso-angular/blob/main/src/tela-cadastro.png)
Disponibiliza formulario de cadastro para novos filmes

# Tela genero filmes
![Tela principal ](https://github.com/CelioRochadaSilva/curso-angular/blob/main/src/tela-principal-genero.png)
Disponibilizar os filmes conforme genero.

# Tela descrição
![Tela principal ](https://github.com/CelioRochadaSilva/curso-angular/blob/main/src/tela-descri%C3%A7%C3%A3o%20filme.png)
Dados importantes do filmes

# Algumas Ferramentas utilizadas.
1. Angular CLI;
2. Angular material;
3. Postmam;
4. Visual Studio Code; 

O curso consiste em um sistema de filmes, com a possibilidade de cadastros, edições, listagem e visualização dos filmes.

## Instalação : passos iniciais

1. clone o repositório `git clone git@github.com:RenanRB/curso-angular.git`
2. Entre no projeto e instale as dependencias `npm install`

## Ambiente Local

Execute `ng serve` para que o projeto suba localmente. Acesse a url `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código

## Simulando o Back-end

Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.

## Gerando componente

Execute `ng generate component nome-do-componente` para criar um novo componente. Você também pode usuar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.

