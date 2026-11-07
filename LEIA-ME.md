# Passagem Zero — Como publicar na Vercel

Esta pasta contém a página completa em um único arquivo (`index.html`). Não precisa de build, Node.js nem configuração extra.

## Opção 1 — Arrastar e soltar (mais fácil)

1. Acesse https://vercel.com e faça login.
2. No painel, clique em **Add New… → Project**.
3. Role até o final da página e clique em **Deploy a static site** (ou arraste esta pasta inteira para a área indicada).
4. A Vercel publica na hora e te dá um endereço `https://seu-projeto.vercel.app`.

## Opção 2 — Pelo terminal (Vercel CLI)

```bash
npm install -g vercel
cd passagem-zero-vercel
vercel --prod
```

## Observações

- O arquivo é 100% estático: funciona em qualquer hospedagem (Vercel, Netlify, GitHub Pages, servidor próprio).
- A fonte (Raleway) é carregada do Google Fonts, então a página precisa de internet para exibir a fonte exata — sem internet, usa uma fonte padrão do sistema.
- Os espaços de depoimento estão marcados com `[Espaço para depoimento real]`, `[Nome]` e `[Cidade / situação]`. Substitua pelos depoimentos reais antes de divulgar.
- O botão "Quero receber informações" aponta para `#informacoes`. Quando o canal oficial estiver definido, troque o `href` pelo link ou telefone oficial.
