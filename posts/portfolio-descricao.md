# Descrição para Portfólio

> Texto pronto para colar no seu portfólio. Há uma versão curta (cards/listas)
> e uma versão completa (página de projeto). Ajuste os links conforme necessário.

---

## 🏷️ Versão curta (para card de projeto)

**Cypress — Automação de Testes E2E (Projeto Didático)**

Projeto de automação de testes end-to-end com Cypress, estruturado como material
de estudo e base para conteúdos sobre o framework. Cada conceito — locators,
ações, asserções, fixtures, interceptação de rede e comandos customizados — é
demonstrado em um spec comentado e executável. Suíte com 24 testes, 100% verde.

`Cypress` · `JavaScript` · `Node.js` · `E2E Testing` · `QA`

---

## 📄 Versão completa (para página de projeto)

### Cypress — Automação de Testes E2E

#### Visão geral
Projeto de automação de testes end-to-end (E2E) construído com **Cypress**, com
foco em boas práticas e clareza didática. Mais do que uma suíte de testes, o
repositório é organizado como uma **trilha de aprendizado**: cada conceito do
framework é isolado em um arquivo de teste comentado, executável e independente,
servindo de referência tanto para estudo quanto para a produção de conteúdo
técnico (blog e vídeos).

#### Objetivo
Demonstrar domínio do Cypress e dos fundamentos de automação de testes,
evidenciando a capacidade de escrever testes legíveis, estáveis e de fácil
manutenção — e de comunicar esse conhecimento de forma estruturada.

#### O que foi implementado
- **Arquitetura de projeto** organizada (configuração, specs, fixtures e camada
  de suporte com comandos customizados).
- **7 suítes temáticas**, uma por conceito:
  - Anatomia de um teste (`describe`, `it`, hooks)
  - **Locators / seletores** — com a ordem de preferência recomendada e o porquê
    de evitar seletores frágeis
  - Ações e interações (`type`, `click`, `check`, `select`, `clear`)
  - Asserções implícitas e explícitas, com retentabilidade automática
  - **Fixtures** e testes orientados a dados (data-driven)
  - **Interceptação de rede** com `cy.intercept` (spy e stub)
  - **Comandos customizados** e a estratégia `data-cy`
- **Comandos customizados** reutilizáveis (`cy.getByData`, `cy.login`,
  `cy.preencher`) para reduzir duplicação e aumentar a legibilidade.
- **Gravação de vídeo** das execuções para documentação e divulgação.

#### Competências demonstradas
- Escrita de testes E2E claros e de baixa fragilidade
- Estratégia de **locators** resistente a refatorações de UI
- Uso de fixtures e abordagem **data-driven**
- **Mock e spy** de requisições HTTP com `cy.intercept`
- Criação de **custom commands** e organização da camada de suporte
- Configuração de ambiente (baseUrl, timeouts, viewport, vídeo)
- Documentação técnica e comunicação do conhecimento

#### Stack & ferramentas
`Cypress` · `JavaScript (ES6+)` · `Node.js` · `npm` · `Git/GitHub`

#### Resultados
- **24 testes** distribuídos em **7 specs**, **100% aprovados**
- Execução rápida e determinística (sem dependência de backend real)
- Estrutura replicável e documentada, pronta para evoluir com novos conceitos

#### Links
- Repositório: https://github.com/Diogomes/cypress
- Documentação do Cypress: https://docs.cypress.io
