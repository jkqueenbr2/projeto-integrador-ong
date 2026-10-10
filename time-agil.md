# Organização do time ágil — Amor de Patas

## Papéis do time
- **Product Owner:** [NOME]. Organiza e prioriza funcionalidades conforme as necessidades da ONG; aceita ou devolve entregas.
- **Scrum Master:** [NOME]. Facilita alinhamentos, acompanha impedimentos e ajuda a respeitar o limite de WIP.
- **Developers:** [NOMES]. Detalham issues, implementam funcionalidades, testam e documentam alterações.

## Definition of Ready
Uma issue só entra em DOING quando:
- [ ] Apresenta história de usuário ou descrição clara do defeito.
- [ ] Possui critérios de aceitação verificáveis (ou resultado esperado, para bugs).
- [ ] Tem prioridade MoSCoW registrada.
- [ ] Dependências e informações necessárias foram identificadas.
- [ ] Existe integrante responsável e capacidade dentro do limite de WIP.

## Definition of Done
Uma issue só entra em DONE quando:
- [ ] Critérios de aceitação da issue atendidos
- [ ] Alterações revisadas por outro integrante (quando houver outro integrante disponível)
- [ ] Testes ou verificações pertinentes executados e registrados
- [ ] Documentação atualizada quando necessário
- [ ] Nenhum erro conhecido bloqueante para a entrega
- [ ] Issue vinculada e quadro atualizado

## Matriz de stakeholders
| Poder | Interesse | Stakeholder | Estratégia |
|---|---|---|---|
| Alto | Alto | Coordenação da ONG | Gerenciar de perto: validação quinzenal de requisitos e entregas |
| Alto | Baixo | Professor orientador | Manter satisfeito: comunicar marcos, riscos e evidências acadêmicas |
| Baixo | Alto | Voluntários e adotantes | Manter informados: demonstrar protótipos e colher feedback |
| Baixo | Baixo | Público visitante | Monitorar: observar dúvidas e uso das páginas públicas |

> Classificação inicial proposta; confirmar com a matriz produzida pelo grupo na Aula 11.

## Plano de comunicação
| Comunicação | Destinatários | Canal | Frequência |
|---|---|---|---|
| Alinhamento de tarefas e bloqueios | Time | Grupo de mensagens | Dias úteis, quando houver trabalho |
| Revisão do quadro e prioridades | Time e Product Owner | GitHub Projects + reunião | Semanal |
| Demonstração do incremento | Coordenação da ONG | Reunião online ou presencial | Quinzenal |
| Relatório de progresso e riscos | Professor | AVA e GitHub | A cada entrega do ciclo |
| Dúvidas sobre funcionalidades | Voluntários consultados | Formulário ou mensagem | A cada validação de protótipo |

## Quadro e limite de WIP
O GitHub Projects utiliza as colunas **TO-DO**, **DOING** e **DONE**. O limite proposto para **DOING é 2 issues simultâneas**, adequado a um time pequeno de aproximadamente 2 a 4 pessoas, para reduzir alternância de contexto e incentivar conclusão antes do início de novas tarefas. Se a equipe tiver outro tamanho, revisar e justificar o limite. Uma issue só entra em DOING se atender à Definition of Ready; só vai para DONE se atender à Definition of Done.

## Declaração de uso de IA
Foi utilizado **ChatGPT (OpenAI)** para elaborar uma proposta inicial de estrutura do repositório, templates, backlog e documentação do processo ágil. **Antes da entrega, o grupo deve revisar e adaptar** o escopo, os nomes, os papéis, a matriz de stakeholders, o limite de WIP e as evidências de execução ao trabalho realmente realizado. Não declarar testes, revisões, commits ou validações que não tenham ocorrido.
