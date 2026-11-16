# Primeira auditoria adversarial — Exercício 3.1

**Assistente 2:** Codex / OpenAI.  
**Pesquisa auditada:** `B_relatorio_assistente_v1.md`, produzida pelo assistente 1, Gemini / Antigravity CLI.  
**Estudante:** Rosy Emannuele Moura dos Santos Bomfim.  
**Data da auditoria:** 16 de novembro de 2026.  
**Serviço:** acesso e permanência na EJA Modular do Ensino Médio da rede estadual de Alagoas, para pessoas de 18 anos ou mais, mantendo o recorte do Exercício 2.1.  
**SHA-256 da v1 examinada:** `6f46cf3ba1c8cafa43f3912bdbdf8d8390aff6ce848e12185f05143ab3c30e1c`.

## Parecer e método

A v1 oferece uma base útil, mas ainda não sustenta a elaboração definitiva das Partes C e D. Há um erro conceitual nas três linhas divisórias, uma alternativa normativa de ingresso omitida, referências bibliográficas inexatas e afirmações operacionais mais fortes do que suas evidências. Esta auditoria identifica **19 achados substantivos, F01 a F19**. Não atribui nota nem considera estilo ou diagramação como falhas.

Foram confrontados o relatório integral, o enunciado do exercício, fontes públicas acessíveis na web e os textos oficiais preservados em `contexto/fontes_2_1/`. Os arquivos locais do DOE foram reutilizados como extrações documentais; isso não equivale a uma nova consulta integral de todas as edições na internet. Não houve visita a escola, entrevista com servidor, acesso autenticado ao SAGEAL nem teste de matrícula real. Portanto, esta auditoria também não comprova a execução cotidiana em toda a rede.

São aproveitáveis: o serviço concreto e nomeado; o público plural; a divisão analítica em cinco momentos; a separação entre portal, sistema escolar e censo; o reconhecimento de ingresso contínuo; e a explicitação de algumas pendências de suporte técnico, GEGEV e AJUS. A correção solicitada é fazer essas ressalvas valerem em todas as seções, inclusive tabelas e pontos de falha.

## Achados que a v2 deverá abordar individualmente

### F01 — As três linhas divisórias estão entre camadas erradas

**Local e trecho:** seção 4: a linha de interação está entre Evidências e Ações do Cidadão; a de visibilidade, entre Ações do Cidadão e Frontstage; a de interação interna, entre Frontstage e Backstage.

**Problema:** essas linhas definem relações entre participantes e visibilidade das ações. Sua posição altera o significado do blueprint; não se trata de ordem meramente estética. O enunciado fornecido pela estudante apresenta a estrutura correta.

**Tratamento exigido:** reorganizar a matriz inteira nesta sequência: **Evidências → Ações do Cidadão → Linha de Interação → Frontstage → Linha de Visibilidade → Backstage → Linha de Interação Interna → Processos de Suporte**. Depois localizar os fail points nas ações correspondentes. Rever também a explicação textual das fronteiras. Uma mesma instituição pode atuar em camadas diferentes conforme a ação; não classificar a instituição inteira como visível ou invisível.

### F02 — O fluxo anual de pré-matrícula foi universalizado

**Local e trecho:** etapa 2: “A inscrição inicial exige o preenchimento de formulário no portal”; PF-01: “Exigência de inscrição prévia em portal web para acesso à vaga”.

**Problema:** a própria seção 2.1 reconhece ingresso contínuo, mas a narrativa impõe a todos o percurso de pré-inscrição e prazo do calendário ordinário. A Portaria nº 16.735/2025 contempla matrícula presencial para vagas existentes e ingresso contínuo na EJA, nos arts. 19 e 24. O portal público, sozinho, não prova que uma janela de inscrição está aberta em novembro. [Portaria de matrícula][S1]; [portal público][S2]; [serviço 585][S3].

**Tratamento exigido:** distinguir o ciclo ordinário de início do ano, o ingresso durante o período letivo e o retorno. Identificar o que se sabe sobre o canal de cada percurso e o que permanece pendente. Verificar o destino atual dos links do portal sem preencher dados pessoais. Não transformar calendário passado em prazo vigente nem prometer disponibilidade de vaga.

### F03 — Falta a alternativa de classificação e a lista documental é imprecisa

**Local e trecho:** etapa 2 enumera documentos como obrigatórios; PF-02 afirma “Impossibilidade de confirmação da matrícula” e “ausência de mecanismos ágeis de convalidação”.

**Problema:** o art. 20, III, admite classificação quando não há documento de estudos anteriores. O art. 15 também exige leitura mais cuidadosa das alternativas e condições documentais; a lista abreviada da v1 não deve parecer exaustiva nem tornar RG/CIN a única identificação admitida. [Portaria de matrícula][S1].

**Tratamento exigido:** representar a bifurcação comprovação de estudos/classificação. Informar requisitos por fonte e aplicabilidade, sem criar dispensas. Apurar responsáveis, encaminhamento e comunicação ao estudante; deixar duração e operação concreta pendentes se não houver evidência. Reescrever PF-02 como risco condicional de dificuldade no encaminhamento ou informação, caso não se encontre prova de ocorrência. Não afirmar exame imediato ou matrícula garantida. Existência da alternativa normativa não é uma escolha da estudante na futura entrevista.

### F04 — Passagens de responsabilidade documentadas ficaram incompletas

**Local e trecho:** etapa 2: “A secretaria confere [...] lança a validação”; suporte da etapa 3: “Inspeção Educacional da GEE homologa calendários escolares”.

**Problema:** o art. 18 da portaria de matrícula prevê deferimento pelo gestor geral/adjunto e secretário escolar. A homologação de calendário não esgota seu fluxo: o art. 5º da Portaria nº 1.133/2026 inclui aprovação pelo Conselho Escolar e encaminhamento via SEI. [Portaria de matrícula][S1]; [Portaria de organização de 2026][S4], extração `doe_p12.txt`.

**Tratamento exigido:** explicitar remetente, destinatário, documento/dado e decisão dessas passagens, mantendo Conselho Escolar distinto de Conselho de Classe. Na matrícula, separar atendimento, conferência, deferimento e registro. Onde a devolutiva ao cidadão diante de pendência ou falta de vaga não estiver documentada, registrar a lacuna, em vez de inventar recibo ou prazo. Usar identificadores consistentes entre narrativa e esquema de handoffs para permitir rastreamento das responsabilidades.

### F05 — Evidências percebidas pelo cidadão foram presumidas

**Local e trechos:** seção 4: “folder informativo”, “Recibo impresso de matrícula assinado”, “apostilas modulares distribuídos”, “Boletim escolar impresso ou emitido via portal”; etapa 3 pressupõe listas em murais.

**Problema:** são objetos plausíveis, mas a v1 não apresenta comprovação de uso na rede para cada um. Atas internas também não se tornam evidência percebida pelo estudante só por existirem. O portal exibe uma função de imprimir inscrição, o que não comprova recibo definitivo de matrícula. Há uma evidência normativa mais concreta omitida: calendário homologado afixado em local visível, conforme art. 6º, § 1º, da Portaria nº 1.133/2026. [Portal][S2]; [Portaria de 2026][S4], `doe_p12.txt`.

**Tratamento exigido:** ligar cada evidência à fonte e ao status: interface publicamente verificável, documento previsto em norma ou hipótese de uso local. Separar comprovante de inscrição de confirmação de matrícula. Evitar afirmar suporte material, assinatura, formato de boletim, meio de contato ou acesso à ata quando desconhecidos. Não é necessário eliminar elementos plausíveis; é necessário qualificá-los.

### F06 — Funções administrativas foram convertidas em arquitetura de sistemas

**Local e trechos:** handoff 1: “integridade da base da Receita Federal/CPF”; handoff 3: status “inscrito”/“matriculado” e “vinculação ao livro de matrícula”; suporte da etapa 5: “Exportação e migração”; seção 5.3: “processamento manual”.

**Problema:** solicitar CPF não demonstra integração com a Receita Federal. Atribuições de registro não comprovam nomes de campos, migração automática, API ou processamento inteiramente manual. Tampouco o art. 9º da Portaria nº 1.133/2026 demonstra a fórmula sugerida por “base de cálculo para repasses de merenda e transporte”: o texto estabelece que os dados subsidiam políticas públicas. [Portaria de 2026][S4], `doe_p12.txt`.

**Tratamento exigido:** descrever responsabilidades e informações necessárias com linguagem funcional. Manter mecanismo técnico, campos, integrações e frequência de sincronização como não comprovados, salvo documentação específica. Distinguir a declaração de dados ao Educacenso da forma técnica de transferência. Ausência de prova de automação também não prova ausência de automação. Identificar o operador humano responsável sem atribuir decisão autônoma à ferramenta.

### F07 — A matriz contradiz as próprias pendências institucionais

**Local e trechos:** seção 4: “Parâmetros de oferta de vagas definidos pela GEGEV/Seduc” e “Suporte técnico [...] (Seduc/ITEC)”; seção 5.3 mantém competências da GEGEV e identidade de TI em aberto.

**Problema:** as ressalvas não acompanham as células que atribuem atos e responsabilidades. Uma estrutura organizacional histórica não comprova, por si, quem parametriza cada sistema em 2026.

**Tratamento exigido:** preservar GEGEV como órgão documentado no contexto disponível, com competência operacional específica a verificar. Representar a função de suporte técnico sem confirmar ITEC, terceirização ou equipe própria. Aplicar a mesma qualificação em todas as ocorrências. Se houver nova fonte que resolva a pendência, citar ato, data e competência demonstrada; não basta mencionar genericamente Seduc.

### F08 — Reenturmação foi equiparada a fechamento e deslocamento forçado

**Local e trechos:** PF-04: “baixa frequência”, parâmetro “40 a 50”, “Deslocamento forçado [...] outra escola distante, alteração de turno ou cancelamento”.

**Problema:** a norma distingue mínimo e máximo de estudantes e contempla tratamento excepcional mediante solicitação à GEE. Reenturmação não demonstra automaticamente todos os desfechos negativos listados, nem autoriza substituir número de estudantes por frequência diária sem fundamentação. [Portaria de matrícula][S1], art. 23 e parágrafo único.

**Tratamento exigido:** apresentar a regra e sua exceção. Separar fato normativo, decisão administrativa e possível efeito sobre o estudante. Manter deslocamento, mudança de turno e cancelamento como hipóteses condicionais que exigem comprovação específica; não como consequências necessárias. Explicitar a comunicação ao estudante como informação a apurar quando não documentada.

### F09 — Alimentação e transporte têm execução e causalidade presumidas

**Local e trechos:** etapa 4 afirma permanência “viabilizada pelo fornecimento”; seção 7 afirma maior risco de “lanches frios não nutritivos” para a noite; PF-07 afirma “forçando a evasão” e cobertura condicionada a convênios municipais; seção 7 fixa término às “21h30–22h”.

**Problema:** faltam observações ou dados de cobertura que sustentem essas situações, comparações e horários. Refeição fria não é, por definição, nutricionalmente inadequada. O art. 6º da Portaria nº 1.133/2026 trata de compatibilização do recesso/calendário relacionada ao transporte; não prova o regime de todos os contratos ou rotas. A previsão alimentar aparece também nos arts. 55–58, não apenas nos programas dos arts. 61–63. [Portaria de 2026][S4], `doe_p12.txt`, `doe_p14.txt` e `doe_p15.txt`.

**Tratamento exigido:** separar direito/previsão normativa, organização do apoio e cobertura efetiva. Retirar horários e comparações sem fonte. Reescrever PF-06/PF-07 como cenários condicionais, com efeitos possíveis, não causalidade medida. Indicar quais registros locais poderiam confirmar o risco, sem declarar que já foram consultados. A alimentação não se torna juridicamente opcional porque sua execução não foi verificada.

### F10 — A busca ativa foi reduzida à digitação no SAGEAL

**Local e trechos:** PF-08: “A busca ativa só é disparada [...] há semanas” e “gargalo operacional conhecido”; seção 7 afirma dependência crítica da digitação docente.

**Problema:** não há evidência local desse atraso ou de que todo acionamento dependa do SAGEAL. O decreto prevê comunicação entre profissionais, além do registro. A Portaria nº 1.133/2026, art. 52, menciona registro de ações em sistema oficial de prevenção ao abandono, sem que isso, isoladamente, identifique esse sistema como SAGEAL. [Decreto BUSCAE][S5], `decreto2023_p6.txt` e `decreto2023_p7.txt`; [Portaria de 2026][S4], `doe_p14.txt`.

**Tratamento exigido:** mapear docente → secretaria/coordenação/gestão → contato com estudante adulto → orientação/recomposição → registro/acompanhamento, conforme a atribuição documentada. O gatilho de três faltas na semana tem respaldo no art. 7º, § 1º, do decreto e deve ser preservado com atribuição correta. Distinguir previsão de comunicação, mecanismo digital e execução observada. Atraso pode ser risco, mas não fato conhecido nem dependência tecnológica exclusiva demonstrada.

### F11 — Classificação de abandono, censos e bloqueio de retorno estão mal sustentados

**Local e trechos:** etapa 5: “Quando esgotadas as ações [...] sem retorno”; PF-09: afastamento por trabalho/família é apresentado como rotulação indevida, com “bloqueio administrativo para retorno ágil”.

**Problema:** motivo da interrupção não demonstra, sozinho, erro na classificação censitária. A v1 também não demonstra o esgotamento do BUSCAE como requisito formal para o registro nem a existência do bloqueio citado. O decreto possui definições próprias no art. 4º; o Inep distingue rendimento, movimento e, para EJA, a situação de curso em andamento. Esta última foi omitida. [Decreto BUSCAE][S5], `decreto2023_p6.txt`; [orientação do Inep][S6].

**Tratamento exigido:** separar interrupção vivida pelo estudante, classificação administrativa estadual e declaração censitária. Explicar os critérios efetivamente documentados, sua referência temporal e o que requer compatibilização com a EJA modular. Incluir curso em andamento quando aplicável. Não transformar percentual de faltas em cancelamento automático. Retirar bloqueio não comprovado e reformular PF-09 como risco condicional de inconsistência de registro, com critério de verificação definido.

### F12 — Progressão e desfechos modulares precisam de compatibilização específica

**Local e trecho:** etapa 5: “assegura-se a progressão parcial nos termos do art. 39, § 2º, III”; etapa 3 atribui aproveitamento aos “arts. 24 e 25”.

**Problema:** a referência geral de progressão não basta para explicar a operacionalização na EJA Modular. O art. 24, § 2º, da portaria de matrícula tem tratamento específico de avanço entre módulos e integralização; o art. 25 trata da organização do calendário, não comprova por si equivalência de componentes. [Portaria de matrícula][S1]; [Portaria de 2026][S4], `doe_p14.txt`.

**Tratamento exigido:** distinguir aprovação/conclusão de módulo, continuidade, pendências, conclusão integral, transferência, interrupção e retorno. Reconciliar os dispositivos ou registrar a interpretação operacional como pendente. Não inventar equivalência automática, prazo de certificação ou atalho de reingresso. Explicar quem verifica o percurso e qual informação sustenta o resultado, reconhecendo limites de documentação.

### F13 — O rótulo de risco não corrige descrições afirmativas sem evidência

**Local e trechos:** PF-03: secretaria “restrito aos turnos diurnos [...] em determinadas unidades”; PF-01: polos de apoio “comprova[m] o reconhecimento do risco pela administração”.

**Problema:** nenhuma unidade foi observada ou identificada como prova do horário descrito. A existência de apoio presencial permite uma inferência sobre possíveis barreiras, mas não comprova a motivação institucional ou incidência do problema. A última coluna da tabela não neutraliza uma afirmação categórica nas demais colunas.

**Tratamento exigido:** para todos os PF, separar condição, mecanismo, efeito possível e evidência disponível. Exemplo metodológico: se o atendimento de uma unidade não coincidir com a disponibilidade do trabalhador, poderá haver dificuldade de confirmação; horários efetivos precisam ser verificados. Isso é hipótese, não ocorrência documentada. Uma informação desconhecida também não é, por si só, um fail point. Preservar códigos dos PF ou fornecer correspondência quando reorganizá-los.

### F14 — Data e objeto da Lei Delegada nº 48 estão errados

**Local e trecho:** referência 4: “Lei Delegada nº 48, de 10 de fevereiro de 2022” e objeto restrito à estrutura da Seduc.

**Problema:** o cadastro oficial registra **30 de dezembro de 2022** e um modelo de gestão da Administração Pública Estadual do Poder Executivo. A estrutura da Seduc é parte desse conjunto. [Assembleia Legislativa de Alagoas][S7].

**Tratamento exigido:** corrigir data e objeto; diferenciar edição original, alterações e republicação usada para identificar órgãos. Citar a localização da estrutura da Seduc na edição efetivamente consultada. Não confundir a data da lei com a de uma republicação nem tratar estrutura de 2023 como comprovação completa de competências em 2026.

### F15 — As referências acadêmicas não correspondem aos artigos vinculados

**Local e trechos:** referências 11 e 12: “Guimarães, M. A.” em Revista Brasileira de Estudos Pedagógicos; título “Práticas de letramento [...] pertença e acolhimento”, volume 13, número 4, para Pedralli e Cerutti-Rizzatti.

**Problema e correção:** o primeiro artigo é de **Sheila Denize Guimarães**, *Práticas pedagógicas e questões sociais: evasão na Educação de Jovens e Adultos*, **Revista Diálogo Educacional**, 25(86), 2025, DOI `10.7213/1981-416X.25.086.DS09`. A revisão de 22 pesquisas é compatível com seu resumo. [Artigo de Guimarães][S8]. O segundo é de **Rosângela Pedralli e Mary Elizabeth Cerutti-Rizzatti**, *Evasão escolar na educação de jovens e adultos: problematizando o fenômeno com enfoque na cultura escrita*, **Revista Brasileira de Linguística Aplicada**, 13(3), 2013, DOI `10.1590/S1984-63982013005000019`. [Artigo de Pedralli e Cerutti-Rizzatti][S9].

**Tratamento exigido:** corrigir metadados sem completar páginas ou títulos por aproximação. Explicitar os limites de transferência dos estudos: eles ajudam a formular hipóteses, mas não demonstram a operação atual da EJA Modular estadual alagoana. Não transformar achados de outros contextos em prevalência ou causalidade local.

### F16 — Referências federais precisam de vínculo preciso com as afirmações

**Local e trechos:** seção 1.3 cita “LDB [...] art. 37, § 1º, I” para idade; seção 2.2 atribui conjuntamente às Resoluções nº 3 e nº 6 a revogação da nº 1/2021; menciona PNE e outras normas sem referências finais completas.

**Problema:** a idade do recorte está diretamente respaldada pela portaria estadual, enquanto o dispositivo da LDB indicado precisa ser corrigido e conferido em texto oficial acessível. A revogação expressa consta no art. 19 da Resolução nº 3/2025; a nº 6/2025 altera a nº 3 no regime de transição. [Portaria estadual][S1]; [Resolução nº 3][S10]; [Resolução nº 6][S11]. O link da LDB presente na v1 retornou 404 nesta auditoria; não se deve alegar leitura atualizada integral com base nesse acesso falho.

**Tratamento exigido:** corrigir a atribuição dos efeitos de cada resolução, sustentar cada requisito pelo dispositivo pertinente e completar as fontes federais mantidas na v2. Distinguir número de objetivo/meta do PNE após conferência do anexo. A mudança federal não permite concluir automaticamente nem revogação do decreto estadual nem validade irrestrita da AJUS. Preservar a pendência de compatibilidade, sem apresentá-la como ausência total de norma.

### F17 — CadEJA é citado, mas sua relevância operacional não foi examinada

**Local e trecho:** seção 2.2 menciona “Cadastro Nacional da EJA — CadEJA”, sem discutir sua relação com o acesso na etapa 1 ou 2.

**Problema:** a Portaria MEC nº 275/2026 institui o **Cadastro da Educação de Jovens e Adultos** para registro e gestão de demanda. Não é sinônimo de matrícula escolar. Seu art. 8º prevê utilização voluntária pelas redes e instituições. Logo, nem omitir a análise do canal nem presumir adoção de Alagoas resolve a questão. [Portaria MEC nº 275/2026, reprodução institucional do DOU][S12].

**Tratamento exigido:** investigar se há evidência de adesão e encaminhamento operacional na rede estadual alagoana. Se não houver, registrar como contexto nacional com integração local não comprovada, sem inseri-lo no fluxo obrigatório do cidadão ou apresentar implantação futura como AS-IS. Explicar a diferença entre manifestar demanda e conseguir matrícula. O nome oficial deve ser corrigido.

### F18 — A rastreabilidade de consultas é insuficiente para o grau de certeza declarado

**Local e trechos:** seção 2.1: “exame documental exaustivo”; seção 2.3: “reproduções certificadas”; PF-06: “não há relatórios públicos”; seção 7 cita notícias e divulgações sem URLs específicas.

**Problema:** não há inventário suficiente para sustentar exaustividade, inexistência de publicações ou certificação independente das cópias. Ausência de resultado nas buscas realizadas não demonstra inexistência de documento. Esta auditoria não conclui que as consultas da v1 não ocorreram; aponta que sua comprovação e vinculação às afirmações estão incompletas.

**Tratamento exigido:** incluir quadro de fonte, órgão/autoria, data, URL ou arquivo local, dispositivo/trecho relevante, contribuição e limite. Distinguir leitura nova, reutilização do 2.1 e tentativa de acesso frustrada. Usar “não localizado nas buscas realizadas” quando esse for o alcance real. Preferir “reprodução institucional” sem alegar validação que não ocorreu. Não copiar para a v2 relatos de bloqueio como se fossem novos testes. Vincular as notícias mencionadas ou retirar a alegação específica.

### F19 — A entrevista não pode escolher fatos legais ou rotinas desconhecidas

**Local e trechos:** perguntas 2–4 da seção 7 perguntam se haverá classificação, se AJUS será formal ou discricionária e se o diário será em tempo real ou semanal/mensal. As etapas 3 e 5 são intituladas principalmente pela operação institucional.

**Problema:** o grill deve colher decisões reais de recorte e representação; não legitimar fatos por preferência da estudante. Classificação já tem previsão normativa. Frequência de atualização possui deveres documentados, enquanto o instante de digitação em sala não foi observado. Também não se demonstrou que AJUS seja prática informal discricionária. Além disso, o exercício exige etapas formuladas pela ótica do cidadão.

**Tratamento exigido:** preparar perguntas sobre como representar evidências e incertezas, fronteiras entre ações, desfechos, seleção de fail points e limites do recorte. Reorientar os títulos para ações/necessidades do estudante, preservando a descrição das operações nas camadas adequadas. Não iniciar nem fabricar respostas da Parte C durante a revisão B. A futura sessão deverá registrar pelo menos seis rodadas autênticas, sem atribuir à estudante relatos de campo que ela não prestou.

## Condições para verificar a v2

A v2 deve conter uma tabela **F01–F19 → corrigido / defendido com evidência / pendente → justificativa → localização do tratamento**. A defesa precisa responder ao problema concreto; a pendência precisa aparecer também na matriz e na narrativa, e não somente no checklist final. Nos achados com vários elementos, abordar cada elemento.

A pesquisa revisada deve continuar autossuficiente: identificação do serviço, jornada, cinco camadas corretamente separadas, responsabilidades, evidências, fail points e fontes. Não basta entregar uma lista de respostas à auditoria. Preservar a v1 e este relatório como registros das iterações. A segunda auditoria verificará a correspondência entre a tabela de resposta e o conteúdo efetivamente alterado.

## Registro das fontes de confronto e limites desta auditoria

Consultas realizadas em 16/11/2026. Links abaixo identificam as fontes usadas nos achados; a indicação de acesso não implica confirmação de execução nas escolas.

| Fonte | Uso e forma de acesso |
|---|---|
| [Portaria nº 16.735/2025][S1] | PDF público do repositório de matrícula, com texto extraído; arts. 15, 18–20, 23–25. |
| [Portal Matrícula Online][S2] e [serviço 585][S3] | Páginas públicas. O link de cadastro foi identificado, mas seu conteúdo dinâmico não pôde ser integralmente inspecionado pela extração; nenhum cadastro foi submetido. Páginas de calendário/informações possuem conteúdo em imagens, insuficiente para validar datas apenas pela extração textual. |
| [Portaria nº 1.133/2026][S4] | Leitura dos arquivos `contexto/fontes_2_1/doe_p12.txt` a `doe_p15.txt`, provenientes do DOE de 08/01/2026; não é nova inspeção integral da edição online. |
| [Decreto nº 90.347/2023][S5] | Leitura das extrações locais `decreto2023_p6.txt` e `decreto2023_p7.txt`, no conjunto preservado do 2.1. |
| [Inep — Situação do Aluno][S6] | Orientação pública consultada, incluindo a distinção de curso em andamento para EJA. |
| [Lei Delegada nº 48 no SAPL][S7] | Cadastro oficial consultado para data, publicação e ementa; não comprova sozinho todas as alterações organizacionais posteriores. |
| [Guimarães][S8]; [Pedralli e Cerutti-Rizzatti][S9] | Páginas dos artigos consultadas para metadados e delimitação dos estudos. |
| [CNE/CEB nº 3][S10]; [CNE/CEB nº 6][S11] | Reproduções institucionais consultadas, respectivamente IFAP e Centro Paula Souza. |
| [MEC nº 275/2026][S12] | Reprodução institucional do DOU consultada; o portal MEC Normas foi localizado, mas sua extração não forneceu texto completo nesta verificação. |
| LDB e PNE citados na v1 | Houve falhas de acesso a páginas da Câmara e limitação de leitura no Planalto. Exige-se conferência acessível na revisão; esta auditoria não certifica compilação integral atualizada dessas leis. |

[S1]: https://www.matriculaonline.al.gov.br/storage/pdfs/16_16_DI%C3%81RIO%20CRONOGRAMA%20MATR%C3%8DCULA.pdf
[S2]: https://www.matriculaonline.al.gov.br/
[S3]: https://alagoasdigital.al.gov.br/servico/585
[S4]: https://diario.imprensaoficial.al.gov.br/apinova/api/editions/viewPdf/51261
[S5]: https://www.imprensaoficial.al.gov.br/storage/files/diary/2023/03/doeal-2023-03-29-completo-bf-3satd6fvadkgkka6baewee74yf73pelwnpeztnnsv2rvtnmrr6.pdf
[S6]: https://www.gov.br/inep/pt-br/acesso-a-informacao/perguntas-frequentes/censo-escolar/situacao-do-aluno/quais-sao-as-informacoes-coletadas
[S7]: https://sapl.al.al.leg.br/norma/2450
[S8]: https://educa.fcc.org.br/scielo.php?lng=pt&nrm=iso&pid=S1981-416x2025000301252&script=sci_arttext&tlng=pt
[S9]: https://www.scielo.br/j/rbla/a/vZWw6znGkH6cFMcCPP354RG/?lang=pt
[S10]: https://ifap.edu.br/documents/1074/Res_CNE_CEB_3_2025.pdf
[S11]: https://bkpsitecpsnew.blob.core.windows.net/uploadsitecps/sites/18/2025/08/Resolucao-CNE-CEB-06_2025-07-21.pdf
[S12]: https://bkpsitecpsnew.blob.core.windows.net/uploadsitecps/sites/18/2026/04/Portaria-MEC-275_2026-03-30.pdf
