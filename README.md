# Landing Page — David Rodrigues

Página pessoal estática (HTML/CSS/JS puro) — Analista de Sistemas, Dev com IA e Engenheiro de Prompt.

## Como publicar no Vercel

### Opção 1 — Mais fácil: arrastar pasta no painel
1. Acesse https://vercel.com e faça login com GitHub, GitLab ou e-mail.
2. Clique em **Add New → Project → Deploy** (ou simplesmente arraste a pasta).
3. Selecione **a pasta que contém `index.html` e `vercel.json`**.
4. Confirme. A Vercel detecta como projeto estático automaticamente.
5. Em ~30 segundos seu site estará no ar em `https://<nome-projeto>.vercel.app`.

### Opção 2 — Via GitHub (recomendado)
1. Crie um repositório novo no GitHub (ex.: `portfolio-david`).
2. Suba os arquivos (`index.html`, `vercel.json`, `README.md`).

```bash
git init
git add .
git commit -m "feat: landing page inicial"
git branch -M main
git remote add origin https://github.com/odavid062/portfolio-david.git
git push -u origin main
```

3. Em https://vercel.com → **Import Project** → selecione o repositório.
4. Clique em **Deploy**. Toda alteração no `main` faz redeploy automático.

### Opção 3 — Vercel CLI
```bash
npm install -g vercel
vercel
```
Siga o assistente. Para produção: `vercel --prod`.

## Domínio personalizado (opcional)
No painel da Vercel → seu projeto → **Settings → Domains** → adicione seu domínio (ex.: `davidrodrigues.dev`).

## Estrutura

- `index.html` — Página única com todas as seções
- `vercel.json` — Configuração de headers de segurança e URLs limpas
- `README.md` — Este arquivo

## Editando

Tudo está no `index.html`. Para mudar cores, edite as variáveis CSS no topo (`:root`).
