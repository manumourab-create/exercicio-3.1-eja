# Relatório de Pesquisa Inicial (v1) — Operação Atual da EJA Modular Estadual de Alagoas

**Assistente 1:** Gemini / Antigravity CLI  
**Estudante:** Rosy Emannuele Moura dos Santos Bomfim  
**Data de referência documental:** 16 de novembro de 2026  
**Finalidade:** Diagnóstico documental AS-IS da operação do serviço público de acesso e permanência na Educação de Jovens e Adultos (EJA) Modular do Ensino Médio da rede pública estadual de Alagoas, com mapeamento das cinco camadas do Service Blueprint, passagens de responsabilidade, pontos de falha e pendências analíticas.  
**Auditoria subsequente:** Assistente 2 (Codex / OpenAI).

---

## 1. Identificação do Serviço, Escopo e Limites de Análise

### 1.1. Delimitação do Serviço e Responsabilidade Institucional
O serviço objeto desta investigação é o **Acesso e Permanência na Educação de Jovens e Adultos (EJA) Modular do Ensino Médio da rede pública estadual de Alagoas**, sob gestão e responsabilidade da Secretaria de Estado da Educação de Alagoas (Seduc-AL). O serviço engloba o percurso completo do estudante adulto: desde a busca de informações, inscrição preliminar e entrega presencial de documentos para confirmação de matrícula, até a alocação em turmas modulares, frequência às aulas, recomposição pedagógica, usufruto de apoios materiais (alimentação e transporte) e desfechos modulares (conclusão, progressão, transferência, interrupção ou retorno).

### 1.2. Canais de Atendimento e Plataformas Operacionais
O atendimento público estrutura-se a partir de canais integrados e pontos presenciais:
- **Canal Digital Externo:** Portal Matrícula Online (`matriculaonline.al.gov.br`), plataforma pública disponibilizada aos cidadãos para cadastro, seleção de preferências de unidade escolar e acompanhamento do resultado da pré-matrícula;
- **Pontos de Atendimento Presencial:** Secretarias Escolares das unidades de ensino da rede estadual distribuídas no território alagoano, encarregadas do recebimento físico de documentos e confirmação da matrícula;
- **Polos Regionais de Apoio:** Unidades escolares polo e sedes das Gerências Especiais de Educação (GEEs), que prestam suporte técnico-operacional presencial aos cidadãos sem acesso à internet ou com dificuldades de letramento digital (Portaria SEDUC nº 16.735/2025, art. 13);
- **Sistemas de Informação e Gestão de Retaguarda:** Sistema de Gestão Educacional de Alagoas (**SAGEAL**), plataforma corporativa estadual de escrituração, enturmação, registro diário de chamadas docentes e notas; e o **Educacenso**, plataforma censitária federal gerenciada pelo Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (Inep/MEC).

### 1.3. Recorte do Usuário e Condições de Vida
O público-alvo é composto por **pessoas com 18 anos ou mais** que buscam iniciar ou concluir o Ensino Médio por meio da organização modular (Portaria SEDUC nº 16.735/2025, arts. 7º e 20, II; LDB nº 9.394/1996, art. 37, § 1º, I). Em estrita consonância com as deliberações do Exercício 2.1 e os requisitos de integridade metodológica:
- Não se pressupõe vínculo formal de emprego, trabalho com carteira assinada ou estabilidade de renda;
- Reconhece-se a pluralidade de situações: trabalhadores informais, diaristas, autônomos, desempregados e cidadãos com responsabilidades prioritárias de cuidados domésticos e familiares;
- Não se assume que todos frequentem o turno noturno, admitindo-se a existência de ofertas modulares diurnas conforme a demanda e capacidade instalada das unidades escolares.

### 1.4. Limites Territoriais e Postura Analítica AS-IS
A análise incide sobre o **fluxo geral da rede estadual de ensino de Alagoas**, sem fixar uma unidade escolar específica (como o CEJA Paulo Freire ou o CEJA Professor Remy Maia em Maceió) como modelo universal. Isso evita generalizações empíricas abusivas sobre disponibilidade de vagas, composição etária de turmas ou rotas locais.

O presente relatório adota uma **postura estritamente diagnóstica AS-IS**, mapeando a operação documentalmente demonstrável ou analiticamente inferida em 16 de novembro de 2026. Fica vedada qualquer antecipação de redesenho To-Be, introdução de propostas de melhoria ou apresentação de desejos normativos como realidades fáticas já operantes.

---

## 2. Método, Fontes Consultadas e Limitações de Acesso

### 2.1. Metodologia e Data de Corte
A pesquisa foi desenvolvida por meio de exame documental exaustivo em fontes primárias estaduais e federais, cruzamento normativo e inferência analítica fundamentada de engenharia de serviços públicos. A data de referência e corte é **16 de novembro de 2026**.

Para evitar anacronismos e erros de categoria, a metodologia distingue com rigor:
1. **Publicação:** Data em que o ato oficial foi veiculado no órgão de imprensa oficial;
2. **Vigência Normativa:** Período no qual o ato produz efeitos jurídicos formais obrigatórios;
3. **Período de Execução:** Calendário factual em que as atividades de campo ou de balcão ocorrem.

*Ressalva sobre calendários:* As datas previstas para o processo ordinário de matrícula de início de 2026 já transcorreram. O encerramento desse cronograma inicial não demonstra a inexistência de matrículas ativas em 16/11/2026, uma vez que a Portaria SEDUC nº 16.735/2025 prevê expressamente em seu art. 24 a possibilidade de **ingresso contínuo na EJA ao longo do período letivo**, bem como fluxos contínuos de reenturmação (art. 23).

### 2.2. Fontes Documentais Primárias e Secundárias Consultadas
1. **Portaria SEDUC nº 16.735/2025** (DOEAL de 26/11/2025, pp. 26–32): Fixa normas e procedimentos para a matrícula no ano letivo de 2026 na Rede Pública Estadual de Alagoas.
2. **Portaria SEDUC nº 1.133/2026** (DOEAL de 08/01/2026, pp. 12–15): Estabelece diretrizes gerais de organização, gestão e funcionamento do ano letivo de 2026 nas unidades estaduais, disciplinando o SAGEAL, calendários, Conselho de Classe e apoios materiais.
3. **Decreto Estadual nº 90.347/2023** (DOEAL de 29/03/2023, pp. 5–7): Institui o Programa Estadual de Busca Ativa Escolar — BUSCAE ALAGOAS, disciplinando procedimentos de acompanhamento de frequência, atribuições docentes/gestoras e a Ausência Justificada com Critérios (AJUS).
4. **Lei Delegada Estadual nº 48/2022** (republicada no DOEAL de 18/08/2023, p. 47): Dispõe sobre a estrutura da Seduc-AL, demonstrando a vinculação da Gerência Especial de Gestão de Vagas (GEGEV) à Superintendência da Rede Estadual de Ensino.
5. **Ficha do Serviço nº 585 do Portal Alagoas Digital** (`alagoasdigital.al.gov.br/servico/585`): Descreve os canais de solicitação de matrícula e os contatos institucionais gerais da Seduc-AL.
6. **Legislação Federal e Diretrizes Nacionais:**
   - Lei Federal nº 9.394/1996 (LDB atualizada), especialmente arts. 3º (inciso XIII), 4º (inciso VIII), 10 (inciso VII), 24 (inciso VI), 37 e 38;
   - Resoluções CNE/CEB nº 3/2025 (DOU de 09/04/2025, seção 1, p. 16) e nº 6/2025 (DOU de 21/07/2025, seção 1, p. 39), que aprovaram as novas Diretrizes Operacionais Nacionais da EJA e revogaram expressamente a Resolução CNE/CEB nº 1/2021;
   - Decreto Federal nº 12.048/2024 (Pacto Nacional pela Superação do Analfabetismo e Qualificação da EJA), Lei Federal nº 15.388/2026 (PNE, Meta 11) e Portaria MEC nº 275/2026 (Instituição do Cadastro Nacional da EJA — CadEJA).
7. **Literatura Acadêmica Pertinente:**
   - Guimarães (2025): Revisão de 22 pesquisas acadêmicas (teses e dissertações) mapeando fatores de permanência e abandono na EJA (trabalho, família, acolhimento institucional e mobilidade);
   - Pedralli e Cerutti-Rizzatti (2013): Estudo qualitativo sobre pertencimento e letramento escolar em adultos, empregado como subsídio para formulação de hipóteses de acolhimento pedagógico.

### 2.3. Transparência sobre Limitações Reais de Acesso às Fontes
Em observância estrita ao princípio da verdade real e às regras da atividade:
- **Acesso restrito ao SAGEAL:** Os módulos de enturmação, chamadas diárias e histórico do sistema corporativo SAGEAL operam sob autenticação fechada por login institucional de servidores, inviabilizando a inspeção externa direta de suas telas de operação e regras de negócio codificadas;
- **Ausência de manuais públicos de TI:** Não se localizou em repositório público manual de parametrização do portal Matrícula Online ou contrato formal detalhado especificando se a manutenção técnica é realizada pelo Instituto de Tecnologia em Informática e Informação do Estado de Alagoas (ITEC/AL), por equipe própria da Seduc ou por empresa terceirizada;
- **Instabilidade e bloqueios em servidores federais:** Tentativas de acesso direto aos portais federais (MEC e Imprensa Nacional) apresentaram bloqueios por validação automatizada de requisições, exigindo a consulta a reproduções certificadas de diários oficiais (como as disponibilizadas por instituições públicas de ensino);
- **Inexistência de dados locais de campo:** Não foram realizadas entrevistas com equipes escolares locais nem visitas às escolas no âmbito deste estudo. Quaisquer afirmações relativas à execução real nas salas de aula são tratadas como hipóteses de campo ou pendências empíricas, e nunca como fatos documentados.

---

## 3. Narrativa da Jornada Operacional do Estudante

A experiência do cidadão adulto ao buscar e cursar a EJA Modular do Ensino Médio é modelada em cinco etapas analíticas fundamentadas nas normas estaduais:

```
[Etapa 1] Busca de Informação e Consulta sobre Vagas
   │
   ▼
[Etapa 2] Solicitação de Vaga e Confirmação Presencial da Matrícula
   │
   ▼
[Etapa 3] Ingresso na Turma Modular, Acolhimento e Enturmação
   │
   ▼
[Etapa 4] Acompanhamento Pedagógico, Frequência e Apoios Materiais
   │
   ▼
[Etapa 5] Avaliação Colegiada, Desfechos Modulares, Certificação ou Retorno
```

### Etapa 1: Busca de Informação e Consulta sobre Vagas
O cidadão de 18 anos ou mais, motivado pela necessidade de reinserção educacional, qualificação profissional ou exigência do mercado de trabalho, inicia sua busca por oportunidades escolares. Ele depara-se com divulgações institucionais da Seduc-AL, notícias em portais de comunicação ou informações boca a boca em sua comunidade. Ao buscar os canais digitais, depara-se com o portal Matrícula Online. Caso não disponha de dispositivo móvel, computador ou pacote de dados, o cidadão procura diretamente o balcão de uma escola estadual próxima de sua residência ou trabalho, ou uma Gerência Especial de Educação (GEE), onde deve receber orientação sobre as escolas que ofertam a EJA Modular e os cronogramas de atendimento.

### Etapa 2: Solicitação de Vaga e Confirmação Presencial da Matrícula
A inscrição inicial exige o preenchimento de formulário no portal Matrícula Online, com indicação de até 3 opções de unidades escolares e turnos. Para os estudantes com barreiras de letramento digital ou sem conectividade, a Portaria SEDUC nº 16.735/2025 (art. 13) prevê que as escolas e as GEEs atuem como polos presenciais de apoio ao preenchimento. Processada a alocação preliminar, o estudante obtém um número de protocolo/resultado e tem prazo fixado para comparecer pessoalmente à secretaria da escola designada. No balcão, entrega os documentos obrigatórios: documento de identificação com foto (RG/CIN), CPF, comprovante de residência atualizado e comprovante de escolaridade anterior (histórico escolar ou declaração provisória de transferência). A secretaria confere a documentação física, lança a validação no SAGEAL e emite o comprovante definitivo de matrícula para o estudante.

### Etapa 3: Ingresso na Turma Modular, Acolhimento e Enturmação
Efetivada a matrícula na secretaria, a equipe gestora e a secretaria procedem à enturmação no SAGEAL, alocando o estudante nos módulos curriculares específicos a serem cursados (considerando eventual aproveitamento de estudos e conhecimentos prévios, conforme arts. 24 e 25 da Portaria nº 16.735/2025). No primeiro dia letivo presencial, o estudante comparece à unidade escolar, localiza sua sala de aula por meio de murais ou listas fornecidas na entrada, e é recebido pela equipe gestora, coordenação pedagógica e professores regentes. Nesse momento inicial, deve ocorrer a apresentação da dinâmica modular, o diagnóstico preliminar de conhecimentos e a pactuação de rotinas.

### Etapa 4: Acompanhamento Pedagógico, Frequência e Apoios Materiais
O estudante frequenta as aulas presenciais nos dias e horários pactuados. Os professores realizam o registro diário de frequência e conteúdos no diário de classe eletrônico do SAGEAL (Portaria SEDUC nº 1.133/2026, arts. 9º e 10). Em caso de faltas decorrentes de jornadas laborais extenuantes, turnos de trabalho rotativos ou adoecimento na família, a Portaria nº 1.133/2026 (arts. 39 e 44) e o Decreto nº 90.347/2023 preveem a atuação da coordenação pedagógica para orientação e recomposição de aprendizagens. Paralelamente, a permanência do estudante no recinto escolar durante o turno é viabilizada pelo fornecimento da merenda escolar (PNAE / Programa Mais Merenda, conforme Portaria nº 1.133/2026, arts. 61–63) e, quando residente em áreas abrangidas por linhas de transporte, pelo transporte escolar gerido pela Seduc em cooperação municipal (art. 6º).

### Etapa 5: Avaliação Colegiada, Desfechos Modulares, Certificação ou Retorno
Ao final de cada módulo ou período letivo, o corpo docente e a equipe pedagógica reúnem-se no Conselho de Classe (Pré-Conselho, Conselho e Pós-Conselho, arts. 40–42 da Portaria nº 1.133/2026) para analisar o rendimento global dos estudantes. A secretaria escolar procede à escrituração oficial dos resultados no SAGEAL. Nessa fase, a rede processa diferentes desfechos educacionais:
- **Conclusão de Módulo:** O estudante obtém aprovação no módulo cursado e segue matriculado para os módulos subsequentes;
- **Conclusão de Ensino Médio:** O estudante integraliza todos os módulos da matriz curricular, e a secretaria escolar emite o Histórico Escolar e o Certificado de Conclusão do Ensino Médio, registrando a publicação de concluintes (art. 8º, II);
- **Progressão Parcial:** Caso reprove em componentes pontuais, assegura-se a progressão parcial nos termos do art. 39, § 2º, III da Portaria nº 1.133/2026;
- **Transferência:** Emissão de declaração e guia de transferência a pedido do estudante;
- **Interrupção de Estudos / Abandono Formal:** Quando esgotadas as ações do programa BUSCAE ALAGOAS sem retorno do estudante, o registro da situação de movimentação é consolidado administrativamente no SAGEAL e reportado ao Educacenso/Inep;
- **Retorno aos Estudos:** Estudantes que interromperam os estudos em períodos anteriores buscam a secretaria escolar ou o portal para retorno, com aproveitamento das disciplinas e módulos já integralizados.

---

## 4. Matriz Preliminar das Cinco Camadas e Três Linhas do Service Blueprint

A tabela abaixo estrutura as interações operacionais ao longo das cinco etapas da jornada, classificando rigorosamente as ações (e não instituições completas) entre as cinco camadas do Service Blueprint e evidenciando as três linhas de demarcação funcional.

| Camada do Blueprint | Etapa 1: Busca e Orientação de Vagas | Etapa 2: Solicitação e Confirmação de Matrícula | Etapa 3: Ingresso na Turma e Acolhimento | Etapa 4: Frequência, Aprendizagem e Apoios | Etapa 5: Avaliação, Desfecho e Retorno |
|---|---|---|---|---|---|
| **EVIDÊNCIAS FÍSICAS E DIGITAIS** *(Sinais e interfaces percebidos pelo estudante)* | - Cartazes de divulgação e avisos institucionais;<br>- Interface web do portal Matrícula Online;<br>- Balcão de atendimento e folder informativo na escola/GEE. | - Tela de confirmação e número de protocolo web;<br>- Documentos pessoais físicos (RG, CPF, residência);<br>- Recibo impresso de matrícula assinado pela secretaria. | - Listas de turmas afixadas em murais escolares;<br>- Sala de aula física e carteiras;<br>- Materiais didáticos e apostilas modulares distribuídos. | - Quadro de sala e caderno do aluno;<br>- Refeição escolar servida no refeitório;<br>- Veículo do transporte escolar (ônibus/van);<br>- Notificação/contato de busca ativa (telefone/carta). | - Boletim escolar impresso ou emitido via portal;<br>- Atas e listas de concluintes publicadas;<br>- Certificado de Conclusão e Histórico Escolar em papel oficial. |
| **--- LINHA DE INTERAÇÃO ---** | | | | | |
| **AÇÕES DO CIDADÃO** *(Passos concretos dados pelo estudante adulto)* | - Consulta vagas e cronogramas no portal ou presencialmente;<br>- Solicita orientações sobre turnos e oferta modular na escola/GEE. | - Preenche formulário de pré-matrícula no portal;<br>- Reúne documentação pessoal e escolar;<br>- Comparece à secretaria escolar para entregar os originais/cópias. | - Dirige-se à escola no primeiro dia letivo;<br>- Localiza sua sala no mural;<br>- Participa do momento de acolhimento e dialoga com docentes. | - Frequenta as aulas presenciais;<br>- Informa impedimentos ou dificuldades de horário;<br>- Alimenta-se da merenda escolar;<br>- Realiza atividades e estudos de recomposição. | - Realiza avaliações e recuperações;<br>- Participa da devolutiva do Conselho de Classe;<br>- Solicita e retira histórico escolar ou certificado na secretaria. |
| **--- LINHA DE VISIBILIDADE ---** | | | | | |
| **FRONTSTAGE** *(Ações visíveis da equipe de linha de frente)* | - Atendente da secretaria escolar ou da GEE tira dúvidas sobre vagas e documentação exigida. | - Secretário/Assistente confere documentos físicos no balcão de atendimento e entrega recibo de matrícula. | - Equipe gestora e coordenadores recepcionam os alunos na entrada;<br>- Docentes acolhem estudantes em sala de aula. | - Docentes ministram aulas e realizam a chamada diária presencial;<br>- Coordenador pedagógico atende estudante infrequente;<br>- Merendeiras servem a refeição. | - Docente entrega resultados de provas e trabalhos;<br>- Gestão/Coordenação realiza atendimento individual de devolutiva pedagógica;<br>- Secretaria entrega o certificado no balcão. |
| **--- LINHA DE INTERAÇÃO INTERNA ---** | | | | | |
| **BACKSTAGE** *(Ações de bastidores longe da vista do usuário)* | - Gestão escolar informa capacidade física e demanda potencial à GEE/Seduc. | - Secretaria escolar confere dados no SAGEAL, valida a inscrição e efetiva o cadastro de matrícula no sistema. | - Secretaria realiza enturmação no módulo específico no SAGEAL;<br>- Coordenação e docentes analisam histórico para aproveitamento de estudos. | - Docentes lançam frequência e notas no diário eletrônico do SAGEAL;<br>- Gestão e coordenação monitoram infrequência e emitem relatórios do BUSCAE;<br>- Equipe escolar executa o Pré-Conselho. | - Reunião deliberativa do Conselho de Classe escolar (art. 40);<br>- Secretaria escritura notas finais e atas de resultados no SAGEAL;<br>- Homologação de concluintes no sistema. |
| **PROCESSOS DE SUPORTE** *(Sistemas, infraestrutura e governança interna)* | - Servidores e infraestrutura do portal Matrícula Online;<br>- Parâmetros de oferta de vagas definidos pela GEGEV/Seduc. | - Banco de dados e regras de negócio do SAGEAL;<br>- Suporte técnico de retaguarda de TI (Seduc/ITEC). | - Parametrização das matrizes curriculares modulares no SAGEAL;<br>- Inspeção Educacional da GEE homologa calendários escolares. | - Logística de entrega de gêneros alimentícios (PNAE/Seduc);<br>- Contratos e convênios municipais de transporte escolar;<br>- Manutenção de servidores de internet e energia na escola. | - Rotinas de fechamento do SAGEAL;<br>- Exportação e migração de dados acadêmicos para a plataforma Educacenso (Inep/MEC);<br>- Tramitação de registros no SEI/Seduc. |

---

## 5. Passagens de Responsabilidade e Handoffs entre Atores e Sistemas

A investigação operacional identificou seis pontos críticos de passagem de responsabilidade (*handoffs*) entre atores e ferramentas tecnológicas:

```
[Cidadão] ──(1) Pré-inscrição──> [Portal Matrícula Online]
                                       │
                                       ▼ (2) Alocação preliminar
[Cidadão] ──(3) Entrega docs───> [Secretaria Escolar] ──(4) Efetivação──> [SAGEAL]
                                       │
                                       ▼ (5) Listas de turmas
                                 [Coordenação / Docentes]
                                       │
                                       ▼ (6) Registro de faltas / notas
                                 [Conselho de Classe / SAGEAL] ──(7) Fechamento──> [Educacenso]
```

### 5.1. Detalhamento dos Fluxos de Passagem
1. **Handoff 1: Do Cidadão para o Portal Matrícula Online (ou Polo de Apoio)**  
   *Quem entrega:* Estudante adulto.  
   *Quem recebe:* Portal Matrícula Online (ou atendente de polo presencial nas escolas/GEEs).  
   *O que é conferido:* CPF, data de nascimento (verificação da idade mínima de 18 anos completos), seleção de opções de escolas/turnos e dados de contato.  
   *Dependência:* Conexão estável à internet, integridade da base da Receita Federal/CPF e disponibilidade do portal.
2. **Handoff 2: Do Portal para a Secretaria Escolar / Gestão**  
   *Quem entrega:* Sistema Matrícula Online (via listas de candidatos alocados).  
   *Quem recebe:* Equipe da Secretaria Escolar e Direção da Unidade de Ensino.  
   *O que é conferido:* Conferência física de documentos originais (RG, CPF, comprovante de residência e histórico escolar/declaração).  
   *Resposta ao cidadão:* Emissão do recibo de matrícula assinado ou protocolo de pendência documental.
3. **Handoff 3: Da Secretaria Escolar para o SAGEAL**  
   *Quem entrega:* Assistente/Secretário Escolar.  
   *Quem recebe:* Base de dados do SAGEAL.  
   *O que é registrado:* Validação do status de "inscrito" para "matriculado", vinculação ao livro de matrícula e alocação na turma modular.  
   *Dependência:* Disponibilidade do SAGEAL e parametrização prévia das turmas pela gestão e pela GEE.
4. **Handoff 4: Da Secretaria Escolar para a Coordenação Pedagógica e Docentes**  
   *Quem entrega:* Secretaria Escolar (via relatórios e diários do SAGEAL).  
   *Quem recebe:* Coordenação Pedagógica e Professores regentes.  
   *O que é conferido:* Listagem oficial de alunos enturmados, identificação de necessidades específicas e histórico de componentes cursados para aproveitamento de estudos.
5. **Handoff 5: Dos Docentes para a Coordenação Pedagógica, Gestão e SAGEAL**  
   *Quem entrega:* Docente em regência de classe.  
   *Quem recebe:* Diário eletrônico do SAGEAL, Coordenação Pedagógica e Gestão Escolar.  
   *O que é registrado:* Chamada diária presencial e relação de alunos com faltas consecutivas ou alternadas. Em caso de 3 faltas na semana, acionamento do fluxo do Decreto nº 90.347/2023 (BUSCAE).
6. **Handoff 6: Da Equipe Escolar para o Conselho de Classe e Sistemas Oficiais (SAGEAL / Educacenso)**  
   *Quem entrega:* Docentes e Coordenação Pedagógica (relatórios de rendimento e assiduidade).  
   *Quem recebe:* Colegiado do Conselho de Classe (Pré-Conselho e Conselho).  
   *O que é conferido:* Deliberação sobre aprovação no módulo, progressão parcial ou retenção.  
   *Encaminhamento subsequente:* Secretaria escritura as atas e notas no SAGEAL; no período censitário, os dados de movimentação e rendimento são migrados e declarados no sistema federal Educacenso.

### 5.2. Diferenciação Estrutural de Sistemas e Plataformas
- **Portal Matrícula Online (`matriculaonline.al.gov.br`):** Canal digital público voltado ao cidadão para captação de inscrições e triagem preliminar de vagas na rede. Não realiza enturmação definitiva nem controle de frequência.
- **SAGEAL:** Sistema de Gestão Educacional de Alagoas. Software corporativo central da Seduc-AL, de uso obrigatório diário pelas escolas estaduais (Portaria nº 1.133/2026, art. 9º). Concentra a escrituração acadêmica, diário de classe eletrônico, matrícula, controle de frequência e base de cálculo para repasses de merenda e transporte.
- **Educacenso:** Plataforma censitária nacional do Inep/MEC. Coleta anualmente dados agregados e individualizados da educação básica (matrícula inicial e situação do aluno/rendimento e movimento). Não é um sistema de atendimento em tempo real.

### 5.3. Ressalvas Operacionais e Não Presunções
- **Ausência de integração automática por API:** Não há comprovação de sincronização em tempo real entre o portal Matrícula Online e o SAGEAL; a validação final da vaga é condicionada ao processamento manual e conferência documental pela secretaria escolar;
- **Retaguarda Técnica Pendente:** A governança tecnológica da infraestrutura (servidores, sustentação e banco de dados) permanece classificada como função técnica a identificar, não havendo documento público detalhando se os operadores são servidores do Estado, do ITEC/AL ou terceirizados;
- **Atribuições da GEGEV em 2026:** A Gerência Especial de Gestão de Vagas tem existência documentada na estrutura organizacional de 2023, mas as portarias de 2025/2026 não delimitam detalhadamente quais atos de parametrização e autorização de turmas cabem exclusivamente a ela.

---

## 6. Pontos de Falha (Fail Points) Codificados e Classificados por Nível de Evidência

A matriz a seguir mapeia os pontos críticos da jornada onde a operação é vulnerável a atritos, atrasos, exclusões ou abandono escolar. Cada ponto de falha recebe classificação categórica de seu status probatório:

| Código | Etapa e Camada | Descrição Operacional da Falha | Efeito Potencial sobre o Estudante | Fundamento e Status de Evidência |
|---|---|---|---|---|
| **[PF-01]** | Etapa 1 / 2<br>*Evidências Físicas / Ações do Cidadão* | **Barreira de Inclusão Digital e Letramento:** Exigência de inscrição prévia em portal web para acesso à vaga, gerando atrito para adultos sem conectividade, sem computador ou com dificuldades de navegação digital. | Desistência da solicitação antes da conclusão do cadastro ou perda do prazo da pré-matrícula. | **Risco analítico inferido.** A Portaria SEDUC nº 16.735/2025 (art. 13) tenta mitigar a barreira instituindo polos presenciais de apoio nas escolas e GEEs, o que comprova o reconhecimento do risco pela administração. |
| **[PF-02]** | Etapa 2<br>*Frontstage / Backstage* | **Rigidez Documental de Entrada:** Exigência de apresentação presencial de histórico escolar original ou declaração emitida pela escola anterior dentro de prazo exíguo após a inscrição online. | Impossibilidade de confirmação da matrícula por estudantes afastados da escola há muitos anos ou oriundos de outros municípios/estados cujas escolas de origem fecharam. | **Risco analítico inferido.** Portaria SEDUC nº 16.735/2025, arts. 15 e 16. A ausência de mecanismos ágeis de convalidação no ato do atendimento gera impedimento burocrático de ingresso. |
| **[PF-03]** | Etapa 2<br>*Frontstage* | **Descompasso de Horário no Atendimento de Balcão:** Funcionamento da secretaria escolar restrito aos turnos diurnos (matutino e vespertino) em determinadas unidades escolares que não mantêm plantão pleno no início do turno noturno. | Estudante trabalhador não consegue comparecer para entrega dos documentos comprobatórios sem faltar ao trabalho ou perder remuneração diária. | **Risco analítico inferido e Lacuna de informação.** A Portaria nº 1.133/2026 não fixa expressamente o horário obrigatório de atendimento das secretarias no noturno, dependendo de rotina local não observada. |
| **[PF-04]** | Etapa 3<br>*Backstage / Suporte* | **Ruptura de Turma por Reenturmação ou Limite Numérico:** Reorganização, fusão ou fechamento de turmas modulares com baixa frequência ou que não atinjam o parâmetro de 40 a 50 estudantes previsto em norma. | Deslocamento forçado do estudante para outra escola distante, alteração de turno ou cancelamento da oferta do módulo no qual o estudante necessitava se matricular. | **Risco analítico inferido de previsão normativa.** Portaria SEDUC nº 16.735/2025, art. 23 (autoriza expressamente a reenturmação por critérios quantitativos). |
| **[PF-05]** | Etapa 4<br>*Frontstage / Backstage* | **Rigidez de Frequência frente a Demandas Laborais:** Incompatibilidade entre as jornadas de trabalho (plantões, escalas rotativas, trabalho informal) ou cuidados com dependentes e a exigência de frequência presencial contínua. | Acúmulo de faltas consecutivas, desmotivação e risco iminente de abandono formal. | **Risco analítico inferido e Lacuna normativa.** O Decreto nº 90.347/2023 prevê a Ausência Justificada com Critérios (AJUS), mas sua validade e regras operacionais após as Resoluções CNE/CEB nº 3/2025 e nº 6/2025 permanecem em aberto. |
| **[PF-06]** | Etapa 4<br>*Processos de Suporte* | **Inconstância na Cobertura de Alimentação Escolar Noturna:** Dificuldades logísticas ou operacionais no fornecimento regular de refeições adequadas para os estudantes da EJA que chegam diretamente do trabalho. | Fadiga física, perda de rendimento na aprendizagem e desestímulo à permanência no turno noturno. | **Risco analítico inferido e Lacuna de execução local.** Portaria SEDUC nº 1.133/2026, arts. 61–63 (prevê PNAE e Mais Merenda, mas não há relatórios públicos sobre cobertura real noturna em cada escola). |
| **[PF-07]** | Etapa 4<br>*Processos de Suporte* | **Descompasso de Rotas no Transporte Escolar Noturno:** Falta de adequação dos itinerários e horários dos veículos escolares às necessidades dos estudantes da EJA residentes na zona rural ou periferias. | Impossibilidade física de retorno seguro para casa após o término das aulas noturnas, forçando a evasão. | **Risco analítico inferido e Lacuna de execução local.** Portaria SEDUC nº 1.133/2026, art. 6º e LDB art. 10, VII. Oferta condicionada a convênios municipais sem dados públicos consolidados. |
| **[PF-08]** | Etapa 4 / 5<br>*Backstage / Suporte* | **Descompasso de Lançamento de Frequência no SAGEAL:** Atraso de docentes no registro diário de chamadas, gerando identificação tardia de estudantes infrequentes pelo programa BUSCAE. | A busca ativa só é disparada após o estudante já ter se desconectado da rotina escolar há semanas, inviabilizando a recomposição pedagógica. | **Risco analítico inferido.** O Decreto nº 90.347/2023 exige registro diário e comunicação em 3 faltas na semana, mas a dependência da digitação docente individual é um gargalo operacional conhecido. |
| **[PF-09]** | Etapa 5<br>*Backstage / Educacenso* | **Rotulação Administrativa de Interrupção como Abandono:** Registro genérico de "abandono" no SAGEAL/Educacenso para estudantes que deixaram de frequentar devido a migração de trabalho ou problemas familiares, sem conclusão de busca ativa. | Distorção dos dados estatísticos, bloqueio administrativo para retorno ágil e falta de políticas direcionadas de reinserção. | **Lacuna de informação e Risco analítico inferido.** Inep (Situação do Aluno) diferencia rendimento e movimento, mas a prática documental das escolas estaduais alagoanas na baixa de matrículas requer comprovação empírica. |

---

## 7. Quadro de Distinção Metodológica e Questões para a Entrevista (`/grill-me`)

Para assegurar total transparência sobre a solidez dos achados, a tabela abaixo categoriza as dimensões investigadas em quatro níveis de densidade epistêmica:

| Dimensão Operacional | 1. Previsão Normativa Formal | 2. Informação Operacional Pública | 3. Inferência Analítica Fundamentada | 4. Execução Local Não Verificada |
|---|---|---|---|---|
| **Acesso e Inscrição** | Portaria SEDUC nº 16.735/2025 (regras de matrícula, idade mínima de 18 anos, polos nas GEEs/escolas). | Portal Matrícula Online e Ficha Alagoas Digital nº 585 (endereço web, lista geral de contatos). | Barreira digital para cidadãos sem conectividade ou sem RG/histórico em mãos no ato da inscrição. | Disponibilidade real de atendentes para auxiliar a inscrição online em cada escola polo da rede estadual. |
| **Enturmação e Módulos** | Portaria SEDUC nº 16.735/2025, arts. 20, 23 e 24 (turmas de 40-50 alunos, ingresso contínuo, reenturmação). | Notícias institucionais sobre início do ano letivo estadual de 2026 em blocos cronológicos. | Reenturmação forçada gera atrito de horários e desistência de trabalhadores com horários inflexíveis. | Frequência efetiva e tamanho real das salas de aula da EJA Modular nas escolas estaduais em novembro de 2026. |
| **Frequência e Busca Ativa** | Decreto Estadual nº 90.347/2023 (BUSCAE Alagoas, diário eletrônico diário, contato após 3 faltas). | Portal da Educação com página do programa de busca ativa (`educacao.al.gov.br`). | O acionamento da busca ativa depende criticamente do ritmo individual de digitação dos docentes no SAGEAL. | Efetividade dos contatos telefônicos ou visitas domiciliares a estudantes adultos infrequentes. |
| **Tratamento de Ausências (AJUS)** | Decreto nº 90.347/2023, art. 6º, § 6º (ciência de Ausência Justificada com Critérios para adultos). | Nenhuma publicação operacional aberta descrevendo critérios atuais pós-2025. | Com a revogação da Resolução CNE/CEB 1/2021 pela CNE/CEB 3/2025, o status da AJUS é juridicamente incerto. | Existência de formulário ou protocolo ativo de AJUS operando na secretaria das escolas estaduais em 2026. |
| **Alimentação Escolar** | Portaria SEDUC nº 1.133/2026, arts. 61–63 (obrigatoriedade PNAE, Mais Merenda, combate à fome). | Divulgações da Superintendência de Alimentação Escolar sobre aquisição da agricultura familiar. | Estudantes da noite sofrem maior risco de desabastecimento ou substituição por lanches frios não nutritivos. | Tipo de alimentação efetivamente servida no intervalo das turmas noturnas da EJA em escolas polo. |
| **Transporte Escolar** | LDB art. 10, VII e Portaria SEDUC nº 1.133/2026, arts. 6º e 9º (transporte compartilhado/SAGEAL). | Registro no SAGEAL subsidia transporte de estudantes estaduais. | Falta de linhas específicas no horário de término do noturno (21h30–22h) gera evasão de alunos periféricos. | Existência de contratos ou rotas ativas atendendo as unidades escolares estaduais à noite. |
| **Retaguarda Técnica** | Lei Delegada nº 48/2022 (criação da GEGEV e órgãos internos da Seduc-AL). | Menção ao SAGEAL e ao Educacenso nas portarias anuais da Seduc. | A sustentação e o desenvolvimento do SAGEAL dependem de cooperação técnica ou contrato de TI a identificar. | Identidade institucional e capacidade de resposta da equipe de suporte do SAGEAL para corrigir erros de enturmação. |

### Questões Orientadoras para a Entrevista (`/grill-me`)
Com base no quadro de incertezas operacionais acima delimitado, formulam-se as seguintes perguntas concretas para deliberação na futura sessão `/grill-me` com a estudante Rosy:

1. **Delimitação Territorial da Jornada:** O Service Blueprint final deve continuar retratando o fluxo sistêmico da rede estadual como um todo ou deve adotar uma unidade de referência concreta (ex.: CEJA Paulo Freire ou uma escola da 1ª GEE) para permitir maior aderência aos dados físicos do espaço escolar?
2. **Tratamento das Barreiras de Entrada:** Na Etapa 2, como modelar o caso do estudante adulto que não possui o histórico escolar do Ensino Fundamental? O blueprint deve considerar o fluxo condicional de realização de prova de nivelamento/classificação no início do módulo?
3. **Representação da AJUS no Blueprint:** Diante da revogação das normas federais antigas e da menção expressa no Decreto nº 90.347/2023, como representar a compensação de ausências: como um procedimento formal documentado no frontstage/backstage ou como uma prática discricionária e informal da gestão escolar?
4. **Linhas de Handoff entre Docentes e SAGEAL:** No acompanhamento da frequência (Etapa 4), o blueprint deve modelar o diário de classe eletrônico como alimentado em tempo real em sala de aula (exigindo infraestrutura de rede) ou como digitação assíncrona semanal/mensal nos bastidores?
5. **Apoios Materiais (Alimentação e Transporte):** Essas duas camadas devem constar como componentes mandatórios do blueprint AS-IS da EJA Modular ou devem ser demarcadas graficamente como fluxos estritamente condicionais à oferta local da escola?
6. **Desfechos Diferenciados:** Na Etapa 5, como representar graficamente a distinção entre a conclusão de um único módulo letivo (que reconduz o aluno à Etapa 3/4) e a conclusão integral do Ensino Médio (que encerra a jornada com emissão de certificado)?
7. **Papel Atribuído à Retaguarda Técnica:** A equipe de suporte do portal e do SAGEAL deve ser representada como um ator corporativo genérico ou sua ausência de especificação deve ser explicitada visualmente como ponto cego da sustentação do serviço?
8. **Fluxo de Retorno aos Estudos:** Como deve ser posicionada a reentrada do estudante que interrompeu os estudos? Trata-se de um novo ciclo iniciando na Etapa 1 ou de um atalho administrativo direto na Etapa 2/3 com aproveitamento no SAGEAL?

---

## 8. Referências Documentais e Rastreabilidade

1. **Alagoas. Secretaria de Estado da Educação (SEDUC-AL).** *Portaria SEDUC nº 16.735, de 25 de novembro de 2025.* Dispõe sobre as diretrizes, procedimentos e cronograma para a realização da matrícula na Rede Pública Estadual de Ensino de Alagoas para o ano letivo de 2026. Diário Oficial do Estado de Alagoas, Maceió, 26 nov. 2025, pp. 26–32. Cópia institucional consultada via repositório de matrícula: [DOE Cronograma Matrícula](https://www.matriculaonline.al.gov.br/storage/pdfs/16_16_DI%C3%81RIO%20CRONOGRAMA%20MATR%C3%8DCULA.pdf).
2. **Alagoas. Secretaria de Estado da Educação (SEDUC-AL).** *Portaria SEDUC nº 1.133, de 06 de janeiro de 2026.* Estabelece diretrizes para a organização e o funcionamento do ano letivo de 2026 na Rede Pública Estadual de Ensino de Alagoas. Diário Oficial do Estado de Alagoas, Maceió, 08 jan. 2026, pp. 12–15. [Edição Eletrônica DOEAL nº 51261](https://diario.imprensaoficial.al.gov.br/apinova/api/editions/viewPdf/51261).
3. **Alagoas. Governador do Estado.** *Decreto Estadual nº 90.347, de 28 de março de 2023.* Dispõe sobre o Programa Estadual de Busca Ativa Escolar – BUSCAE ALAGOAS para o combate ao abandono e à evasão escolar e os procedimentos para o acompanhamento da frequência escolar da Rede Pública de Ensino de Alagoas. Diário Oficial do Estado de Alagoas, Maceió, 29 mar. 2023, pp. 5–7. [Edição Eletrônica DOEAL 29/03/2023](https://www.imprensaoficial.al.gov.br/storage/files/diary/2023/03/doeal-2023-03-29-completo-bf-3satd6fvadkgkka6baewee74yf73pelwnpeztnnsv2rvtnmrr6.pdf).
4. **Alagoas. Governador do Estado.** *Lei Delegada nº 48, de 10 de fevereiro de 2022.* Dispõe sobre a estrutura organizacional da Secretaria de Estado da Educação (SEDUC). Republicada com alterações no Diário Oficial do Estado de Alagoas, Maceió, 18 ago. 2023, p. 47. [Edição Eletrônica DOEAL nº 37543](https://diario.imprensaoficial.al.gov.br/apinova/api/editions/viewPdf/37543).
5. **Alagoas. Governo do Estado.** *Matrícula Escolar na Rede Pública Estadual.* Portal de Serviços Alagoas Digital, Serviço nº 585. Disponível em: [Alagoas Digital - Serviço 585](https://alagoasdigital.al.gov.br/servico/585). Consulta em: 16 nov. 2026.
6. **Alagoas. Secretaria de Estado da Educação (SEDUC-AL).** *Portal Matrícula Online.* Canal oficial de cadastro e consulta de vagas escolares. Disponível em: [Matrícula Online Alagoas](https://www.matriculaonline.al.gov.br/). Consulta em: 16 nov. 2026.
7. **Brasil. Presidência da República.** *Lei Federal nº 9.394, de 20 de dezembro de 1996.* Estabelece as Diretrizes e Bases da Educação Nacional (LDB). Texto atualizado com as alterações vigentes. Disponível em: [Portal da Legislação / Câmara dos Deputados](https://www2.camara.leg.br/legin/fed/lei/1996/lei-9394-20-dezembro-1996-362578-normaatualizada-pl.html).
8. **Brasil. Ministério da Educação. Conselho Nacional de Educação (CNE/CEB).** *Resolução CNE/CEB nº 3, de 08 de abril de 2025.* Institui as Diretrizes Operacionais Nacionais para a Educação de Jovens e Adultos (EJA) e revoga a Resolução CNE/CEB nº 1/2021. Diário Oficial da União, Brasília, 09 abr. 2025, Seção 1, p. 16. Reprodução institucional consultada: [IFAP Normas](https://ifap.edu.br/documents/1074/Res_CNE_CEB_3_2025.pdf).
9. **Brasil. Ministério da Educação. Conselho Nacional de Educação (CNE/CEB).** *Resolução CNE/CEB nº 6, de 17 de julho de 2025.* Altera e complementa dispositivos transitórios das Diretrizes Operacionais Nacionais para a EJA. Diário Oficial da União, Brasília, 21 jul. 2025, Seção 1, p. 39. Reprodução consultada: [Repositório Institucional CPS](https://bkpsitecpsnew.blob.core.windows.net/uploadsitecps/sites/18/2025/08/Resolucao-CNE-CEB-06_2025-07-21.pdf).
10. **Brasil. Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (Inep).** *Censo Escolar da Educação Básica: Orientações sobre Situação do Aluno (Movimento e Rendimento).* Brasília: Inep/MEC. Disponível em: [Inep - Censo Escolar](https://www.gov.br/inep/pt-br/acesso-a-informacao/perguntas-frequentes/censo-escolar/situacao-do-aluno/quais-sao-as-informacoes-coletadas). Consulta em: 16 nov. 2026.
11. **Guimarães, M. A.** (2025). Permanência e evasão na Educação de Jovens e Adultos: um olhar a partir de teses e dissertações brasileiras. *Revista Brasileira de Estudos Pedagógicos*, Brasília. Disponível em: [SciELO / FCC](https://educa.fcc.org.br/scielo.php?lng=pt&nrm=iso&pid=S1981-416x2025000301252&script=sci_arttext&tlng=pt).
12. **Pedralli, R.; Cerutti-Rizzatti, M. E.** (2013). Práticas de letramento no contexto da Educação de Jovens e Adultos: pertença e acolhimento em análise. *Revista Brasileira de Linguística Aplicada*, Belo Horizonte, v. 13, n. 4, pp. 1133–1158. Disponível em: [SciELO Brasil](https://www.scielo.br/j/rbla/a/vZWw6znGkH6cFMcCPP354RG/?lang=pt).
