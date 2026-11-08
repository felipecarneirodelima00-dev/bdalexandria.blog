# Biblioteca de Alexandria

Site de resenhas de livros feito só com HTML, CSS e JavaScript, sem dependências. Os dados (contas, livros, resenhas) ficam salvos no `localStorage` do navegador.

## Estrutura

- `index.html`: páginas e abas do site
- `style.css`: visual
- `script.js`: lógica (contas, estante, resenhas, perfil, estatísticas e listas)

## Como usar

Abra o `index.html` no navegador. Para publicar, ative o GitHub Pages em Settings > Pages.

## E-mails (opcional)

Boas-vindas e recuperação de senha usam o [EmailJS](https://www.emailjs.com/). Preencha o objeto `EJ` no início do `script.js`. Sem isso o site funciona normalmente, só não envia e-mails.

## Limite

Sem servidor: os dados ficam só no navegador de cada pessoa e as senhas são guardadas em texto puro. Serve como protótipo.
