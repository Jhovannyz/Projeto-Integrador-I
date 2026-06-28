# Relatório de Conclusão — Projeto Integrador I

Data: 24/06/2026

Equipe: Fred Gabriel, Giovani Silva, Lucas de Jesus, Gustavo Barbosa, Guilherme Krinski

Projeto: Grêmio Digital

Escola Parceira: CEM Paulo Freire

---

## 1. Sobre o Projeto

O Grêmio Digital nasceu de uma observação simples feita durante a imersão na escola parceira: alunos com smartphone na mão, mas o Grêmio ainda dependendo de cartaz de papel e grupos de WhatsApp para se comunicar, e de cédulas de papel dobradas numa caixinha para realizar eleições.

A proposta foi direta: criar uma plataforma web leve, acessada via QR Code pelo navegador do celular, que centralizasse a comunicação oficial do Grêmio e tornasse as votações seguras, transparentes e auditáveis. Sem instalar app. Sem cadastro complicado. Só o número de matrícula e pronto.

Ao longo do Projeto Integrador I, a equipe dedicou o semestre inteiro ao planejamento, documentação e validação dessa solução, construindo a fundação sobre a qual o sistema será desenvolvido nos próximos semestres.

---

## 2. O que Foi Entregue

Durante o semestre, a equipe produziu uma documentação completa e consistente, com rastreabilidade entre todos os artefatos:

**Documentação do Produto:**
- Plano de Projeto com cronograma, equipe, riscos e marcos
- Documento de Visão com contexto, problema, solução e proposta de valor
- Documento 5W2H
- Documento de Requisitos com 5 Requisitos Funcionais e 5 Requisitos Não Funcionais especificados por Histórias de Usuário
- Backlog do Produto com 21 histórias de usuário priorizadas por MoSCoW
- Documentação Geral do Projeto
- Business Model Canvas
- Diagramas UML: Casos de Uso e Classes

**Processo e Gestão:**
- GitHub Projects com Kanban completo e atualizado ao longo de todas as sprints
- Sprint Planning documentado nas Discussions do GitHub
- Daily Scrum registrada em `docs/daily-scrum-20-05-2026.md`
- Documento Técnico da Sprint 2 com stack, arquitetura MVC e padrões de código
- Checklist da Sprint 2 em `docs/sprint2/checklist-sprint2.md`

**Validação e Refinamento:**
- Roteiro de Teste de Usabilidade em `docs/usabilidade/roteiro-teste-usabilidade.md`
- Relatório de Análise Crítica em `docs/usabilidade/relatorio-analise-critica.md`
- Documento de Refino em `docs/usabilidade/refino-da-solucao.md`
- 5 ajustes implementados no protótipo (RF-A1 a RF-A5) com base em feedback real
- Relatório de Retrospectiva em `docs/retrospectiva.md`

**Produto:**
- Protótipo navegável completo no Figma, cobrindo os fluxos do aluno e do administrador
- Protótipo validado com representantes do Grêmio Estudantil do CEM Paulo Freire
- Demo em vídeo do fluxo principal do MVP

---

## 3. O que Aprendemos

Esse semestre ensinou que construir software de qualidade começa muito antes do primeiro linha de código. Alguns aprendizados que a equipe leva para os próximos semestres:

**Sobre o produto:**
Validar com usuários reais desde o início faz toda a diferença. As melhorias mais impactantes que fizemos no protótipo o banner de votação ativa, os textos de apoio e a reestruturação da ouvidoria não vieram da nossa cabeça. Vieram de conversar com quem vai usar o sistema de verdade.

**Sobre o processo:**
Aplicar Scrum em um semestre de documentação pareceu estranho no começo, mas funcionou. Ter sprints definidas, backlog priorizado, daily scrums e retrospectiva fez com que a equipe sempre soubesse o que estava fazendo, por que estava fazendo e o que vinha a seguir. A metodologia não é sobre código, é sobre organização e colaboração.

**Sobre a equipe:**
Pair Programming mostrou que duas cabeças pensam melhor que uma, e que a revisão contínua do trabalho do colega evita problemas que a revisão individual nunca pegaria. A divisão clara de papéis (PO, SM, Developers) também foi essencial para que ninguém ficasse sobrecarregado e para que as decisões tivessem um responsável claro.

**Sobre documentação:**
Rastreabilidade não é burocracia. Manter os mesmos IDs em todos os artefatos e registrar cada decisão no momento em que foi tomada fez com que qualquer membro da equipe, ou qualquer pessoa de fora, conseguisse entender o estado do projeto sem precisar perguntar nada a ninguém.

**O que funcionou bem:**
- Abordagem Mobile-First: Focar no navegador do celular foi a decisão mais estratégica, garantindo que a plataforma seja acessível de qualquer dispositivo.
- Validação Constante: Trazer o feedback do Grêmio para dentro do Figma evitou que desenvolvêssemos funções inúteis.

**O que poderia ser diferente:**
- Gestão de Tempo Inicial: No início da Sprint 1, subestimamos o tempo de escrita dos requisitos. Se pudéssemos reiniciar, teríamos começado o detalhamento das Histórias de Usuário uma semana antes para evitar sobrecarga no final da sprint.
- Exploração de Tecnologias: Poderíamos ter testado ferramentas de prototipagem de baixa fidelidade antes de ir direto para o Figma, o que teria agilizado o processo de ideias inicial.

---

## 4. Estado Atual da Solução

O Grêmio Digital chega ao final do PI I com:

- ✅ Problema identificado e validado com a escola parceira
- ✅ Solução definida, documentada e aprovada
- ✅ Protótipo navegável cobrindo 100% do fluxo do MVP
- ✅ Stack tecnológica definida e justificada
- ✅ Arquitetura documentada e pronta para implementação
- ✅ Backlog priorizado com 21 histórias prontas para o desenvolvimento
- ✅ Base de código e infraestrutura planejadas (React, Node.js, Firebase, Vercel)
- ⏳ Desenvolvimento do código — PI II
- ⏳ Testes com usuários reais e implantação na escola — PI III

---

## 5. Próximos Passos

**PI II — Desenvolvimento:**
O foco será transformar o protótipo em código funcional, implementando as histórias Must Have e Should Have do backlog. A equipe começa o semestre com a vantagem de já ter a arquitetura definida, os padrões de código estabelecidos e o ambiente de desenvolvimento mapeado.

**PI III — Testes e Implantação:**
Após o desenvolvimento, a etapa final será testar o sistema com alunos reais do CEM Paulo Freire, ajustar com base no feedback e fazer o deploy em produção na Vercel. QR Codes serão impressos e instalados nos pontos estratégicos da escola, e o manual do usuário será entregue ao Grêmio Estudantil.

---

## 6. Considerações Finais

O Projeto Integrador I nos mostrou, na prática, o que significa trabalhar em equipe com metodologia, ouvir o usuário com atenção e documentar as decisões com responsabilidade. Mais do que um conjunto de documentos, o que construímos nesse semestre foi um caminho claro, sabemos exatamente o que vai ser construído, para quem, com qual tecnologia e por quê.

O Grêmio Digital não é só um projeto acadêmico. É uma solução real para um problema real, construída por estudantes para estudantes.
