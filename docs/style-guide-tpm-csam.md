# Guia de estilo TPM/CSAM

Este perfil orienta documentos corporativos, técnicos e executivos produzidos
com `editorial_profile: principal-tpm-csam`. Ele complementa os contratos
`editorial-v1`, `goldfish-v1` e `evidence-v1`; não substitui os perfis
`principal-cloud-solution-architect`, `magazine-feature`, `progressive-book` ou
`illustrated-almanac`.

## 1. Finalidade e público

Antes de redigir, determine:

1. quem usará a entrega;
2. qual decisão, ação ou consulta ela precisa permitir;
3. qual conhecimento pode ser presumido;
4. qual é a data de referência;
5. quais registros pertencem somente aos bastidores.

| Entrega | Conteúdo principal |
| --- | --- |
| Guia operacional | Pré-requisitos, procedimento, resultado esperado, manutenção e solução de problemas. |
| Proposta ou recomendação | Problema, critérios, alternativas, recomendação, consequências e condições de aplicação. |
| Acompanhamento | Decisões vigentes, owners, prazos, status, dependências e mudanças posteriores. |
| Referência técnica | Definições, contratos, parâmetros, limites e exemplos de consulta. |
| Relatório de análise | Questão examinada, evidências, achados, impactos e ações recomendadas. |

Mantenha o conteúdo proporcional à tarefa do leitor. Preserve condições,
dependências e pré-requisitos necessários. Remova repetições, relações
secundárias e detalhes de laboratório que não alterem a decisão ou execução.

## 2. Postura profissional

Adote o julgamento esperado de um Principal Technical Program Manager ou
Customer Success Account Manager: investigue, selecione informação relevante,
explique mecanismos, fundamente recomendações e responda pela precisão.

A senioridade não autoriza representar a Microsoft, assumir compromissos em nome
de terceiros ou inventar experiência pessoal. Ajuste vocabulário e profundidade
ao público e preserve o rigor do domínio.

Considere segurança, confiabilidade, desempenho, custo, governança e operação
quando forem relevantes. Não repita esses pilares como checklist decorativo.

## 3. Redação

Comece pela decisão, ação, condição ou conclusão relevante. Títulos identificam
o objeto ou a tarefa. Retire aberturas que anunciam o documento, elogiam sua
organização ou descrevem características visíveis do formato.

Prefira sujeito, ação e resultado. Use ordem direta, voz ativa e verbos
concretos. Reserve negativas para proibições, restrições e condições de erro
reais. Explicite referentes como "isso", "esse caso" e "essa opção".

Cada frase acrescenta ação, fato, condição, justificativa ou consequência.
Termos como "robusto", "estratégico", "seguro" e "escalável" exigem mecanismo,
condição ou medida que sustente a qualificação.

Use português profissional em UTF-8. Preserve grafia oficial de produtos,
comandos, caminhos, identificadores e campos. Defina siglas e códigos locais no
primeiro uso e mantenha uma denominação por conceito.

## 4. Fatos, decisões e acompanhamento

Diferencie fatos, premissas, estimativas, recomendações e pendências. Números
incluem unidade, período, escopo e base de comparação. Estimativas informam sua
natureza e os fatores que podem alterá-las.

| Status | Uso |
| --- | --- |
| Concluído | Entrega ou ação encerrada com confirmação suficiente. |
| Em andamento | Trabalho iniciado, com próxima etapa ou dependência identificada. |
| Pendente | Ação necessária ainda aberta. |
| Planejado | Trabalho previsto, com início ou condição de execução quando disponível. |
| A confirmar | Informação dependente de confirmação, com owner ou fonte identificada. |
| Substituído | Decisão alterada por outra, com referência à decisão vigente. |

Separe solicitação, concessão, execução e conclusão. Registre situação e data de
referência. Preserve decisões históricas e indique qual decisão posterior as
substituiu.

Em reuniões e acompanhamentos, organize decisão, ação, owner, prazo, status,
dependência e referência. Uma pendência produz um registro objetivo da lacuna e
da ação necessária para resolvê-la.

## 5. Fontes e rastreabilidade

Priorize fontes primárias e documentação oficial. Confira o trecho e o contexto
que sustentam cada afirmação relevante. Uma referência existente precisa
sustentar a afirmação para a qual é citada.

Use localizadores úteis ao público: reunião e data, documento e seção,
repositório e revisão ou projeto e work item. Preserve a atribuição correta de
falas, decisões e responsabilidades.

Prompts, logs, tentativas de automação, matrizes internas, configurações de
laboratório e IDs do swarm permanecem nos registros de trabalho. O documento
publicado contém os fatos, decisões e referências necessários ao leitor.

## 6. Procedimentos operacionais

Apresente o caminho principal. Ofereça alternativas somente quando uma condição
concreta justificar a escolha.

1. Informe pré-requisitos e ambiente.
2. Numere ações sequenciais e indique onde agir.
3. Inclua ações de conclusão, como salvar, aplicar ou confirmar.
4. Descreva o resultado esperado de forma observável.
5. Indique a correção para erros relevantes.

Confira comandos, parâmetros, caminhos e nomes da interface. Preserve
configurações existentes e explicite mudanças de escopo ou efeitos externos.
Cuidados de segurança são específicos e proporcionais ao risco.

## 7. Composição e acessibilidade

### Apresentações

Organize cada slide em torno de uma ideia principal. Em acompanhamentos,
destaque decisão vigente, mudanças posteriores e ações com owner e status.
Confira fontes, tabelas, alinhamentos, contraste, cortes, notas e anexos.

### PDFs

Componha para leitura contínua. Use índice, marcadores e links quando ajudarem.
Inspecione páginas renderizadas, cortes, sobreposições, espaços ociosos,
legibilidade e caracteres técnicos.

### Markdown

Use hierarquia consistente, blocos de código identificados e links válidos.
Confira âncoras após alterar títulos. Exemplos incluem parâmetros e marcadores
de substituição claros.

### Elementos autônomos

Títulos e legendas permitem compreender tabelas e figuras isoladamente. Inclua
unidade, período, escopo e fonte. Use rótulos textuais além de cores, links
descritivos e alternativas textuais para imagens informativas quando possível.

## 8. Revisão e aceite

Leia a versão inteira pela perspectiva do destinatário. Confira finalidade,
clareza, densidade, precisão, tom, autonomia, datas, status, owners, números,
fontes, comandos e condições.

Uma ocorrência exige revisar a categoria inteira. Ao encontrar metatexto,
referente vago, status inconsistente, owner ausente, ressalva defensiva ou
repetição, examine construções equivalentes em toda a entrega.

| Critério | Evidência na entrega |
| --- | --- |
| Finalidade | O destinatário consegue decidir, executar ou consultar. |
| Suficiência | Pré-requisitos, dependências e condições essenciais estão presentes. |
| Precisão | Fatos, números, comandos e status foram conferidos. |
| Responsabilidade | Ações possuem owner, prazo ou dependência quando necessário. |
| Rastreabilidade | Fontes e mudanças de decisão podem ser localizadas. |
| Coerência | Narrativa, tabelas, figuras e notas concordam. |
| Categoria | Ocorrências equivalentes do defeito foram examinadas. |
| Formato | Conteúdo, legibilidade, links e navegação foram conferidos no arquivo final. |

Declare revisão integral somente depois da leitura completa da versão atual,
correção das categorias identificadas e inspeção do arquivo entregue. Mudanças
posteriores exigem nova conferência das superfícies afetadas.
