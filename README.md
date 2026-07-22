<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=#102A43&height=120&section=header" width="100%"/>

  <h1>
    Olá, eu sou Diego Batista
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
  </h1>

  <p>
    <strong>Desenvolvedor Full Stack</strong> · Tecnologia em Sistemas para Internet<br>
    Construindo interfaces modernas, responsivas e integradas a serviços reais e estudando AWS.
  </p>

  <p>
    <a href="https://diegodev.dev.br">
      <img src="https://img.shields.io/badge/Portfólio-diegodev.dev.br-b71c1c?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfólio">
    </a>
    <a href="mailto:diegobatistt@gmail.com">
      <img src="https://img.shields.io/badge/E--mail-diegobatistt@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail">
    </a>
    <a href="https://github.com/Dieguin77">
      <img src="https://img.shields.io/badge/GitHub-Dieguin77-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
    </a>
  </p>

</div>

---

## Sobre mim

- Desenvolvedor **Tecnologia em Sistemas para Internet** (IFES)
- Experiência prática em projetos **pessoais e comerciais**
- Foco em interfaces modernas, SEO, acessibilidade e integração com APIs
- Atualmente aprofundando conhecimentos em **React**, **Node.js** e **PostgreSQL**
- Objetivo: atuar como **Desenvolvedor Full Stack**, entregando soluções que geram valor real

---

## Tecnologias

### Front-End
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
</p>

### Back-End & Banco de Dados
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Sanity.io-F03E2F?style=for-the-badge&logo=sanity&logoColor=white" alt="Sanity.io">
</p>

### Ferramentas & Deploy
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
  <img src="https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages">
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code">
  <img src="https://img.shields.io/badge/Figma-007ACC?style=for-the-badge&logo=Figma&logoColor=white" alt="Figma">
</p>

---

## Projetos em Destaque

### [Everlabs Full Stack](https://everlabs-fullstack.vercel.app) | Gestão de Tarefas (Kanban)
> Sistema fullstack de gestão de tarefas estilo Kanban, desenvolvido como desafio técnico para vaga de Estagiário Full Stack. [Código-fonte](https://github.com/Dieguin77/everlabs-fullstack) · Login demo: `admin@demo.com` / `demo12345`

**Stack:** Node.js · Express · TypeScript · Prisma · React 18 · Redux Toolkit · Docker

- Clean Architecture (domain/infra/shared) com injeção de dependência via TSyringe
- Autenticação JWT com perfis Admin/User e permissões por rota
- Quadro Kanban com drag-and-drop nativo, sem bibliotecas externas
- Upload de anexos, comentários e sistema de tags nas tarefas
- Testes automatizados (Vitest) e documentação da API via Swagger
- Ambiente completo containerizado com Docker Compose

---

### [UMADGOV 2026](https://umadgov.com.br) | Sistema de Gestão
> Sistema Web para venda e organização das camisas oficiais do evento UMADGOV 2026, com pagamento via PIX e painel administrativo.

**Stack:** React · Vite · Supabase · JavaScript

- Geração de QR Code PIX (payload EMV/BR Code) direto no navegador, sem depender de gateway externo
- Upload opcional de comprovante e consulta pública do status do pedido
- Painel administrativo com autenticação e controle de acesso por perfil (Supabase Auth + RLS)
- Numeração de pedido automática e sequencial via trigger no Postgres

---

### [Sistema Lista de Tarefas](https://sistema-tarefas-app.fly.dev/) | API REST + Gestão de Tarefas
> Sistema web para cadastro e gerenciamento de tarefas, com API REST própria e persistência em SQLite.

**Stack:** Node.js · Express · SQLite (sql.js) · Docker · Fly.io

- CRUD completo com validações (nome único, custo ≥ 0, data válida)
- Reordenação por drag-and-drop e por botões, persistida no banco
- Destaque visual automático para tarefas de custo elevado
- Deploy containerizado com volume persistente no Fly.io

---

### [Tocando Pra Valer](https://tocando-pra-valer3-0.vercel.app) | Plataforma Musical
> Plataforma musical completa para músicos brasileiros — cifras, afinador, metrônomo e piano virtual, 100% gratuita.

**Stack:** React 18 · Vite · Tailwind CSS · React Router · EmailJS · Vercel

- Busca de cifras em tempo real (`useDeferredValue`) com transposição automática de tom
- Afinador via microfone (Web Audio API) e metrônomo interativo
- Sistema de envio/aprovação de cifras com múltiplos backends configuráveis (Supabase, Google Sheets, Formspree, localStorage)
- Notificações por e-mail sem servidor próprio (EmailJS)
- Code splitting por rota e SEO técnico completo (Schema.org, Open Graph, sitemap)

---

### [gladstonfreire.com.br](https://gladstonfreire.com.br) | Site Institucional & Marca Pessoal
> Site oficial de Gladston Freire | Ministro, Escritor, Advogado e Palestrante.

**Stack:** HTML5 · CSS3 · JavaScript · Sanity.io · Supabase · GitHub Pages

- Landing page com hero, pregações, livro, agenda ministerial e blog
- CMS headless integrado ao Sanity.io para publicação de artigos
- Formulário de agenda com persistência no Supabase e notificação por EmailJS
- Painel administrativo para gestão de convites
- SEO avançado: Schema.org, Open Graph, sitemap, robots.txt
- Responsivo para mobile, tablet e desktop

---

### [Diego Dev](https://diegodev.dev.br) | Portfólio & Landing Page de Serviços
> Landing page comercial para apresentação de projetos, serviços e captação de leads via WhatsApp.

**Stack:** HTML5 · CSS3 · JavaScript · GitHub Pages

- Teste A/B da seção hero e rastreamento de conversão integrado ao Google Analytics 4
- Formulário de contato que monta a mensagem e abre o WhatsApp diretamente, sem back-end
- SEO técnico completo: dados estruturados JSON-LD, Open Graph, sitemap e robots.txt
- Banner de consentimento (LGPD) e acessibilidade (skip link, `aria-label`, `prefers-reduced-motion`)

---

## Estatísticas

<div align="center">

  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Dieguin77&show_icons=true&theme=dark&bg_color=0d0d0d&title_color=b71c1c&icon_color=b71c1c&text_color=ffffff&border_color=b71c1c&hide_border=false&count_private=true" alt="GitHub Stats">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dieguin77&layout=compact&theme=dark&bg_color=0d0d0d&title_color=b71c1c&text_color=ffffff&border_color=b71c1c&hide_border=false" alt="Top Languages">

</div>

---

## Atualmente estudando

- React avançado (hooks, context, performance)
- Node.js e APIs REST
- SQL e PostgreSQL
- Metodologias Ágeis | Scrum e Kanban
- Clean Code e boas práticas de desenvolvimento

---

<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=b71c1c&height=80&section=footer" width="100%"/>

</div>
