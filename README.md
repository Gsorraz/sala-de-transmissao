# Sala de Transmissão

Página única (HTML + CSS + JavaScript) para assistir a uma **transmissão de tela ao vivo** junto com outras pessoas,
com chat na lateral. A tela é capturada com `getDisplayMedia` e enviada direto entre os navegadores (WebRTC via
**PeerJS**), sem servidor de vídeo no meio.

## Como usar
1. Sirva a pasta por `http://localhost` (ex.: `python -m http.server 8000`) ou publique no Netlify.
   A captura de tela não funciona abrindo o arquivo direto.
2. Abra a página, digite seu nome e entre.
3. Quem vai mostrar a tela clica em transmitir; os outros assistem e conversam no chat.

