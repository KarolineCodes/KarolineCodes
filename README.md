# Karoline Silva

**Software Engineer** · Arquitetura e entrega end-to-end de produtos Web e Mobile

Trabalho do levantamento de requisitos ao deploy: APIs e microsserviços, interfaces
web de alta performance, aplicações mobile multiplataforma e orquestração de
agentes de IA integrados ao produto.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karolinencs)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:karoline.sln22@gmail.com)

---

## Projetos

### [Cadência](https://github.com/KarolineCodes/cadencia) · monorepo TypeScript

Plataforma de estudo para escolas de idiomas, com área do aluno e painel do
professor. O **mesmo módulo de agendamento roda no navegador e no servidor**,
então a tela responde na hora e os dois não têm como divergir.

Repetição espaçada adaptada ao calendário da escola, nivelamento que converge em
oito perguntas, correção de redação e conversação com IA que cita o trecho exato
e é verificada contra o texto. Autenticação com rotação de token e detecção de
reúso, autorização por recurso, 356 testes mais 138 de integração contra
Postgres real.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

O app móvel vive em [cadencia-app](https://github.com/KarolineCodes/cadencia-app).

### [Copiloto de Atendimento](https://github.com/KarolineCodes/copiloto-atendimento) · IA + engenharia

Painel de analytics onde o modelo **nunca vê os dados brutos e nunca calcula**.
Ele chama ferramentas tipadas, o código computa, o modelo narra, o que elimina
a classe de erro mais comum em produto com LLM: número inventado com confiança.

Provedores Anthropic, OpenAI e simulado; roda por completo sem chave de API.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![SSE](https://img.shields.io/badge/SSE-FF6C37?style=flat-square)

### [emaildispatch](https://github.com/KarolineCodes/emaildispatch) · infraestrutura em Go

Disparo de e-mail em massa com IP e DKIM próprios. Arquitetura hexagonal e
**zero dependências externas no núcleo**: o `go.mod` de desenvolvimento não tem
bloco `require`. Multi-cliente, com aquecimento de IP progressivo.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### [Caderneta](https://github.com/KarolineCodes/Caderneta-Flutter) · Flutter offline-first

Controle de fiado para pequeno comércio. SQLite é a fonte da verdade, não um
cache: escrita local e fila de envio na **mesma transação**, e lançamento é fato
imutável, o que torna a sincronização entre aparelhos uma união de conjuntos em
vez de um merge de dinheiro.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-40D0FD?style=flat-square)

### [Painel MF](https://github.com/KarolineCodes/painel-mf) · micro frontends

Painel de atendimento com Module Federation. Quatro barreiras de isolamento
garantem que um módulo remoto fora do ar não derrube o resto da aplicação.

![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Module Federation](https://img.shields.io/badge/Module%20Federation-1F6FEB?style=flat-square&logo=webpack&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

### [Maré UI](https://github.com/KarolineCodes/Mare-UI-Storybook) · design system

Biblioteca de componentes com arquitetura de tokens em duas camadas, 15
componentes acessíveis e Storybook publicado.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing%20Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white)

---

## Stack

**Linguagens**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white)

**Mobile**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

**Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**IA**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D4A27F?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

---

![Estatísticas](./profile/stats.svg)
![Linguagens](./profile/linguagens.svg)
