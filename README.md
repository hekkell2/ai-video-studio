# AI Video Studio (Protótipo HTML)

Projeto inicial em HTML/CSS/JS puro com interface para gestão de múltiplas histórias, blocos, imagens e vídeos.

## Como executar

Como é um protótipo estático, basta abrir o `index.html` no navegador.

Opcionalmente, rode um servidor local:

```bash
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## O que já existe

- Tela inicial com cards de histórias.
- Workspace por história com:
  - Mapa de cenas lateral.
  - Blocos com colunas de texto, imagens e vídeos.
  - Menu de ações por thumbnail.
- Modal de biblioteca com abas de imagens e vídeos.
- Placeholders (`alert`) para integrações futuras.

## Próximos passos sugeridos

1. Separar CSS e JS em arquivos (`styles.css` e `app.js`).
2. Trocar mocks por dados reais (API/back-end).
3. Implementar persistência (localStorage ou banco).
4. Substituir `alert` por modais de fluxo real.
5. Adicionar autenticação e permissões de projeto.
