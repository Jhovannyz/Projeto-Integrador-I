# Relatório de Retrospectiva – Grêmio Digital

Data: 24/06/2026

Equipe: Fred Gabriel, Giovani Silva, Lucas de Jesus, Gustavo Barbosa, Guilherme Krinski

Projeto: Grêmio Digital — Plataforma web para gestão do Grêmio Estudantil

Escola Parceira: CEM Paulo Freire

---

## 1. Aprendizados

- **Documentar antes de executar funciona.** Passar o semestre inteiro planejando antes de codar parece contraditório, mas nos mostrou que chegar no PI II com backlog completo, arquitetura definida e protótipo validado é muito mais valioso do que ter código pela metade sem direção clara.

- **Validação com usuário real muda tudo.** Toda vez que levamos o protótipo para o Grêmio do CEM Paulo Freire, voltamos com insights que a equipe jamais teria sozinha. O banner de votação ativa e os textos de apoio nas funcionalidades, duas das melhorias mais impactantes, vieram diretamente do feedback da escola, não de suposição nossa.

- **Rastreabilidade é mais importante do que parece.** Manter os mesmos IDs (RF01, US01, RNF01) em todos os documentos, do Documento de Requisitos ao Backlog, do Backlog ao GitHub Projects, fez com que qualquer membro da equipe conseguisse entender o estado do projeto sem precisar perguntar nada a ninguém.

- **Pair Programming reduz retrabalho.** A revisão cruzada entre Driver e Navigator na Sprint 2 pegou inconsistências que passariam despercebidas em revisões individuais. É uma prática que agrega muito mais valor do que parece no começo.

- **Decisões técnicas precisam ser tomadas e registradas juntas.** A definição da stack só foi formalizada na Sprint 2, e a falta de um padrão de nomenclatura combinado antes gerou retrabalho. Ficou claro que esse tipo de decisão precisa acontecer antes de qualquer sprint de desenvolvimento começar.

- **Scrum funciona mesmo sem código.** Aplicar Daily Scrum, Sprint Planning, Kanban e Retrospectiva em um semestre de documentação mostrou que a metodologia é sobre organização e colaboração, não sobre tecnologia.

---

## 2. Técnica Start / Stop / Continue

### 🟢 Start — Começar a fazer

- Validar com usuários reais desde as primeiras sprints, sem esperar o refinamento.
- Enviar formulários de feedback com pelo menos duas semanas de antecedência e acompanhar ativamente.
- Definir stack, padrões de código e nomenclatura antes de qualquer sprint de desenvolvimento.
- Criar a issue no GitHub antes de executar qualquer tarefa, não depois.
- Gravar demos parciais ao final de cada sprint para mostrar a evolução incremental.

### 🔴 Stop — Parar de fazer

- Deixar issues com descrições incompletas para detalhar depois, gera retrabalho e perda de contexto.
- Combinar padrões de nomenclatura no meio da sprint, quando o desenvolvimento já começou.
- Acumular documentação para produzir perto dos prazos, registrar decisões no dia em que acontecem.
- Depender exclusivamente de Free Tier sem mapear os limites e alternativas de cada ferramenta.

### 🔵 Continue — Continuar fazendo

- Pair Programming com papéis definidos de Driver e Navigator em tarefas críticas.
- Rastreabilidade entre todos os artefatos com IDs únicos e consistentes.
- Daily Scrum semanal via Discord.
- GitHub Projects atualizado com colunas, labels MoSCoW, assignees e estimativas.
- Validações regulares com a escola parceira ao longo de todo o desenvolvimento.
- Conventional Commits (`feat:`, `fix:`, `docs:`, `refactor:`) para manter o histórico organizado.

---

## 3. Registros das Sprints

### Sprint 1 — Planejamento e Documentação Base
- **Foco:** Definição do problema e requisitos base.
- **Principais entregas:** Plano de Projeto, Documento de Visão, Documento 5W2H, Documento de Requisitos (RF01–RF05 e RNF01–RNF05), Backlog do Produto com 20 histórias priorizadas por MoSCoW, Sprint Planning e Daily Scrum registrados no GitHub.
- **Pontos fortes:** Documentação consistente com rastreabilidade entre artefatos; protótipo navegável validado com a escola parceira desde o início.
- **Pontos fracos:** Definição técnica não formalizada nessa sprint; padrões de nomenclatura não combinados previamente geraram retrabalho na Sprint 2.

### Sprint 2 — Implementação Incremental
- **Foco:** Arquitetura e prototipagem de alta fidelidade.
- **Principais entregas:** Documento Técnico com stack e arquitetura MVC; 4 histórias implementadas no protótipo (US07, US08, US09, US12); Pair Programming em 4 pares; checklist da sprint registrado em `docs/sprint2/checklist-sprint2.md`.
- **Pontos fortes:** Pair Programming funcionou bem; decisões técnicas registradas com justificativas e alternativas descartadas.
- **Pontos fracos:** Padronização de nomenclatura precisou ser alinhada no início da sprint, atrasando o começo; algumas issues precisaram ser ajustadas depois de criadas.

### Sprint de Refinamento — Validação e Ajustes
- **Foco:** Usabilidade e ajustes finos.
- **Principais entregas:** Teste de Usabilidade com roteiro estruturado; Relatório de Análise Crítica; 5 ajustes implementados no protótipo (RF-A1 a RF-A5); Documento de Refino em `docs/usabilidade/refino-da-solucao.md`; Business Model Canvas; Diagramas UML (Casos de Uso e Classes).
- **Pontos fortes:** Feedback real da escola parceira incorporado diretamente nos ajustes; rastreabilidade mantida com issues para cada melhoria realizada.
- **Pontos fracos:** Formulário de usabilidade não respondido por todos os membros do Grêmio a tempo; demo em vídeo ainda pendente de gravação e publicação.

---

## 4. Análise Crítica

- **Qualidade da solução:** Adequada para o estágio atual do projeto. O protótipo navegável cobre os fluxos principais do aluno e do administrador, foi validado com usuários reais e passou por um ciclo completo de refinamento baseado em feedback. A base técnica está documentada e pronta para o desenvolvimento no PI II.

- **Eficiência do processo:** Alta. A equipe conseguiu produzir uma documentação completa e consistente em um semestre, aplicando metodologia ágil (Scrum) de forma adaptada ao contexto acadêmico. O uso do GitHub Projects como quadro Kanban e o registro sistemático de todas as decisões foram diferenciais importantes para manter a organização ao longo das sprints.

- **Propostas de melhoria para os próximos ciclos:**
  - Iniciar o PI II com uma Sprint 0 dedicada exclusivamente à configuração do ambiente de desenvolvimento, definição de padrões e criação da estrutura de pastas do repositório.
  - Estabelecer um ciclo fixo de validação com a escola parceira a cada duas sprints, com agendamento antecipado.
  - Criar um documento de Definição de Pronto (DoD) formal e visível para toda a equipe desde o início do desenvolvimento.
  - Implementar testes automatizados desde as primeiras funcionalidades, evitando acúmulo de dívida técnica.

---

## 5. Conclusão

O Projeto Integrador I foi um semestre de construção de fundações, e fundações sólidas fazem toda a diferença quando o desenvolvimento real começa. A equipe entregou um conjunto completo de documentação, um protótipo validado com usuários reais e uma base técnica clara para os próximos semestres.

Mais do que os artefatos entregues, o aprendizado mais importante foi entender que software bem feito começa muito antes do primeiro linha de código: começa no entendimento do problema, na escuta ativa do usuário, na organização do time e no registro cuidadoso de cada decisão tomada.

O Grêmio Digital ainda tem muito pela frente, o desenvolvimento no PI II e implantação real no PI III. Mas chegamos nessa etapa com algo que muitos projetos não têm: clareza sobre o que construir, para quem construir e por que construir.
