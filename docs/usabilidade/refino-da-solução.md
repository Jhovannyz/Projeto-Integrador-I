# Documento de Refino da Solução

Data: 17/06/2026

Equipe: Grêmio Digital

Projeto: Grêmio Digital — Protótipo (Figma)

---

## 1. Critérios de Validação

- **Usabilidade:** Parcial — o fluxo de votação foi compreendido com facilidade, mas o usuário sentiu falta de textos explicativos sobre o que cada funcionalidade faz, e não percebeu de imediato que havia uma pauta de votação ativa.
- **Funcionalidade:** Sim — o fluxo de voto (seleção de opção, confirmação e mensagem de sucesso) funcionou conforme esperado, sem erros relatados.
- **Desempenho:** Sim — não houve relatos de lentidão ou demora entre as telas durante a navegação no protótipo.
- **Clareza técnica:** Sim — arquitetura, stack e padrões de código já estão documentados no Documento Técnico da Sprint 2, servindo de base sólida para a implementação.

---

## 2. Ajustes Realizados

- Adição de textos de apoio (placeholders e legendas explicativas) explicando a função de cada seção principal do sistema (Mural, Votação, Painel Admin), reduzindo a curva de entendimento inicial do usuário.
- Criação de um destaque visual (banner "Votação Ativa") no topo do mural, exibido sempre que houver uma pauta em aberto, resolvendo o problema de baixa visibilidade identificado no teste.
- Modal adicionado na tela de ouvidoria, em formato de e-mail, mostrando histórico de conversas entre a ouvidoria e o aluno.
- Inclusão de uma notificação visual (badge numérico) no mural, alertando os alunos sobre novas pautas ou avisos publicados sem a necessidade de navegação ativa.
- Uma melhor visualização de quem compõe as chapas estudantis, aparecendo os integrantes de cada chapa e suas propostas para a escola ao clicar em "Eleição para Presidente do Grêmio 2026" por exemplo.

---

## 3. Versão Refinada

- Link do protótipo atualizado: https://sharp-set-73507180.figma.site/login
- A versão atualizada do protótipo apresenta uma usabilidade mais polida, com fluxos autoexplicativos que reduzem a curva de aprendizado. O destaque visual para as votações ativas resolveu o principal ponto de atrito apontado nos testes, enquanto as melhorias na ouvidoria agregaram maior valor funcional à comunicação entre alunos e o Grêmio.

---

## 4. Análise Crítica

- **Pontos fortes da versão refinada:** identidade visual consistente e bem avaliada, fluxo de votação intuitivo e tela de confirmação que transmite segurança ao usuário — todos esses pontos foram mantidos e reforçados nesta versão.
- **Pontos a melhorar:** ainda é necessário validar com mais usuários se os textos de apoio adicionados realmente resolvem a dificuldade de compreensão inicial; o onboarding pode ser simplificado ainda mais nas próximas iterações.
- **Próximos passos:** implementar esses ajustes em código durante o Projeto Integrador II e realizar uma nova rodada de testes de usabilidade com mais alunos e representantes do Grêmio.

---

## 5. Conclusão

Nossa equipe concluiu que a solução apresenta um nível de qualidade satisfatório, tendo evoluído significativamente de um rascunho funcional para um protótipo refinado e centrado no usuário. Os ajustes realizados endereçaram diretamente as dores levantadas na validação, alinhando o produto às expectativas de modernização e transparência exigidas pelo Grêmio Estudantil. 
