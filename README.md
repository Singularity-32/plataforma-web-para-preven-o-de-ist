# 🏥 PLATAFORMA WEB PARA PREVENÇÃO DE IST PARA JOVENS E PROFESSORES 🧬
Projeto Finalizador de Curso - Bacharelado em Engenharia de Software - 8° Período

# 🏥 ESTRUTURA E TECNOLOGIAS DO PROJETO 🧬

**Samuel Oliveira Acácio — RGM: 11231100856**
Bacharelado em Engenharia de Software — Universidade de Mogi das Cruzes - UMC 2026
Disciplina: Projeto de Finalização de Curso - PFC
Professor: Alessandro Aparecido da Silva Horas 
Orientador: Pedro Henrique Miho Souza

---

Front-end: 
HTML5, CSS3, Bootstrap, Javascript, Django Templates.

---

BACK-END
Python, Django Framework.

---

BANCO DE DADOS:
PostgreSQL, Django ORM.

---

VERSIONAMENTO:
Git, Github.

---

DEPLOY E HOSPEDAGEM:
Render, Github.

---

SEGURANÇA, LGPD E LOGS:
Django Auth, Hashing PBKDF2, Minimização de Dado.

---

TESTES E QUALIDADE:
Testes Unitários e de Integração (Django Test Framework).

---

REQUISITOS FUNCIONAIS: 
RF01: Permitir a consulta de conteúdos educativos organizados por categorias e temas.
RF02: Disponibilizar um guia educativo sobre prevenção de IST e métodos contraceptivos   
RF03: Permitir a realização de quizzes educativos com feedback explicativo.  
RF04: Permitir o cadastro e autenticação opcional de usuários.  
RF05: Permitir o registro e acompanhamento do progresso de usuários autenticados. 

---

REQUISITOS NÃO FUNCIONAIS: 
RNF01: Responsividade e Usabilidade.
RNF02: Desempenho e Disponibilidade.
RNF03: Segurança e Privacidade.
RNF04: Acessibilidade.

---

ENTIDADES DE DADOS: 
Usuário, Categoria, Conteúdo, Quiz, Pergunta e Alternativa, Progresso_Conteúdo, Resultado do Quiz.

---

# 🗺️ Estrutura do projeto (rascunho), vou corrigir posteriormente.

                         INTERNET
                            │
                          HTTPS
                            │
                            ▼
                  ┌──────────────────┐
                  │   NAVEGADOR WEB  │
                  │                  │
                  │ HTML             │
                  │ CSS              │
                  │ Bootstrap        │
                  │ JavaScript       │
                  └────────┬─────────┘
                           │
                           │ HTTP/HTTPS
                           ▼
              ┌───────────────────────────┐
              │          DJANGO           │
              │                           │
              │ URLs / Routing            │
              │ Views                     │
              │ Forms                     │
              │ Auth                      │
              │ Regras de negócio         │
              │ Templates                 │
              │ Django ORM                │
              └────────────┬──────────────┘
                           │
                           │ SQL / conexão BD
                           ▼
              ┌───────────────────────────┐
              │       POSTGRESQL          │
              │                           │
              │ Usuários                  │
              │ Conteúdos                 │
              │ Categorias                │
              │ Quizzes                   │
              │ Perguntas                 │
              │ Alternativas              │
              │ Progresso                 │
              │ Resultados                │
              └───────────────────────────┘


---


## 🚀 Como rodar o projeto (passo a passo)

Abra o terminal e execute os comandos abaixo:

### 1. Eu vou editar isso nos próximos dias... e definir as coisas. Hoje foi um dia horrível para mim. 
