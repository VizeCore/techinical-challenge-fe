**Desafio Técnico - Front-End (React + Vite)**

Seja bem-vindo(a), candidato(a)! Este desafio avalia suas habilidades na construção de uma aplicação dinâmica usando **React** com **Vite** como bundler. Demonstre conhecimento em busca de dados, roteamento, componentização, organização de código e boas práticas de performance.

* * *

### Cenário

Você vai construir um site que consome conteúdo do **dev.to**. Os usuários devem poder:

- Navegar por artigos recentes de diferentes comunidades.
- Pesquisar artigos por **título**, **tags** e **nome de usuário**.
- Filtrar artigos por **estado** (published, draft, etc.).
- Visualizar um artigo individual com formatação completa e informações do autor.
- Usar o site confortavelmente em **qualquer tamanho de tela**.

* * *

### Pontos Extras (opcionais, mas contam muito)

| Tema | Sugestão |
| --- | --- |
| **Renderização no servidor (SSR)** | Use algo como *vite-plugin-ssr* ou *react-ssr-vite* para melhorar SEO e carregamento inicial. |
| **Gerenciamento de cache** | React Query, TanStack Query ou SWR. |
| **Paginação** | Infinit scroll ou botões “Próximo / Anterior”. |
| **Testes E2E** | Cypress ou Playwright com pelo menos um fluxo de sucesso. |

<button class="bg-token-bg-primary hover:bg-token-bg-tertiary text-token-text-secondary my-1 rounded-sm p-1 transition-opacity group-[:not(:hover):not(:focus-within)]:pointer-events-none group-[:not(:hover):not(:focus-within)]:opacity-0"><svg width="24" height="24" viewbox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-md-heavy"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg></button>

* * *

### Requisitos Técnicos

1. **React 18 + Vite** para o front-end.
2. Roteamento com **React Router v6** (ou outra solução que preferir).
3. Qualquer biblioteca de UI (MUI, Mantine, Shadcn, Bootstrap) **ou** CSS-in-JS (Styled-Components, Emotion).
4. Pode adicionar outras dependências; documente no README o *porquê*.
5. Testes unitários com **Vitest + Testing-Library**.

* * *

### Instruções de Envio

1. Faça um *fork* ou crie um repositório GitHub público.
2. Inclua um **README** explicando:

    - Sua arquitetura, principais decisões e trade-offs.
    - Como rodar em modo dev, build de produção, testes e lint.
    - Quais requisitos/pontos extras foram entregues.
3. Mantenha o código limpo, documentado e organizado.

* * *

### Critérios de Avaliação

| Peso | Critério | O que observaremos |
| --- | --- | --- |
| ★★★ | **Funcionalidade** | Se todos os requisitos (e extras) funcionam sem erros. |
| ★★☆ | **Qualidade do Código** | Clareza, modularização, tipagem (TS opcional), padrão de commits. |
| ★★☆ | **Performance** | Boa pontuação no Lighthouse, lazy-loading, code-splitting. |
| ★★☆ | **Testes** | Cobertura mínima dos componentes críticos + E2E funcional. |
| ★★☆ | **Documentação** | README esclarecedor e processo de setup simples. |

<button class="bg-token-bg-primary hover:bg-token-bg-tertiary text-token-text-secondary my-1 rounded-sm p-1 transition-opacity group-[:not(:hover):not(:focus-within)]:pointer-events-none group-[:not(:hover):not(:focus-within)]:opacity-0"><svg width="24" height="24" viewbox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-md-heavy"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg></button>

* * *

### Prazo

Entregue dentro de **2 dias corridos** após receber este enunciado.

* * *

### Observações Adicionais

- API oficial: [https://developers.forem.com/api](https://developers.forem.com/api)
- Sinta-se livre para criar mockups ou seguir guias de design.
- Qualquer dúvida durante o desafio, pergunte!

Boa sorte e bom código ✨
