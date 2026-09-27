# Pesquisa Futurama

Projeto de formulário HTML com estilos escritos em SCSS e compilados para CSS.

## Requisitos

- Node.js 20 ou superior e npm

## Instalar dependências

Na pasta do projeto, execute:

```bash
npm install
```

## Compilar o SCSS

Para compilar uma vez:

```bash
npm run build:css
```

Durante o desenvolvimento, deixe este comando rodando para recompilar o CSS sempre que salvar um arquivo SCSS:

```bash
npm run sass
```

O código-fonte fica em `scss/style.scss`. O Sass gera `css/style.css`, que é o arquivo carregado pelo navegador.

## Abrir a página

Abra `index.html` no navegador ou use a extensão Live Server do VS Code. Se estiver usando o Sass em modo de observação, mantenha o terminal aberto enquanto edita os estilos.