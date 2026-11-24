<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=14213D&height=120&section=header" width="100%"/>

  <h1>
    Olá, eu sou Diego Batista
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
  </h1>

  <p>
    <strong>Desenvolvedor Full Stack</strong> · React · TypeScript · Node.js<br>
    Crio aplicações web do layout ao deploy, com projetos em produção para clientes reais.
  </p>

  <p>
    <a href="https://dieguin77.github.io/site-diego-dev/">
      <img src="https://img.shields.io/badge/Portfólio-dieguin77.github.io-14213D?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfólio">
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

- Estudante de **Tecnologia em Sistemas para Internet** no IFES (conclusão prevista para 2027)
- Projetos **comerciais em produção**: sistema de vendas com pagamento por PIX e cartão, sites institucionais e landing pages
- Foco em **front-end com React e TypeScript**, integrado a APIs REST e bancos de dados
- Cuidado com SEO, acessibilidade e desempenho
- Objetivo: atuar como **Desenvolvedor Front-end ou Full Stack**

---

## Projetos em Destaque

### [Everlabs Full Stack](https://everlabs-fullstack.vercel.app) | Gestão de Tarefas (Kanban)
> Sistema full stack de gestão de tarefas estilo Kanban, criado a partir de um desafio técnico. [Código-fonte](https://github.com/Dieguin77/everlabs-fullstack) · Login demo: `admin@demo.com` / `demo12345`

**Stack:** TypeScript · React 18 · Redux Toolkit · Node.js · Express · Prisma · PostgreSQL · Docker

- Clean Architecture (domain/infra/shared) com injeção de dependência via TSyringe
- Autenticação JWT com perfis Admin/User e permissões por rota
- Quadro Kanban com drag-and-drop nativo, sem bibliotecas externas
- Upload de anexos, comentários e tags nas tarefas
- Testes automatizados com Vitest e documentação da API com Swagger
- Deploy com Vercel (front-end), Render (API) e Supabase (banco)

---

### [UMADGOV 2026](https://umadgov.com.br) | Sistema de Vendas
> Sistema web em produção para a venda das camisas oficiais do evento UMADGOV 2026, com pagamento por PIX e cartão e painel administrativo. [Código-fonte](https://github.com/Dieguin77/umadgov-2026)

**Stack:** React · Vite · JavaScript · Supabase (Postgres, Auth, Storage) · Vercel Functions · InfinitePay

- QR Code PIX (payload EMV/BR Code) gerado no próprio navegador
- Pagamento por cartão com o checkout da InfinitePay e confirmação automática por webhook
- Upload de comprovante e consulta pública do status do pedido
- Painel administrativo com Supabase Auth e políticas RLS por perfil
- Numeração sequencial dos pedidos via trigger no Postgres

---

### [Sistema Lista de Tarefas](https://sistema-tarefas-app.fly.dev/) | API REST + Gestão de Tarefas
> Sistema web para cadastro e gerenciamento de tarefas, com API REST própria e persistência em SQLite. [Código-fonte](https://github.com/Dieguin77/sistema-lista-tarefas)

**Stack:** Node.js · Express · SQLite (sql.js) · Docker · Fly.io

- CRUD completo com validações (nome único, custo ≥ 0, data válida)
- Reordenação por drag-and-drop e por botões, salva no banco
- Destaque visual automático para tarefas de custo elevado
- Deploy em contêiner com volume persistente no Fly.io

---

### [Tocando Pra Valer](https://tocando-pra-valer3-0.vercel.app) | Plataforma Musical
> Plataforma musical gratuita para músicos brasileiros: cifras, afinador, metrônomo e piano virtual. [Código-fonte](https://github.com/Dieguin77/tocando-pra-valer-3)

**Stack:** React 18 · Vite · Tailwind CSS · React Router · EmailJS · Vercel

- Busca de cifras em tempo real (`useDeferredValue`) com transposição automática de tom
- Afinador pelo microfone (Web Audio API) e metrônomo interativo
- Envio e aprovação de cifras com back-ends configuráveis (Supabase, Google Sheets, Formspree, localStorage)
- Notificações por e-mail sem servidor próprio (EmailJS)
- Code splitting por rota e SEO técnico (Schema.org, Open Graph, sitemap)

---

### [gladstonfreire.com.br](https://gladstonfreire.com.br) | Site Institucional & Marca Pessoal
> Site oficial de Gladston Freire: ministro, escritor, advogado e palestrante. [Código-fonte](https://github.com/Dieguin77/gladston-freire)

**Stack:** HTML5 · CSS3 · JavaScript · Sanity.io · Supabase · GitHub Pages

- Landing page com pregações, livro, agenda ministerial e blog
- CMS headless com Sanity.io para publicação de artigos
- Formulário de agenda salvo no Supabase, com aviso por e-mail (EmailJS)
- Painel administrativo para gestão de convites
- SEO: Schema.org, Open Graph, sitemap e robots.txt

---

### [Diego Dev](https://dieguin77.github.io/site-diego-dev/) | Portfólio & Landing Page de Serviços
> Landing page comercial para apresentar projetos e serviços e captar contatos pelo WhatsApp. [Código-fonte](https://github.com/Dieguin77/site-diego-dev)

**Stack:** HTML5 · CSS3 · JavaScript · GitHub Pages

- Teste A/B na seção principal e conversões medidas no Google Analytics 4
- Formulário que monta a mensagem e abre o WhatsApp, sem back-end
- SEO técnico: dados estruturados JSON-LD, Open Graph, sitemap e robots.txt
- Aviso de cookies (LGPD) e acessibilidade (skip link, `aria-label`, `prefers-reduced-motion`)

---

## Tecnologias

### Linguagens
<p>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
</p>

### Front-end
<p>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
<img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux Toolkit">
<img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white" alt="React Router">
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
</p>

### Back-end
<p>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express">
<img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma">
<img src="https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=openapiinitiative&logoColor=white" alt="REST API">
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT">
</p>

### Banco de dados e CMS
<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
<img src="https://img.shields.io/badge/Sanity.io-F03E2F?style=for-the-badge&logo=sanity&logoColor=white" alt="Sanity.io">
</p>

### Testes e qualidade
<p>
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest">
<img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint">
<img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black" alt="Prettier">
</p>

### Cloud, deploy e DevOps
<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900" alt="AWS">
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" alt="Render">
<img src="https://img.shields.io/badge/Fly.io-8B5CF6?style=for-the-badge&logo=flydotio&logoColor=white" alt="Fly.io">
<img src="https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Netlify">
<img src="https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="GitHub Pages">
</p>

### Ferramentas
<p>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code">
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma">
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude Code">
</p>

Na faculdade também programei em **C** e **Python**.

---

## Estatísticas

<div align="center">

  <img height="160" src="https://github-readme-stats-murex-eta-47.vercel.app/api?username=Dieguin77&show_icons=true&theme=dark&bg_color=0d0d0d&title_color=14213D&icon_color=14213D&text_color=ffffff&border_color=14213D&hide_border=false&count_private=true" alt="GitHub Stats">
  <img height="160" src="https://github-readme-stats-murex-eta-47.vercel.app/api/top-langs/?username=Dieguin77&layout=compact&theme=dark&bg_color=0d0d0d&title_color=14213D&text_color=ffffff&border_color=14213D&hide_border=false" alt="Top Languages">

</div>

---

## Atualmente estudando

- Fundamentos de **JavaScript e TypeScript** (tipos, assincronismo, imutabilidade)
- **React** em profundidade: hooks, estado, gerenciamento com Redux Toolkit e desempenho
- Testes de front-end com **Vitest e Testing Library**
- **AWS Certified AI Practitioner** (Escola da Nuvem)
- **Inglês** técnico para o dia a dia de desenvolvimento

---

<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=14213D&height=80&section=footer" width="100%"/>

</div>
