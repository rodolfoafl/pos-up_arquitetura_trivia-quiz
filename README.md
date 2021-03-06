# Trivia Quiz

- Um aplicativo de linha de comando, utilizando Node.js. É um Quiz simples, onde o jogador poderá escolher uma categoria, responder as perguntas
  e ver sua pontuação final.
- Utilizando-se da API do [Open Trivia Database](https://opentdb.com), foram selecionadas 3 categorias como as disponíveis para o jogador: "Movies", "Video Games" e "Computers".
- Após selecionada a categoria, o jogador deverá responder 5 questões aleatórias (de dificuldade fácil, segundo os parâmetros da API).
- Ao término, o jogador poderá ver sua pontuação final e jogar ou não novamente;
- Todos os menus, perguntas e respostas estão em inglês.

## Requisitos

- [Node.js](https://nodejs.org/en/): v14.17.0

## Desenvolvendo

- Clone o projeto para seu ambiente local.
- Execute `npm install` ou `yarn install` para instalar as dependencias.
- Execute `npm start` para iniciar a aplicação.

## Documentação

- [Node.js](https://nodejs.org/en/)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Open Trivia DB](https://opentdb.com/api_config.php): API fornecedora das categorias, perguntas e respostas.
- [Axios](https://axios-http.com/docs/intro): Utilizado para requisições HTTP.
- [Inquirer](https://www.npmjs.com/package/inquirer#documentation): Pacote de interface interativa para utilização com linhas de comando.
- [html-entities](https://www.npmjs.com/package/html-entities): Utilizado para decodificar entidades HTML.
