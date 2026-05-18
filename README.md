# arthuramossantos.dev

Site pessoal de Arthur Ramos dos Santos — pesquisador em proteção digital e aprendizado federado.

## Stack
- [Astro](https://astro.build/) — framework estático
- GitHub Pages — hospedagem gratuita
- Deploy automático via GitHub Actions

## Desenvolvimento local

```bash
npm install
npm run dev
```

Acessa em `http://localhost:4321`

## Estrutura

```
src/
├── layouts/
│   └── Base.astro       # Layout compartilhado
├── pages/
│   ├── index.astro      # Página inicial
│   ├── research.astro   # Pesquisa
│   ├── sobre.astro      # Sobre
│   └── blog/
│       └── index.astro  # Blog
```

## Deploy

Push para `main` → GitHub Actions faz build → publica em GitHub Pages.

## Domínio

Para conectar `arthuramossantos.dev`:
1. Compra o domínio (Namecheap, ~$13/ano)
2. Adiciona arquivo `CNAME` em `public/` com o conteúdo `arthuramossantos.dev`
3. Configura DNS no provedor: CNAME `www` → `seuusuario.github.io`
# ArthurRepositorio
