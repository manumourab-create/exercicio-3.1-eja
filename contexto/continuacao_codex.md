# Continuação do Exercício 3.1 no Codex CLI

## Autorização e origem

A estudante Rosy Emannuele Moura dos Santos Bomfim escolheu explicitamente continuar pelo **Codex no terminal** após o Antigravity/Gemini informar limite individual de uso. O Codex CLI já foi encontrado instalado e autenticado com ChatGPT.

Você é **Codex / OpenAI**, não Gemini nem Claude. O histórico real da Parte B é: Gemini produziu v1, v2 e a primeira redação da v3; Codex realizou as duas auditorias. A tentativa final do Gemini, interrompida por quota, não modificou a v3: seu SHA-256 permanecia `849f5947148b40a18ca747b9d4bd1e274a32179d85e0fbc4c713751e53faf519`. O original está preservado em `contexto/historico/B_relatorio_assistente_v3_antes_ajustes_finais.md`.

A partir daqui, os ajustes finais de consistência e a entrevista serão realizados no Codex, por escolha da estudante. Registre essa mudança de ferramenta e participação no README, na nota de autoria da v3 corrigida e no transcript. Não reatribua suas alterações ao Gemini. O enunciado indica Claude Code com `/grill-me`; esta execução utiliza a skill correspondente no Codex CLI (`$grill-me`), e essa adaptação deve ficar explícita.

## Etapa 1 — Concluir os ajustes pontuais antes da entrevista

1. Leia `contexto/ajustes_v3_codex.txt`, `B_relatorio_assistente_v3.md`, `B_relatorio_auditoria_v2.md`, `A_meta_prompt.md` e `contexto/roteiro_3_1.md`. Consulte `contexto/exercicio_2_1/C_mapa_atores.md` para continuidade do serviço.
2. Aplique todos os oito grupos de ajustes localizados de `contexto/ajustes_v3_codex.txt` no próprio `B_relatorio_assistente_v3.md`, sem reescrever desnecessariamente o restante. As referências R01–R17 continuam sendo os gatilhos da segunda auditoria.
3. Acrescente uma nota factual na v3: redação de pesquisa por Gemini / Antigravity CLI; ajustes finais de consistência por Codex / OpenAI após interrupção por limite da conta, com original preservado. A nota não substitui a aplicação dos ajustes.
4. Confira as ocorrências afetadas, a distinção entre norma e execução não verificada, os ramos do ingresso/classificação e as referências. Mantenha pendências documentais explícitas; não as resolva com imaginação. Atualize a tabela de resposta e o README com o estado real.
5. Preserve A, v1, auditoria v1, v2, auditoria v2 e o contexto do 2.1. Não produza v4 nem terceira auditoria. A cópia histórica da v3 deve permanecer intacta.
6. Após verificar as correções, informe brevemente o que mudou e as pendências mantidas. Avance à Etapa 2 na mesma sessão; a estudante já autorizou realizar a atividade. Se houver impedimento concreto que inviabilize a base da entrevista, relate-o em vez de declarar a correção pronta.

## Etapa 2 — Entrevista real com a skill grill-me

Use **$grill-me**, com a implementação auxiliar **grilling** instalada em `.agents/skills/`. Leia os dois `SKILL.md`. Se a instrução original mencionar uma ferramenta `Skill` não disponível no Codex, carregue diretamente `.agents/skills/grilling/SKILL.md`; não tente chamar uma ferramenta inexistente. A fonte e licença estão em `contexto/origem_skills_grill.md` e nos diretórios das skills.

Para esta atividade, as regras do enunciado e as instruções explícitas da estudante prevalecem sobre padrões genéricos da skill: faça **UMA pergunta por vez**, aguarde a resposta real e registre **pelo menos seis rodadas completas**. Planeje cerca de oito a dez rodadas, cobrindo decisões diferentes. Não use subagentes: consulte diretamente os documentos já fornecidos. Não faça perguntas que os arquivos podem responder. Não pergunte se a estudante quer começar: apresente a primeira pergunta após a Etapa 1.

### Recorte já decidido

- Serviço: acesso e permanência na EJA Modular do Ensino Médio da rede estadual de Alagoas / Seduc-AL.
- Público: pessoas 18+, perfis plurais de trabalho, renda e cuidado; não presumir emprego formal nem somente turno noturno.
- Abrangência: rede estadual geral, sem escola específica como evidência representativa.
- Produto: AS-IS documental, com hipóteses identificadas e lacunas locais; não há entrevistas de campo ou observação presencial.
- Relação com 2.1: aproveitar o mapa de atores, reexaminando ações e participação na jornada; não copiar automaticamente a classificação das instituições para camadas inteiras.

### Decisões a cobrir, respeitando dependências

Pergunte sobre uma decisão por rodada, sem oferecer opções conceitualmente inválidas:

1. Organização das cinco ou mais etapas pela ótica do estudante e seus limites.
2. Representação dos percursos de ingresso e da bifurcação entre comprovação de estudos e classificação, com deliberação do Conselho de Classe.
3. Linha de visibilidade e distribuição de ações concretas entre contato digital/presencial, backstage e suporte.
4. Passagens de responsabilidade e devolutivas ao cidadão, incluindo o que permanece desconhecido.
5. Apoios à permanência e busca ativa: distinguir previsão normativa, interação visível e execução local não verificada.
6. Desfechos: conclusão de módulo, avanço, conclusão integral, interrupção, transferência e retorno; não confundir andamento de turma com situação individual censitária.
7. Escolha fundamentada dos fail points a destacar e indicação de riscos inferidos, sem fabricar ocorrências reais.
8. Evidências e representação das pendências, inclusive AJUS, GEGEV, TI e cobertura dos apoios.
9. Confirmação nominal dos atores e etapas efetivamente escolhidos, com tabela resumida que permita à estudante corrigir a seleção.
10. Fechamento do entendimento e formato final da matriz, se ainda necessário. Não acumule perguntas independentes em uma única rodada apenas para reduzir o número de respostas.

As cinco camadas e as posições das fronteiras não são objeto de votação: Evidências → Ações do Cidadão → Linha de Interação → Frontstage → Linha de Visibilidade → Backstage → Linha de Interação Interna → Suporte. A estudante decide o recorte e representação dentro dessa estrutura. Resposta da interface digital pertence ao contato visível; ação de preencher pertence ao cidadão. Não invente comissão de matrícula/classificação.

### Como conduzir e registrar

- Use linguagem acessível em português. Dê duas ou três opções válidas, explique sua recomendação e peça uma justificativa curta. Aceite resposta livre. Ajude a estudante a entender os conceitos sem decidir por ela.
- Aguarde cada resposta. Uma opção recomendada não é resposta dada. Não aceite confirmação presumida por silêncio.
- Crie `C_grill_transcript.md` com o pedido real recebido, identificação da ferramenta, origem das skills e declaração de ausência de entrevistas de campo.
- Registre integralmente cada pergunta, alternativas, recomendação e a resposta literal. Se a resposta for "1" ou "sim", preserve esses caracteres e registre separadamente a alternativa referida; não transforme a recomendação em fala literal da estudante.
- Salve progressivamente após cada resposta para evitar perda do transcript. Uma pergunta aguardando resposta deve constar como pendente e não conta como rodada completa.
- Se uma resposta for ambígua ou contraditória, esclareça antes de utilizá-la; não preencha lacunas como se fossem decisões dela.
- Na confirmação final, apresente um resumo concreto das etapas, atores, camadas, riscos e pendências. A skill exige entendimento compartilhado antes de agir: se essa regra motivar a confirmação, cite e identifique a fonte de forma breve. Essa confirmação integra a entrevista; não é autorização de Git ou publicação.

## Etapa 3 — Somente após a entrevista real

Após pelo menos seis rodadas respondidas e o entendimento final confirmado:

1. Complete `C_grill_transcript.md`, mantendo perguntas e respostas literais.
2. Elabore `C_blueprint_asis.md` com no mínimo cinco etapas pela ótica do cidadão, cinco camadas, três fronteiras na posição correta e ao menos um fail point. Toda etapa e todo ator nominal do blueprint deve aparecer na entrevista. Inclua rastreabilidade para a rodada e para a fonte, quando pertinente.
3. Não crie respostas para justificar atores novos. Se faltar deliberação necessária, faça uma pergunta adicional e aguarde.
4. Atualize o README com o status real de C, autoria e a adaptação do uso da skill ao Codex. D permanece pendente nesta fase.
5. Pare e informe os arquivos produzidos para que a estudante traga o resultado à conversa de acompanhamento. Não crie ainda `D_diagrama_asis.md`, não execute Git, não publique no GitHub, não rode autograde nem faça submissão.

## Integridade

Você não recebeu autorização para simular uma entrevista. Comece pela Etapa 1, depois faça a primeira pergunta e aguarde a estudante. Dados normativos são pesquisáveis; decisões de representação são dela. Não acrescente nomes reais de servidores, credenciais ou dados de estudantes ao material público.
