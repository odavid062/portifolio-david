# Landing — David Rodrigues

Landing page comercial de David Rodrigues de Sousa. O site apresenta produtos digitais e soluções com software, inteligência artificial e automação.

## Acesso

- Site: https://davidrodrigues.dev.br/
- GitHub: https://github.com/odavid062
- LinkedIn: https://www.linkedin.com/in/david-rodrigues-00b988214/

## Conteúdo

- Plataforma de estudos para concursos: simulados, flashcards e desempenho
- CRM com WhatsApp e IA: funil, etiquetas, follow-up e atendimento humano
- Gestão financeira: despesas, cartões, parcelamentos, metas e dashboards
- Agentes de IA, automações, integrações entre sistemas, aplicações e dashboards
- Apresentação breve e contato

A plataforma de estudos é uma aplicação separada, com repositório e deploy próprios. Este repositório contém apenas a landing.

## Tecnologias do site

- HTML5, CSS3 responsivo e JavaScript puro, sem etapa de build
- Vercel para hospedagem e deploy contínuo

## Executar localmente

Como o projeto é estático, abra `index.html` no navegador. Para usar um servidor local:

```bash
npx serve .
```

## Publicação

O repositório está conectado à Vercel (projeto `portfolio-david`). Cada push para a branch `master` gera uma nova implantação de produção automaticamente, servida em `davidrodrigues.dev.br`. Pushes em outras branches geram implantações de preview.

## Estrutura

- `index.html` — conteúdo da página, metadados de SEO, dados estruturados (Person e WebSite) e a arte do hero em SVG inline (fluxos de automação)
- `style.css` — estilos, incluindo a animação dos pulsos da arte
- `script.js` — menu mobile e animações de entrada
- `og-image.jpg` — imagem de compartilhamento (1200×630) com a mesma arte do hero
- `hero.webp` — foto usada no hero anterior; não é mais referenciada pela página
- `robots.txt` e `sitemap.xml` — rastreamento e indexação
- `vercel.json` — configuração de hospedagem
- `README.md` — documentação do projeto

Para atualizar o conteúdo, edite `index.html` (e `style.css` para o visual) e faça push para `master`.
