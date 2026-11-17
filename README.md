<h1 align="center">Cezar Augusto Vellozo</h1>

<p align="center">
  <b>Desenvolvedor Frontend Júnior</b><br>
  React · TypeScript · JavaScript · Node.js · SQL
</p>

<p align="center">
  <a href="https://augusto10vellozo-coder.github.io/site-servicos/"><img src="https://img.shields.io/badge/Servi%C3%A7os-sites%20e%20sistemas%20web-d9451c?style=flat-square" alt="Site de serviços"></a>
  <a href="https://taskbio.com.br"><img src="https://img.shields.io/badge/App%20no%20ar-taskbio.com.br-123d2c?style=flat-square" alt="App no ar"></a>
  <a href="https://idyllic-dodol-fc7f03.netlify.app/demo"><img src="https://img.shields.io/badge/Demo-prato%20digital-e0443e?style=flat-square" alt="Demo do Prato Digital"></a>
  <a href="https://www.linkedin.com/in/cezarvellozo/"><img src="https://img.shields.io/badge/LinkedIn-cezarvellozo-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:augusto10vellozo@gmail.com"><img src="https://img.shields.io/badge/Email-augusto10vellozo@gmail.com-BB4433?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

Construo aplicações web reais, não exercícios de curso. Venho de 7 anos em gestão de processos (PCP)
— o que me deu disciplina de entrega, leitura de processo e obsessão por dado correto, que hoje
aplico em código.

**Faço sites e sistemas web sob medida para pequenos negócios.**
Orçamento e escopo em [augusto10vellozo-coder.github.io/site-servicos](https://augusto10vellozo-coder.github.io/site-servicos/).

**Qualidade:** CI em todos os projetos de código, **311 testes** no TaskBio, **27** no Prato Digital e
Lighthouse **100/100/100** nos sites publicados.

## Projetos

### [TaskBio](https://taskbio.com.br) — plataforma de rotina e saúde · [código](https://github.com/augusto10vellozo-coder/taskbio)
Agenda, treino, alimentação, hábitos e estudos no mesmo dia, com um só progresso. Em produção, com
domínio próprio e uso diário.
**React 19 · TypeScript · TanStack Start · Supabase · Tailwind CSS v4 · Cloudflare**

- **311 testes automatizados** em 39 suítes (Vitest), cobrindo as regras de domínio
- Row Level Security em **26 tabelas**; pontuação decidida no servidor por funções Postgres idempotentes, com trigger que bloqueia escrita direta
- PWA instalável com notificações push agendadas por cron no banco
- Tema claro/escuro por tokens de CSS, aplicado antes do primeiro paint

### [Prato Digital](https://idyllic-dodol-fc7f03.netlify.app/demo) — SaaS de cardápios e sites · [código](https://github.com/augusto10vellozo-coder/prato-digital)
Plataforma para desenvolvedores venderem cardápios digitais a restaurantes: wizard de prospecção,
CRM com quadro e funil, editor de cardápio e de site, exportação em HTML autônomo e sites públicos.
**React 19 · TypeScript · Vite · React Router** — 40+ rotas, SPA estática, estado persistido no
navegador com export/import em JSON.

### [Dossiê](https://augusto10vellozo-coder.github.io/dossie-crm/app.html?demo=1) — CRM de candidatos · [código](https://github.com/augusto10vellozo-coder/dossie-crm)
Aplicativo offline em arquivo único para o RH importar a planilha de candidatos, organizar a base e
imprimir a ficha padrão da empresa em A4.
**HTML, CSS e JavaScript puros** — zero dependências, dados no navegador, backup em JSON e demo com
10 candidatos fictícios.

### [Motor de Diagnóstico de Energia](https://github.com/augusto10vellozo-coder/motor-diagnostico-energia) — regras plugáveis em Node
Recebe faturas de energia normalizadas e devolve achados priorizados com evidência e nível de
confiança, separando economia confirmada de pista a auditar.
**Node.js puro** — 7 regras independentes, extrator de PDF do grupo Copel que lê as **coordenadas
x/y** para reconstruir a tabela (29 de 30 PDFs nativos reconciliados) e relatório HTML offline.

### [Controle de Faturas de Energia](https://augusto10vellozo-coder.github.io/site-servicos/casos/controle-faturas.html) — automação interna
Painel offline que lê PDFs de faturas, confere a emissão por unidade e estima a economia solar.
**Node.js · PDF · OCR · HTML offline** — código privado; o case mostra o fluxo e as telas com dados
fictícios.

### [Estoque do Mercado](https://github.com/augusto10vellozo-coder/estoque-mercado) — operação de estoque
Recebimento por código de barras, livro de movimentos com custo médio ponderado, alerta de
reposição e API local servida na rede da loja.
**Node.js + SQLite, zero dependências** — saldo calculado por soma de movimentos, nunca campo
editável, com auditoria de quem mexeu e quando.

### [Painel Financeiro](https://augusto10vellozo-coder.github.io/painel-financeiro/) — dashboard consolidado
Protótipo de alta fidelidade em **HTML, CSS e JavaScript puros**, sem framework e sem build.
Três escopos na mesma tela (Pessoal / Empresa / Consolidado), cinco KPIs com variação percentual,
gráfico receita × custos em SVG e distribuição por categoria.

### [Painel do Mercado](https://augusto10vellozo-coder.github.io/painel-mercado/) — indicadores do varejo · [código](https://github.com/augusto10vellozo-coder/painel-mercado)
Lê a exportação do PDV e a planilha de estoque e gera **um HTML offline** com venda, margem, CMV,
ruptura, validade e contas a pagar.
**Node.js + CSV** — importador que descarta dado pessoal por configuração e demo com base fictícia.

### [Sabor de Casa](https://receitassabordecasa.com.br) — site de receitas
Site estático gerado por um script Node a partir de JSON, com schema `Recipe`, sitemap e checagem
de conteúdo. Publicado com domínio próprio no GitHub Pages.

### [Banners HTML5 e e-mail marketing](https://augusto10vellozo-coder.github.io/portfolio-rich-media/) — peças de campanha · [código](https://github.com/augusto10vellozo-coder/portfolio-rich-media)
Peças de campanha em arquivo único, **abaixo de 5 KB**, com animação restrita a `transform` e
`opacity` e suporte a `clickTag`. E-mail responsivo de 600 px em tabela com CSS inline,
compatível com Outlook.

## Stack

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white">
</p>

## Formação

**Desenvolvimento Full Stack — DevClub** (em andamento) · Análise e gestão de processos (7 anos de
experiência profissional)

---

<p align="center">
  <sub>Aberto a oportunidades júnior, remotas. Português nativo · inglês intermediário.</sub>
</p>
