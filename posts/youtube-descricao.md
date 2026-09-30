# Descrição para o YouTube

> Copie o bloco abaixo direto para a descrição do vídeo. Ajuste os timestamps
> do capítulo conforme a edição final e troque os links das suas redes.

---

🌿 Aprenda automação de testes com Cypress do zero! Neste vídeo eu mostro a estrutura completa de um projeto Cypress e explico, na prática, como escrever testes, escolher bons locators (seletores) e aplicar as boas práticas do framework — tudo rodando de verdade no navegador.

O projeto é a base de uma série de conteúdos sobre Cypress: cada conceito vira um arquivo de teste comentado, na ordem em que apresento aqui. Os exemplos rodam contra o Kitchen Sink oficial (example.cypress.io), então você consegue reproduzir tudo sem precisar subir nenhuma aplicação.

🔗 CÓDIGO NO GITHUB
https://github.com/Diogomes/cypress

⚙️ COMO RODAR
npm install
npm run cy:open   → modo interativo (interface do Cypress)
npm run cy:run    → roda todos os testes no terminal

📚 O QUE VOCÊ VAI APRENDER
✅ Como estruturar um projeto Cypress do zero
✅ A anatomia de um teste: describe, it e os comandos cy.*
✅ A regra de ouro dos LOCATORS (e como não escrever testes frágeis)
✅ Ações: digitar, clicar, marcar checkbox e selecionar
✅ Asserções e por que o Cypress quase nunca precisa de "sleep"
✅ Fixtures e testes orientados a dados (data-driven)
✅ Interceptar requisições de rede com cy.intercept (spy e stub)
✅ Comandos customizados e a estratégia data-cy

⏱️ CAPÍTULOS
00:00 Introdução
00:30 Estrutura do projeto
01:30 #1 Primeiro teste (describe / it / hooks)
03:00 #2 Locators: como encontrar elementos
05:00 #3 Ações e interações
07:00 #4 Asserções
09:00 #5 Fixtures e dados
11:00 #6 Network com cy.intercept
13:00 #7 Comandos customizados
15:00 Rodando a suíte completa
16:00 Conclusão e próximos passos

🎯 A REGRA DE OURO DOS LOCATORS
1. [data-cy="..."] → atributo dedicado a teste (MELHOR)
2. Texto visível → cy.contains('Salvar')
3. Atributos semânticos → role, aria-label, name
4. Classes / IDs de CSS → evite (mudam com o estilo)
5. Estrutura do DOM → o pior, quebra a qualquer refatoração

🔗 LINKS ÚTEIS
Documentação oficial: https://docs.cypress.io
Boas práticas: https://docs.cypress.io/guides/references/best-practices
Kitchen Sink: https://example.cypress.io

💬 Gostou? Deixa o like, se inscreve no canal e comenta qual conceito de Cypress você quer ver no próximo vídeo!

#cypress #automacaodetestes #qa #testing #javascript #desenvolvimento #programacao #testesautomatizados #cypressio #qualidadedesoftware
