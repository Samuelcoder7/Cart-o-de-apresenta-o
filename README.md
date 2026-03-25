# Cartao Digital

Projeto de cartao de identificacao digital feito com Ionic + Angular (standalone). A pagina inicial mostra um cartao com foto e dados basicos, e o botao "Ver mais" leva para a pagina de detalhes.

## Funcionalidades
- Cartao de identificacao com foto e informacoes
- Navegacao entre Home e Sobre
- Estilo moderno no card

## Tecnologias
- Ionic
- Angular (standalone)
- TypeScript
- SCSS

## Requisitos
- Node.js
- Ionic CLI

## Como rodar
1. Instale as dependencias:

```bash
npm install
```

2. Inicie o servidor de desenvolvimento:

```bash
ionic serve
```

Acesse no navegador o endereco mostrado no terminal.

## Rotas
- `/home` pagina principal
- `/sobre` pagina de detalhes

## Estrutura principal
- `src/app/home/` tela principal do cartao
- `src/app/sobre/` tela de detalhes
- `src/app/app.routes.ts` configuracao de rotas

## Personalizacao rapida
- Troque a imagem em `src/assets/`
- Edite os textos em `src/app/home/home.page.html`
- Ajuste o estilo em `src/app/home/home.page.scss`

## Build (producao)
```bash
ionic build
```
