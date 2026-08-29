# China 2027

Aplicativo offline de viagem da familia Arci, China e Tibete, 28/12/2026 a 28/01/2027.

Publicado em GitHub Pages. Funciona sem internet depois de aberto uma vez.

## Arquivos do site

- `index.html` aplicativo inteiro, com dados e documentos criptografados embutidos
- `manifest.json` permite instalar como aplicativo no Android
- `sw.js` service worker, faz o app funcionar offline
- `icon-192.png` e `icon-512.png` icones da tela inicial

## Nao publicados

`CHINA2027_BACKUP.html` e `COMO_PUBLICAR.md` ficam de fora pelo .gitignore. O backup e para uso local, e o guia e documentacao interna.

## Atualizar

Substituir o `index.html` e dar commit. O service worker tem versao propria, entao o app se atualiza sozinho na proxima abertura com internet.
