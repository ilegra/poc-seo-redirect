# POC SEO REDIRECT

## Requerimentos

- [ngrok](https://ngrok.com/)
- [http-server](https://github.com/indexzero/http-server)

## Como testar

1) Inicializar dois servidores `http-server`, um em cada pasta
2) Inicializar dois `ngrok`, um em cada pasta
3) Trocar o valor da variável `serverSideUrl` em `/client-side/index.html`
4) Trocar o valor do link `canonical` em `/server-side/index.html`
5) Acessar o [Google Search Console](https://search.google.com/search-console/welcome) e verificar a página do `client-side` seguindo as instruções
6) Inspecionar a URL > TEST LIVE URL > Verificar no resultado a página `server-side` sendo renderizada

