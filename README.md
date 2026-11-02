# Portfólio — Lucas Roberto

Site pessoal de Lucas Roberto Oliveira, desenvolvedor Full Stack em Teresina, PI.

Arquivo único (`index.html`): HTML, CSS e JavaScript, sem dependências de build. Inclui projetos, sobre, arsenal com ícones, seção de dados, um mini jogo de plataforma em Canvas 2D e contato.

## Como ver localmente

Basta abrir `index.html` no navegador. Ou, com Python instalado:

```bash
python3 -m http.server 8000
```

Depois acesse http://localhost:8000.

## Como editar

- **Projetos:** cards em `<article class="card">` e objeto `P` no script de detalhes.
- **Tecnologias e ícones:** objeto `ICON` e `LABEL` no script do topo. `LEARNING` define quais chips aparecem como "aprendendo".
- **Mini jogo:** seção `#jogo`, com níveis (`PL`, `COINS0`, `SPIKES`, `GOAL`) no script do jogo.
- **Cores e fontes:** variáveis CSS em `:root`.

## Como publicar

Qualquer hospedagem de site estático serve: GitHub Pages, Netlify, Vercel ou Cloudflare Pages. Para o GitHub Pages: Settings → Pages → Source: branch `main`, pasta `/ (root)`.

## Pendências

- Capturas reais de Trilha Full Stack 3.0 e HortiGestão PRO (hoje são ilustrações conceituais).
- Currículo em PDF (botão de download ainda não está na página).
- Imagem de compartilhamento (og:image).

## Licença

Todo o conteúdo é pessoal. O código pode ser reutilizado como referência; fotos e capturas não podem ser usadas sem autorização.
