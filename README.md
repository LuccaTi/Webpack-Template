# Webpack Template

Template base para projetos Front-End com Webpack.

O objetivo deste repositório é servir como ponto de partida reutilizável para novos projetos, com uma estrutura limpa, suporte a módulos JavaScript, processamento de CSS/HTML e layout responsivo no formato Holy Grail.

## Descrição

Este projeto usa Webpack como bundler em modo de desenvolvimento, com:

- Entrada JS modular em `src/index.js`.
- Injeção automática do bundle no HTML via HtmlWebpackPlugin.
- Suporte a importação de CSS, HTML e imagens.
- Servidor de desenvolvimento com hot reload.

## Tecnologias e Conceitos

- JavaScript modular (ES Modules)
- Webpack 5 + webpack-cli + webpack-dev-server
- html-webpack-plugin
- css-loader + style-loader
- html-loader
- Asset Modules do Webpack para imagens
- HTML5 semântico
- CSS Grid + Flexbox
- Layout responsivo (mobile first)

## Estrutura do Projeto

```text
webpack-template/
|- src/
|  |- greeting.js
|  |- index.js
|  |- styles.css
|  |- template.html
|- package.json
|- webpack.config.js
|- .gitignore
```

## Como Executar

### Pre-requisitos

- Node.js 18+ (recomendado)
- npm

### Passos

1. Instale as dependencias:

```bash
npm install
```

2. Rode o servidor de desenvolvimento:

```bash
npx webpack serve
```

3. Abra no navegador:

```text
http://localhost:8080
```
## Observações

- O template esta configurado para desenvolvimento (`mode: development`).
- O bundle de saida é gerado em `dist/` com limpeza automática a cada build.
- O layout base segue o padrao Holy Grail com sidebar esquerda, conteúdo central e sidebar direita em telas maiores.





