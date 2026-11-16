# Segunda auditoria adversarial — Exercício 3.1

**Assistente 2:** Codex / OpenAI.  
**Estudante:** Rosy Emannuele Moura dos Santos Bomfim.  
**Data:** 16 de novembro de 2026.  
**Objeto:** `B_relatorio_assistente_v2.md`, produzido pelo Gemini / Antigravity CLI, assistente 1.  
**SHA-256 da v2 auditada:** `ef5a5b4db533371b48efc9f8f280bccd81b8f34e3c9a810c993380ea4d45adde`.  
**Referência de confronto:** `B_relatorio_auditoria_v1.md`, achados F01–F19.  
**Serviço preservado:** acesso e permanência na EJA Modular do Ensino Médio da rede estadual de Alagoas, pessoas de 18 anos ou mais, sem escolher uma escola como representante de toda a rede.

## Parecer

A v2 evoluiu de forma verificável: corrigiu a posição das três linhas do blueprint, incorporou a classificação sem comprovante de estudos, distinguiu percursos de ingresso, completou responsabilidades de deferimento e calendário, corrigiu autores e títulos acadêmicos e delimitou a inserção do CadEJA. Entretanto, a declaração de que todos os 19 achados foram corrigidos não corresponde ao corpo do relatório. Há correções parciais, problemas que reaparecem nas tabelas e erros novos.

Esta segunda auditoria reconhece **3 achados atendidos no seu objeto específico — F01, F07 e F17 — e 16 parcialmente atendidos, com pendências ou regressões**. “Atendido” em F07 e F17 significa que o limite de evidência foi adequadamente representado, não que se comprovou a identidade da equipe de TI, a competência executiva da GEGEV ou adesão ao CadEJA. Os ajustes remanescentes estão organizados em **R01–R17**; cada mudança da v3 deverá citar o identificador desta segunda auditoria que a motivou.

Não há nota nesta auditoria. A Parte B precisa da revisão final antes da entrevista que decidirá o blueprint. Não foram produzidas respostas da estudante nem documentos das Partes C e D.

## Procedimento e preservação

Foram lidos integralmente a v2, a auditoria anterior e o README. Houve confronto com fontes primárias na web, reproduções institucionais e extrações oficiais locais. O texto da LDB no Planalto ficou acessível nesta rodada, diferentemente da limitação de acesso registrada na primeira auditoria. A página dinâmica de cadastro de matrícula continuou sem conteúdo textual extraível; isso não demonstra encerramento das inscrições.

Foi conferido que A e a primeira auditoria permanecem iguais às cópias preparadas anteriormente, e que a v1 conserva seu SHA-256 `6f46cf3ba1c8cafa43f3912bdbdf8d8390aff6ce848e12185f05143ab3c30e1c`. A comparação dos arquivos homônimos do contexto 2.1 com a pasta do exercício anterior não encontrou diferenças. A v2 contém aproximadamente 11,3 mil palavras: o mínimo quantitativo foi superado, mas extensão não resolve contradições internas.

Não houve inspeção de escola, entrevista com servidor, acesso autenticado ao SAGEAL ou submissão de cadastro. Os achados abaixo não constituem prova de falhas realmente ocorridas em uma escola específica.

## Verificação de todos os achados da auditoria v1

| Achado anterior | Resultado desta auditoria | Evidência na v2 e encaminhamento |
|---|---|---|
| F01 — Linhas divisórias | **Atendido** | Seção 4 agora posiciona interação entre cidadão/frontstage, visibilidade entre frontstage/backstage e interação interna entre backstage/suporte. A classificação de algumas ações ainda exige o ajuste novo R11. |
| F02 — Percursos de ingresso | **Parcial** | Seção 1.3 distingue quatro percursos, mas infere predominância presencial e encerramento do formulário sem evidência suficiente; o esquema H1–H6 continua linear a partir do portal. Ver R08. |
| F03 — Classificação e documentos | **Parcial** | A bifurcação foi incluída, mas o texto acrescenta CNH ao art. 15, exige foto ao mesmo tempo que admite certidão e omite NIS na lista operacional. A decisão de classificação também precisa de maior precisão. Ver R03–R04. |
| F04 — Responsabilidades | **Parcial** | Foram incluídos deferimento gestor/secretário e calendário Conselho Escolar/Inspeção. Permanecem assinatura conjunta presumida e devolutivas não comprovadas; a classificação demanda participação colegiada. Ver R03–R04 e R09. |
| F05 — Evidências percebidas | **Parcial** | Calendário visível e algumas hipóteses locais foram classificados corretamente; recibo, ata de classificação, mural de concluintes e papel timbrado voltam como evidências presumidas ou mal atribuídas. Ver R09. |
| F06 — Arquitetura de sistemas | **Parcial** | Foram retiradas integração com Receita Federal e fórmulas de repasse. Surgem “sincronização censitária”, “livro eletrônico” e certificação via SEI sem prova específica. Ver R10. |
| F07 — GEGEV e suporte técnico | **Atendido com pendências explícitas** | Seções 1.2 e 4 mantêm competências executivas da GEGEV a confirmar e equipe de TI a identificar. Preservar essas ressalvas; não convertê-las em competências comprovadas. |
| F08 — Reenturmação | **Parcial, com erro novo** | Exceção via GEE e consequências condicionais foram incluídas, mas foi inventada faixa de 30–50 no diurno e o momento da reorganização foi imprecisamente alterado. Ver R05. |
| F09 — Apoios materiais | **Parcial** | Foram retirados horários exatos e parte da causalidade determinista; continuam comparações sobre lanches, “refeições quentes”, alegações de ausência de relatórios e efeitos certos de abandono. Ver R13 e R15. |
| F10 — Busca ativa | **Parcial** | Comunicação interpessoal e contato em três faltas foram recuperados. O fluxo não distingue suficientemente o dever docente do gatilho da coordenação nem identifica como pendência o sistema de prevenção referido na norma de 2026. Ver R12. |
| F11 — Abandono/censo/retorno | **Parcial, com agravamento conceitual** | Foi incluído curso em andamento, mas como possível alternativa ao registro de um estudante que deixou de comparecer, sem distinguir sua situação individual da continuidade da turma. PF-09 mantém esgotamento da busca ativa e barreira de retorno sem prova. Ver R07. |
| F12 — Desfechos modulares | **Parcial** | A regra específica foi citada, mas a narrativa ainda afirma harmonização não demonstrada e aproveitamento integral no retorno; a condição explícita dos quatro módulos/ênfases não foi adequadamente detalhada. Ver R06. |
| F13 — Riscos sem ocorrência comprovada | **Parcial** | Há condições hipotéticas, sobretudo em PF-02/PF-03/PF-04. Persistem efeitos deterministas, reconhecimento institucional presumido e uma cadeia de setas sem causalidade demonstrada. Ver R13. |
| F14 — Lei Delegada nº 48 | **Parcial, com erro novo** | Data do ato e objeto foram corrigidos; a publicação foi indevidamente informada como 30/12/2022, em desacordo com o cadastro oficial citado. Ver R14. |
| F15 — Referências acadêmicas | **Parcial, com erro novo** | Autores, títulos, periódico e número foram corrigidos; a paginação de Pedralli/Cerutti-Rizzatti agora está em 849–872, mas o PDF informa 771–788. Ver R14. |
| F16 — Normas federais | **Parcial** | Efeitos distintos das resoluções CNE foram corrigidos; o dispositivo inexistente da LDB mudou de “§ 1º, I” para “§ 1º, II”. AJUS recebe conclusão jurídica além do que foi verificado. Ver R02 e R12. |
| F17 — CadEJA | **Atendido como delimitação probatória** | Seção 1.4 distingue demanda de matrícula, adesão voluntária e integração local não comprovada. É legítimo mantê-lo fora do percurso obrigatório estadual. |
| F18 — Rastreabilidade | **Parcial** | A tabela de fontes é um avanço, mas permanecem notícias sem endereço específico, afirmações de inexistência pública e declarações abrangentes de verificação contraditas por erros materiais. Ver R15. |
| F19 — Entrevista e ótica do cidadão | **Parcial** | Títulos estão mais próximos da experiência estudantil e perguntas tratam de representação. A pergunta 5 ainda oferece uma escolha entre raias obrigatórias e apoio condicional que mistura estrutura do blueprint, direito e execução. Ver R16. |

## Correções remanescentes e novas — gatilhos para a v3

### R01 — Reconciliação entre tabela de respostas, corpo e README

**Origem:** verificação transversal de F01–F19.  
**Trecho:** todas as linhas da tabela inicial estão como “Corrigido”; a declaração final afirma que todas as referências foram integralmente verificadas.

**Conclusão:** o relato de tratamento não pode substituir a correção efetiva. Os exemplos nos próximos itens mostram problemas ainda ativos. Não se infere intenção de falsificar a pesquisa; verifica-se incompatibilidade entre a declaração e o conteúdo.

**Ação na v3:** manter esta v2 intacta e registrar uma tabela de mudanças da v2 para a v3 com ID R, mudança concreta, fonte e seção final. Usar “pendente” quando faltarem dados. Revisar todas as ocorrências de uma afirmação, incluindo matriz, handoffs, PF, perguntas e referências. Atualizar o README sem apresentar como comprovada uma execução local não observada. As correções da primeira auditoria que foram efetivamente concluídas devem ser preservadas.

### R02 — A citação da LDB continua inexistente

**Origem:** F16.  
**Trechos:** tabela F16, seção 1.3 e quadro de fontes: “art. 37, § 1º, II”, associado a 18 anos.

**Confronto:** o § 1º do art. 37 não se divide nesses incisos. A idade de 18 anos para ingresso no Ensino Médio da EJA consta no art. 16 da Resolução CNE/CEB nº 3/2025 e na portaria estadual, art. 20, II. O art. 38, § 1º, II, da LDB trata de exames supletivos; não deve ser simplesmente trocado no texto como se tivesse o mesmo objeto de matrícula em curso. [LDB, arts. 37–38][LDB]; [Resolução CNE nº 3, art. 16][CNE3]; [Portaria estadual][MAT].

**Ação na v3:** remover todas as ocorrências do dispositivo inexistente. Vincular requisito de ingresso à regra de ingresso, mantendo a LDB como contexto quando pertinente. Não é necessária nova interpretação jurídica para preservar o recorte 18+ já documentado.

### R03 — A documentação de matrícula ainda contém invenções e omissões

**Origem:** F03/F04.  
**Trechos:** etapa 2 e H2: “documento [...] com foto”, incluindo certidão e CNH; matriz: gestor e secretário “assinam conjuntamente”.

**Confronto:** o art. 15, alínea b, enumera certidão de nascimento/casamento ou RG, e não CNH. O § 3º menciona expressamente residência, CPF e NIS, mas NIS desaparece da lista operacional da v2. O art. 18 distingue assinatura do termo pelo estudante/responsável e deferimento pelos profissionais; não comprova o formato de assinatura conjunta criado na matriz. [Portaria de matrícula, arts. 15–18][MAT].

**Ação na v3:** corrigir essas atribuições. Uma lista resumida deve declarar que é resumida, remeter à lista integral e discriminar requisitos condicionais do público 18+; não deve dispensar exigências nem acrescentar documentos como se constassem do artigo. Certidão não é documento com foto. Se houver outra base válida para CNH/CIN, citá-la separadamente. Não confundir a prova dos estudos com os demais documentos cadastrais.

### R04 — Falta uma decisão colegiada no subfluxo de classificação

**Origem:** complemento substantivo de F03/F04, identificado nesta rodada.  
**Trecho:** etapa 2/H2 encaminham avaliação e posicionamento modular à equipe gestora/pedagógica; o Conselho de Classe aparece sobretudo no desfecho.

**Confronto novo:** o art. 18, § 2º, da Resolução CNE/CEB nº 3/2025 exige registro formal do processo avaliativo e deliberação do Conselho de Classe sobre a fase/etapa de classificação. O § 3º admite mais de um momento avaliativo. [Resolução CNE nº 3, art. 18][CNE3].

**Ação na v3:** incluir a passagem avaliação → registro → deliberação colegiada → encaminhamento para matrícula/posicionamento, com as dependências apropriadas. Distinguir essa decisão do deferimento cadastral gestor/secretário. Não fixar uma prova escrita, ata específica, aplicação imediata ou responsável individual sem fonte. O registro formal tem base nacional verificável; seu formato e exposição ao cidadão permanecem a confirmar. Esta é uma etapa de bastidor relevante antes do ingresso, não apenas ao final do módulo.

### R05 — A faixa de 30–50 no diurno não está no dispositivo citado

**Origem:** F08, erro novo na v2.  
**Trechos:** tabela F08, etapa 3 e PF-04: “40 a 50 estudantes (ou 30 a 50 no diurno)”; quadro de fontes resume “30 a 50”.

**Confronto:** art. 23, III, fixa mínimo 40/máximo 50 para EJA Ensino Modular, sem aquela diferenciação por turno. O dispositivo também situa reenturmação ao término de bimestre/módulo; a v2 fala em primeiras semanas. A leitura deve abranger o parágrafo único do art. 23 e os parágrafos subsequentes do art. 24, inclusive participação da Superintendência na autorização descrita no § 5º. [Portaria, arts. 23–24][MAT].

**Ação na v3:** remover o limite diurno sem fonte e corrigir o momento da rotina. Separar solicitação excepcional via SEI/GEE, autorização prevista e reorganização. Não reduzir todo o procedimento a escolha discricionária da gestão ou a uma única negativa da GEE. Preservar deslocamento distante ou mudança de turno como efeito possível a verificar, sem declarar ocorrência ou automatismo.

### R06 — Continuidade modular não equivale a equivalência integral automática

**Origem:** F12.  
**Trechos:** tabela F12 diz que a interpretação unificada permanece pendente; etapa 5 afirma harmonização e retorno “aproveitando integralmente os módulos e componentes”.

**Confronto:** o art. 24, § 2º, permite avanço de reprovados e condiciona conclusão à aprovação nos quatro módulos, com quatro ênfases. O art. 25 delimita calendários de 2026; não demonstra uma regra geral de equivalência de componentes. [Portaria de matrícula][MAT].

**Ação na v3:** explicar a regra específica e separar sua aplicação dos detalhes de progressão parcial ainda não reconciliados. No retorno, indicar análise documental/pedagógica dos estudos anteriores, sem prometer aproveitamento integral automático. Deixar a pendência junto do trecho que dela depende. Distinguir resultado intermediário de módulo, integralização escolar e categoria censitária final; ver também R07.

### R07 — Curso em andamento não é um substituto genérico para abandono

**Origem:** F11; distorção nova da categoria incluída na v2.  
**Trechos:** etapa 5, item 5, descreve quem deixou de comparecer e oferece “deixou de frequentar” ou “curso em andamento” conforme o calendário; PF-09 repete “sem esgotamento de busca ativa” e “barreiras no prontuário”.

**Confronto:** o caderno do Inep distingue estudante que permanece em atividades ainda não concluídas de estudante que deixou a escola. A continuidade da turma, isoladamente, não resolve a situação individual. Também distingue resultado de etapa de resultados intermediários por módulo. O caderno consultado é da coleta **2025**, disponibilizado como referência na página de perguntas frequentes; sua edição não deve ser renomeada como norma da coleta 2026. [Inep, caderno Situação do Aluno 2025, seções 3 e 5][INEP25]; [perguntas frequentes][INEPFAQ].

**Ação na v3:** apresentar a distinção conceitual e o limite temporal da fonte. Não inferir erro de registro apenas do motivo laboral/familiar ou da falta de esgotamento da busca ativa. Retirar a barreira de prontuário sem prova, que reintroduz o bloqueio já contestado. O risco defensável é uma divergência entre situação individual documentada e declaração, sem afirmar que já ocorreu. Compatibilização operacional com a coleta aplicável pode permanecer pendente.

### R08 — Extração vazia de um portal não demonstra fechamento nem predominância presencial

**Origem:** F02 e nova inferência na v2.  
**Trechos:** seção 1.3 diz que não há módulos abertos, “o que confirma” atendimento predominantemente presencial; quadro de fontes afirma inscrição fechada.

**Confronto:** nesta auditoria, o portal mantém link de matrícula para `matriculaonline.educacao.al.gov.br/cadastro/cpf`. A página de destino não produziu texto extraível. Isso não permite confirmar nem abertura nem fechamento. Ausência de observação do formulário tampouco quantifica distribuição entre canais. [Portal público][PORTAL]; [destino do cadastro][CADASTRO].

**Ação na v3:** informar a limitação e retirar a conclusão de predominância. Manter separados prazo ordinário passado, previsão de ingresso contínuo e disponibilidade atual não verificada. O esquema H1–H6 deve permitir entrada presencial em H2 nos casos documentados, sem exigir passagem universal pelo portal. Não confundir ausência de acesso técnico com ausência do serviço.

### R09 — Evidências materiais ainda recebem status documental excessivo

**Origem:** F05/F04.  
**Trechos:** matriz: “ata de prova de classificação (previsto em norma: art. 20, III)”, “recibo [...] prática administrativa padrão”, “relação de concluintes afixada [...] art. 8º, II” e certificado em papel timbrado.

**Conclusão:** a previsão de classificação não especifica sozinha esses objetos. O registro formal agora pode ser sustentado pela fonte nacional de R04, mas isso não comprova entrega de ata ao candidato. A atribuição de publicar concluintes não comprova mural, e a existência de certificado não define seu suporte físico. O texto narrativo ainda descreve murais/recepção como rotina certa, enquanto a matriz os chama de hipótese.

**Ação na v3:** registrar formato, entrega e visibilidade como pendentes quando desconhecidos. Separar documento interno, evidência apresentada pelo cidadão e retorno efetivamente percebido. Preservar calendário visível, que tem suporte específico, sem estender sua regra a outros documentos. Mapear orientação/resultado de matrícula em termos funcionais quando não se conhece o comprovante. [Portaria nº 1.133/2026, arts. 6º e 8º, extração local `doe_p12.txt`][ANO26]; [Resolução nº 3, art. 18][CNE3].

### R10 — Sincronização, livros eletrônicos e certificação via SEI continuam sem prova

**Origem:** F06.  
**Trechos:** suporte da etapa 5: “Declaração e sincronização censitária”; H3: “registro no livro eletrônico”; matriz: “livros de concluintes no SAGEAL” e certificação via SEI.

**Conclusão:** substituir “migração” por “sincronização” não resolve a falta de evidência técnica. Dever de escrituração e atualização não comprova módulo, livro ou integração. SEI documentado no fluxo de calendário não demonstra que todo processo de certificação percorra o mesmo sistema. [Portaria de 2026, arts. 5º e 7º–10, extração `doe_p12.txt`][ANO26].

**Ação na v3:** usar registro escolar, declaração censitária e tramitação administrativa como funções; deixar mecanismo e suporte específico pendentes. Não afirmar automação nem digitação totalmente manual. A interface pública pode ser visível sem que seus mecanismos internos sejam conhecidos. Responsabilidade institucional e arquitetura de software devem permanecer distintas.

### R11 — Há ações agrupadas em uma camada sem verificar sua visibilidade

**Origem:** falha de modelagem residual, distinta da posição das linhas já corrigida em F01.  
**Trecho:** frontstage da etapa 4: equipe de nutrição/merendeiras “prepara e serve” a refeição. No caminho digital, o frontstage das etapas 1–2 descreve apenas atendentes humanos.

**Conclusão:** preparar alimentos não é necessariamente observado pelo estudante; servir pode sê-lo. Também não se deve equiparar função técnica nutricional à preparação/distribuição sem verificar atribuições. A interação com a interface digital é parte perceptível do serviço, mesmo que não exista atendente humano naquele passo.

**Ação na v3:** separar planejamento/preparo, entrega e consumo, atribuindo camadas por ação e explicando o limite de observação. Mostrar apresentação de informação/recepção do pedido na interface pública no frontstage digital, sem inventar resposta técnica não inspecionada. Manter a ordem correta das cinco camadas. A escolha entre backstage e suporte para uma ação interna deve ser justificada pelo recorte, não pelo nome da instituição.

### R12 — BUSCAE e AJUS: distinguir responsabilidades, sistema e pendência jurídica

**Origem:** F10/F16.  
**Trechos:** H5 associa comunicação docente às três faltas; quadro de fontes diz que manutenção da AJUS “depende de ato normativo alagoano”; PF-05 afirma necessidade de regulamentação atualizada.

**Confronto:** o decreto descreve dever docente de comunicação e um gatilho específico de contato pela coordenação, que não devem ser fundidos. Já existe ato estadual sobre AJUS: o próprio decreto. Não localizar atualização não permite afirmar exigência jurídica de novo ato. A Portaria nº 1.133/2026, art. 52, prevê registro das ações em sistema oficial de prevenção ao abandono, cuja identificação não está resolvida na pesquisa. [Decreto BUSCAE, arts. 5º–7º, extrações locais][BUSCAE]; [Portaria de 2026, art. 52, `doe_p14.txt`][ANO26].

**Ação na v3:** separar comunicação, contato, encaminhamento pedagógico e registro das ações. Não condicionar toda comunicação docente a esperar três faltas. Manter identidade/integração do sistema de prevenção como pendência. Qualificar a aplicabilidade atual da AJUS sem declará-la revogada, plenamente regularizada ou automaticamente dependente de nova lei. Ciência/compensação não deve ser renomeada como abono geral.

### R13 — Os fail points continuam misturando hipóteses, consequências certas e relações não provadas

**Origem:** F09/F13 e problemas novos de representação.  
**Trechos:** PF-01 presume reconhecimento institucional; PF-06 prevê jejum “gerando [...] abandono”; seção 7 compara lanches rápidos; PF-08 pressupõe desligamento completo; o esquema liga PF-01 → PF-02 → PF-03 sem explicar relações.

**Conclusão:** um mecanismo condicional não torna inevitável seu efeito. A norma alimentar não estabelece que só refeições quentes sejam adequadas. As setas entre riscos sugerem sequência causal que não foi demonstrada. Além disso, a tabela declara cinco colunas, mas as nove linhas de PF contêm quatro células: status probatório fica sob “Efeito Potencial” e a coluna de fundamento fica vazia. Aqui a estrutura prejudica a interpretação da evidência, não apenas a aparência.

**Ação na v3:** separar condição, mecanismo, efeito possível e fundamento/status em células correspondentes. Retirar comparação nutricional sem fonte e a interpretação automática de motivação institucional. Distribuir os riscos por etapas; não ligar riscos independentes como causas sucessivas. Não inventar medida de ocorrência. O direito à alimentação permanece normativo mesmo quando a cobertura observada é desconhecida. [Portaria de 2026, arts. 55–58, extração `doe_p14.txt`][ANO26].

### R14 — Três erros verificáveis de identificação documental e territorial

**Origem:** F14/F15 e erro territorial ainda não apontado na primeira auditoria.

1. **Lei Delegada nº 48:** tabela F14, quadro de fontes e referência 4 afirmam publicação em 30/12/2022. O cadastro citado distingue data do ato **30/12/2022** de publicação **31/12/2022**. Corrigir todas as ocorrências. [SAPL da Assembleia Legislativa][LEI48].
2. **Pedralli/Cerutti-Rizzatti:** tabela F15, fontes e referência 14 informam páginas **849–872**. O PDF do artigo informa **771–788**, volume 13, número 3, 2013. Corrigir sem alterar os autores e título já ajustados. [PDF do artigo, primeira página][PEDPDF].
3. **CEJA Remy Maia:** seção 1.5 o situa em Maceió. O cadastro oficial o localiza em **Palmeira dos Índios**. Corrigir ou retirar o exemplo, mantendo o recorte estadual. O cadastro publica expediente e ressalva sobre almoço, mas isso não prova toda a rotina de atendimento nem autoriza generalizar para a rede. [Alagoas Digital — unidade 888][REMY].

### R15 — O quadro de fontes não elimina alegações não rastreáveis

**Origem:** F18.  
**Trechos:** PF-06: “sem auditoria pública disponível”; PF-07: “não constam em relatórios públicos abertos”; seção 7 cita notícias, página Escola 10/Busca Ativa e publicações de contratos sem links específicos.

**Conclusão:** a seção metodológica afirma que o relatório evita inexistência documental, mas essas formulações persistem. Uma página inicial de órgão não sustenta notícia ou rotina específica. Declaração de verificação integral é especialmente inadequada diante dos erros de R02/R05/R14.

**Ação na v3:** citar a publicação exata e o que foi efetivamente consultado, ou retirar a alegação. Limitar resultados negativos às buscas realizadas. Separar consulta nova, reutilização local e referência indicada pela auditoria. Não inventar histórico de ferramentas ou consultas. Se o PNE ficar apenas como contexto constitucional genérico, dizer isso; não declarar conferência de metas vigentes sem lei/anexo identificados. Manter a explicação de fonte nacional versus execução estadual em todas as células relevantes.

### R16 — As perguntas finais devem separar decisão de representação de constatação de direito

**Origem:** F19.  
**Trecho:** pergunta 5 opõe “raias obrigatórias permanentes” a “processos de suporte condicionais à oferta local”.

**Conclusão:** a estudante decide como representar ações e incertezas; não decide se alimentação é direito ou se determinada rota funciona. Alimentação e transporte não substituem as cinco camadas obrigatórias do exercício. Uma oferta não verificada deve ser qualificada sem apagar obrigação normativa.

**Ação na v3:** formular perguntas sobre visibilidade, percurso, grau de detalhe, desfechos e destaque dos riscos, com pressupostos factuais já corrigidos. Manter o recorte estadual acordado; escola ilustrativa não vira evidência de campo. Preparar a pergunta sobre a nova participação do Conselho de Classe na classificação para a futura entrevista. Não gerar agora respostas, transcript, blueprint final ou diagrama da Parte D.

### R17 — A alocação em opção diferente é um risco documentável ainda omitido

**Origem:** novo ponto de falha e passagem de responsabilidade identificados nesta auditoria.  
**Local:** etapa 2/H1 menciona escolha de até três escolas/turnos, mas não explica adequadamente alocação divergente.

**Confronto:** art. 12, §§ 2º–3º, admite alocação em turno divergente ou unidade fora das opções, nas condições previstas. Isso não prova abandono ou deslocamento ocorrido, mas fundamenta risco de incompatibilidade entre a oferta recebida e a disponibilidade do adulto. [Portaria de matrícula, art. 12][MAT].

**Ação na v3:** incorporar essa informação na jornada e analisar como risco específico, por exemplo PF-10, ou justificar explicitamente sua incorporação a PF existente. Distinguir regra documentada de efeito hipotético. Indicar como pendência o procedimento de devolutiva/alternativa quando não comprovado, sem inventar recurso administrativo, reserva de vaga ou prazo. Esse ponto pode ser mais bem fundamentado que presumir cancelamento ou bloqueio automático.

## Orientação de fechamento da v3

A v3 deve ser uma pesquisa integral e coerente, mantendo as cinco etapas e a matriz preliminar de cinco camadas, com as três fronteiras já corrigidas. Não precisa reproduzir toda a extensão da v2. Deve conter:

- Tabela **R01–R17 → correção/defesa fundamentada/pendência → mudança concreta em relação à v2 → seção e fonte**. Cada delta deve citar seu gatilho desta segunda auditoria.
- Regras documentadas separadas de formatos operacionais desconhecidos; hipóteses e efeitos possíveis qualificados na própria célula ou frase.
- Passagens de classificação, deferimento, registro, acompanhamento e desfecho suficientemente distintas, sem arquitetura de TI presumida.
- Um quadro explícito das pendências que continuarão para observação futura: rotinas locais, cobertura de apoios, instrumentos de comunicação, integrações, detalhes de AJUS e aplicação censitária correspondente.

Não alterar retrospectivamente v1, auditoria v1 ou v2 para fazer parecer que os erros nunca ocorreram. Uma pendência bem delimitada pode permanecer no AS-IS documental; uma afirmação contrária à fonte deve ser corrigida. Os achados não autorizam inventar observações para preencher lacunas.

## Fontes efetivamente usadas nesta rodada

Consultas web em 16/11/2026, salvo extrações locais explicitamente identificadas. Acesso à norma não é observação da execução.

| Fonte | Uso e limite |
|---|---|
| [Portaria nº 16.735/2025][MAT] | Texto do PDF público consultado: arts. 12, 15–20 e 23–25. |
| [LDB no Planalto][LDB] | Texto acessível nesta rodada; confronto específico de arts. 37–38. Não se afirma auditoria integral de toda a legislação educacional. |
| [Resolução CNE/CEB nº 3/2025][CNE3] | Reprodução institucional IFAP: arts. 16 e 18, especialmente classificação e sua deliberação colegiada. |
| [Portal][PORTAL] e [cadastro][CADASTRO] | Link público identificado; destino dinâmico sem conteúdo extraível, sem comprovar seu estado de funcionamento. Nenhum dado pessoal foi enviado. |
| [Inep — caderno 2025][INEP25] e [FAQ][INEPFAQ] | Definições de situação do aluno e distinção entre etapa e módulos intermediários. Manter identificação da edição 2025 e verificar regras da coleta aplicável. |
| [Lei Delegada nº 48 — SAPL][LEI48] | Data do ato, publicação e ementa. |
| [Artigo de Pedralli/Cerutti-Rizzatti em PDF][PEDPDF] | Cabeçalho comprova páginas 771–788. |
| [Cadastro CEJA Remy Maia][REMY] | Localização em Palmeira dos Índios e expediente informado; não comprova cumprimento cotidiano ou representatividade estadual. |
| [Portaria nº 1.133/2026][ANO26] e [Decreto nº 90.347/2023][BUSCAE] | Releitura de `contexto/fontes_2_1/doe_p12.txt`, `doe_p14.txt`, `decreto2023_p6.txt` e `decreto2023_p7.txt`; não é nova inspeção integral das edições online. |

[MAT]: https://www.matriculaonline.al.gov.br/storage/pdfs/16_16_DI%C3%81RIO%20CRONOGRAMA%20MATR%C3%8DCULA.pdf
[LDB]: https://www.planalto.gov.br/ccivil_03/leis/l9394.htm
[CNE3]: https://ifap.edu.br/documents/1074/Res_CNE_CEB_3_2025.pdf
[PORTAL]: https://www.matriculaonline.al.gov.br/
[CADASTRO]: https://matriculaonline.educacao.al.gov.br/cadastro/cpf
[INEP25]: https://download.inep.gov.br/publicacoes/institucionais/estatisticas_e_indicadores/cadernos_de_conceitos_e_orientacoes_da_segunda_etapa_do_censo_escolar_2025_situacao_do_aluno_ed.pdf
[INEPFAQ]: https://www.gov.br/inep/pt-br/acesso-a-informacao/perguntas-frequentes/censo-escolar/
[LEI48]: https://sapl.al.al.leg.br/norma/2450
[PEDPDF]: https://www.scielo.br/j/rbla/a/vZWw6znGkH6cFMcCPP354RG/?format=pdf&ilang=pt_BR&lang=pt
[REMY]: https://alagoasdigital.al.gov.br/unidade-de-atendimento/888
[ANO26]: https://diario.imprensaoficial.al.gov.br/apinova/api/editions/viewPdf/51261
[BUSCAE]: https://www.imprensaoficial.al.gov.br/storage/files/diary/2023/03/doeal-2023-03-29-completo-bf-3satd6fvadkgkka6baewee74yf73pelwnpeztnnsv2rvtnmrr6.pdf
