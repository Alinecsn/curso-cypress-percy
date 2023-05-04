# curso-cypress-percy

Repositório do curso básico de testes de regressão visual com Cypress e Percy da [Escola Talking About Testing](https://talkingabouttesting.coursify.me).

## Pré-requisitos

Para instalar as dependências do projeto e executar os testes automatizados, é necessário que o [Node.js](https://nodejs.org/en) e [NPM](https://www.npmjs.com/) estejam instalados em seu computador.

> As seguints versões de ambos os sistemas foram utilizados durante o desenvolvimento deste projeto (`Node.js v18.12.1`e `npm 8.19.2`).

> Ao instalar o Node.js, o NPM é automaticamente instalado.

## Instalação

Após clonar o projeto, acesse o diretório do mesmo e execute `npm install` para instalar as depedências de desenvolvimento

## Exportando o token do projeto criado no Percy.io

Exporte como uma variável de ambiente o token do seu projeto (disponível no _dashboard_ do Percy). Veja os exemplos abaixo para sistemas Windows e unix (Mac e Linux).

```
# Windows
$ set PERCY_TOKEN=<your token here>

# Unix 
$ export PERCY_TOKEN=<your token here>
```

>Fonte: https://docs.percy.io/docs/cypress.

## Executando os testes

Execute o comando `npm test` para executar os testes em modo _headless_.
___

Um curso da [Escola Talking About Testing](https://www.udemy.com/user/walmyr).
