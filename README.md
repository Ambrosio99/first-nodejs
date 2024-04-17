# Minha primeira biblioteca em Node.js

Está é minha primeiro biblioteca em Node.js desenvolvida a partir do curso de Node.js disponível pela escola Alura.

Este projeto é uma aplicação simples para gerenciar links que se encontram dentro de um arquivo Markdown, de forma a facilitar o trabalho de testar se todos estão funcionais. Nesse programa, foram desenvolvidos dois métodos: um é utilizado apenas para retornar os links e o segundo, além de retornar os links, realiza a verificação se todos os links estão funcionais utilizando fetch e retorna seus códigos HTTP.

## Como funciona?

No projeto, Foi utilizado um texto em formato Markdown dentro da pasta 'arquivos' como exemplo. No arquivo 'package.json', na seção 'scripts', temos as seguintes linhas de comando desenvolvidas para serem utilizadas no terminal para funcionalidades do programa:

- O script 'cli' é utilizado para extrair apenas os links do texto.
- O script 'cli:valida' é utilizado para extrair os links e realizar a validação."

## Como usar

### Pré-requisitos

- Node.js e npm instalados ([Baixe aqui](https://nodejs.org/))
- Chalk instalado (`npm install chalk`)

### Rodando o Projeto

- O arquivo em formato Markdown que utilizei no projeto se encontra dentro da pasta "arquivos" e pode ser alterado para qualquer arquivo na mesma formatação para uso pessoal.
- Dentro de package.json está o script que é usado para rodar o programa pelo terminal. Caso altere o arquivo Markdown será necessário a alteração desse script para o funcionamento com seu arquivo pessoal.

Exemplo em caso de alteração do arquivo Markdown:

```bash
    "cli": "node ./src/cli.js ./arquivos/seuArquivo.md",
    "cli:valida": "node ./src/cli.js ./arquivos/seuArquivo.md --valida"
```

Para rodar o programa no terminal:

```bash
npm run cli:valida
npm run cli
```
