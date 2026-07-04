# cchooks — Claude Code na prática · Trilha 03: Automação & Hooks

Curso web self-contained (HTML + fontes CDN + JS inline, sem build/backend, funciona em `file://`) sobre **hooks do Claude Code**. Formato-curso INEMA **v4**: dark editorial com movimento, leitura viva (uma ideia por seção + figura na margem) e uma camada de aprendizagem com retenção (progresso, marcar lido, grifo → flashcard, revisão espaçada, "minha jornada").

## Estrutura

- `index.html` — redireciona para a landing.
- `landing.html` — landing do curso (as seis trilhas; a Trilha 03 está aberta).
- `curso.html` — **a experiência principal**: página única (trilha + 5 aulas como views, roteamento por hash `#trilha`, `#aula-1`…`#aula-5`), com um único estado de progresso em `localStorage`.
- `assets/aula.css` — design language v4 (tokens, temas dark/papel/sépia, leitura + trilho + painéis).
- `assets/curso.js` — motor da página única (roteador, progresso na trilha, teste-se, grifo/flashcard, revisão espaçada, jornada, export/import).

## Publicado em

GitHub Pages: https://inematds.github.io/cchooks/

> Conteúdo educativo sobre hooks do Claude Code — demo do formato-curso v4.
