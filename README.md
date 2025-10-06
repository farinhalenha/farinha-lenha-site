# Site Farinha & Lenha — GitHub Pages
- Edite `site/index.html` para ajustar cardápio, horários, WhatsApp, etc.
- Publicação no GitHub Pages (rápido):
  1. Crie um repositório no GitHub
  2. Suba os arquivos e **mova o conteúdo de `site/` para a raiz** do repositório (ou configure Pages para `site/`)
  3. Em *Settings → Pages*: *Deploy from a branch*, branch `main`, pasta `/ (root)`
  4. Acesse a URL do Pages e defina no console:
     ```js
     localStorage.setItem('PRINT_WEBHOOK','https://SUA-URL-DE-TUNEL/print')
     // (opcional) se a ponte usar chave:
     localStorage.setItem('PRINT_KEY','MINHA_CHAVE')
     ```
