# cchooks — Hooks do Claude Code

Curso web **self-contained** (HTML + fontes CDN + JS inline, sem build/backend, funciona em `file://`) inteiramente sobre **hooks do Claude Code**: dos fundamentos às travas de segurança, à automação e ao uso em equipe/CI. Formato-curso INEMA **v4** — dark editorial com movimento, leitura viva (uma ideia por seção + figura na margem) e uma camada de aprendizagem com retenção (progresso, marcar lido, teste-se, grifo → flashcard, revisão espaçada, "pratique agora", "minha jornada").

## Estrutura

- `index.html` — redireciona para a landing.
- `landing.html` — porta do curso: hero + as 4 trilhas + método.
- `curso.html` — **Trilha 01 · Fundamentos** (5 aulas). Página única (roteamento por hash `#trilha`, `#aula-1`…), estado próprio em `localStorage`.
- `curso-guardrails.html` — **Trilha 02 · Guardrails** (4 aulas): travas de segurança.
- `curso-automacao.html` — **Trilha 03 · Automação** (4 aulas): formatar, avisar, logar, injetar contexto.
- `curso-time.html` — **Trilha 04 · Equipe & CI** (4 aulas): versionar, determinismo, headless, higiene.
- `assets/aula.css` — design language v4 (tokens, temas dark/papel/sépia, leitura + trilho + painéis).
- `assets/curso.js` — motor da página única (roteador, progresso, teste-se, grifo/flashcard, revisão espaçada, jornada, export/import).

Cada trilha é uma página v4 independente (estado isolado por `<meta name="curso">`); a subnav no topo cruza entre as trilhas.

## As trilhas

1. **Fundamentos** — o que é um hook · os eventos do ciclo · `settings.json` · o que o hook recebe (JSON no stdin) · como responde (exit code + JSON).
2. **Guardrails** — a ideia de trava (`exit 2`) · ler o comando · casos reais · allow/ask/deny + higiene.
3. **Automação** — formatar ao salvar · avisar ao terminar · registrar comandos · injetar contexto.
4. **Equipe & CI** — versionar pro time · determinismo · rodar headless/pipeline · hook é poder (segurança).

## Publicado em

GitHub Pages: https://inematds.github.io/cchooks/

> Conteúdo educativo sobre hooks do Claude Code — no formato-curso INEMA v4.
