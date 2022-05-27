# Desafio: Trabalhando com middlewares Node.js

Este projeto serve como um backend para funcionar como API público para demonstrar a utilização da API do Trabalhando com middlewares Node.js. A ideia da aplicação é que os usuários possam adicionar tarefas a sua conta, possuindo plano pro ou free e dependendo do plano as tarefas serão limitadas a conta do usuário nessas tarefas também é permitido a adição de data, horário e até se foi concluida ou não,
Para a utilização da API é necessário estar autenticado com o username cadastrado.

## Rodando servidor

O primeiro passo para executar o servidor é verificar se você possui o NodeJS instalado na sua máquina, caso contrário, baixe <a href="https://nodejs.org/en/download/">aqui</a>

Após a instalação, <a href="https://github.com/barretot/conceitos-do-nodejs-1.git">clone</a> este projeto em um local de sua preferência e com seu gerenciador de pacotes instale as dependências do projeto.

### Instalando dependências:

#### Yarn

```
$ yarn
```

#### NPM

```
$ npm install
```

### Iniciando servidor

Se você seguiu todos os passos acima, pode executar o servidor com os seguintes comandos:

#### Yarn

```
$ yarn dev
```

#### NPM

```
$ npm run start
```

### Para usar todas as rotas da aplicação clique nesse botão e importe o WorkSpace do Conceitos Node.js no Insomnia.

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=Conceitos%20Node.js&uri=https%3A%2F%2Fgist.githubusercontent.com%2Fbarretot%2Fef572cdd37bab6a86937d735b7b7f1d4%2Fraw%2Ffe3a4055a825056a1d9eedd05fd31a5adc1bd6c5%2Fgistfile1.txt)

Se você não possui o Insomnia, baixe <a href="https://insomnia.rest/download">aqui</a>

Se você não sabe como importar, clique <a href="https://support.insomnia.rest/article/172-importing-and-exporting-data">aqui</a>

## Project information

#### Dependencies

- <a href="https://www.npmjs.com/package/cors">cors</a>
- <a href="https://www.npmjs.com/package/express">express</a>
- <a href="https://www.npmjs.com/package/uuid">uuid</a>

#### Dev Dependencies

- <a href="https://www.npmjs.com/package/jest">jest</a>
- <a href="https://www.npmjs.com/package/nodemon">nodemon</a>
- <a href="https://www.npmjs.com/package/supertest">supertest</a>
