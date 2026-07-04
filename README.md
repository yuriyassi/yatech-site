# YATECH Automação — Landing Page

Landing page institucional da YATECH Automação, gerada com Google Stitch e ajustada manualmente.

## Stack
- HTML puro + Tailwind CSS (via CDN, sem build necessário)
- Sem dependências, sem processo de build — funciona direto como site estático

## Rodando localmente
Basta abrir o `index.html` no navegador, ou usar um servidor simples:

```bash
python3 -m http.server 8000
```

## Deploy
Este projeto está pronto para deploy direto na Vercel como site estático (sem framework, sem build command).

## Pendências conhecidas
- A imagem do mapa na seção "Nossa Base de Operações" usa uma URL temporária gerada pelo Stitch (`googleusercontent.com`) — trocar por imagem própria antes de ir definitivo pra produção.
