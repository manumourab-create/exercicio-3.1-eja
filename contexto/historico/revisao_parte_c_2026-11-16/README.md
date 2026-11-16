# Exercício 3.1 — Service Blueprint AS-IS da EJA estadual de Alagoas

**Estudante:** Rosy Emannuele Moura dos Santos Bomfim.

**Serviço:** acesso e permanência na EJA Modular do Ensino Médio da rede estadual de Alagoas, para pessoas de 18 anos ou mais, pelo portal Matrícula Online e pelas unidades da Seduc-AL. Continuidade do [Exercício 2.1](https://github.com/manumourab-create/exercicio-2.1-eja).

## Entregáveis

1. [A_meta_prompt.md](A_meta_prompt.md) — meta-prompt executado; gerou o prompt de pesquisa em [contexto/prompt_pesquisa_3_1.md](contexto/prompt_pesquisa_3_1.md).
2. [B_relatorio_assistente_v1.md](B_relatorio_assistente_v1.md) — pesquisa inicial completa concluída pelo Assistente 1 (Gemini / Antigravity CLI).
3. [B_relatorio_auditoria_v1.md](B_relatorio_auditoria_v1.md) — primeira auditoria concluída pelo Assistente 2 (Codex / OpenAI), identificando 19 achados substantivos (F01 a F19).
4. [B_relatorio_assistente_v2.md](B_relatorio_assistente_v2.md) — pesquisa revisada completa concluída pelo Assistente 1 (Gemini / Antigravity CLI).
5. [B_relatorio_auditoria_v2.md](B_relatorio_auditoria_v2.md) — segunda auditoria concluída pelo Assistente 2 (Codex / OpenAI), identificando 17 pontos de ajuste (R01 a R17).
6. [B_relatorio_assistente_v3.md](B_relatorio_assistente_v3.md) — pesquisa original por Gemini / Antigravity CLI, com ajustes finais de consistência aplicados e conferidos por Codex / OpenAI, vinculados à segunda auditoria; pendências documentais explícitas.
7. [C_grill_transcript.md](C_grill_transcript.md) — entrevista real concluída no Codex, com dez rodadas respondidas, respostas literais e entendimento/formato confirmados na Q10.
8. [C_blueprint_asis.md](C_blueprint_asis.md) — Parte C elaborada por Codex / OpenAI após confirmação da estudante: cinco etapas, cinco camadas, três fronteiras, quatro riscos inferidos selecionados e quadros de responsabilidades e rastreabilidade; disponível para revisão.
9. [D_diagrama_asis.md](D_diagrama_asis.md) — diagrama Mermaid consistente com o blueprint; pendente.

## Andamento e Metodologia

Nesta atividade, o **assistente 1 é o Gemini / Antigravity CLI** (pesquisa e revisões), e o **assistente 2 é o Codex / OpenAI** (auditorias). Os papéis são próprios do exercício 3.1. O Codex assumiu também os ajustes finais da v3 e a entrevista por escolha expressa da estudante após limite do Gemini, sem reatribuir suas alterações ao assistente original. O modelo específico de cada execução será registrado apenas quando houver evidência.

- **Etapa A:** O meta-prompt de [A_meta_prompt.md](A_meta_prompt.md) foi executado com rigor, preservando o arquivo original e salvando o prompt de pesquisa aprofundada em [contexto/prompt_pesquisa_3_1.md](contexto/prompt_pesquisa_3_1.md).
- **Etapa B (v1):** O Assistente 1 produziu [B_relatorio_assistente_v1.md](B_relatorio_assistente_v1.md) com base em fontes normativas e operacionais públicas.
- **Etapa B (Auditoria v1):** O Assistente 2 (Codex / OpenAI) realizou a primeira auditoria adversarial em [B_relatorio_auditoria_v1.md](B_relatorio_auditoria_v1.md), catalogando 19 achados substantivos (F01 a F19).
- **Etapa B (v2):** O Assistente 1 elaborou [B_relatorio_assistente_v2.md](B_relatorio_assistente_v2.md) com a reorganização canônica das camadas e detalhamento dos fluxos.
- **Etapa B (Auditoria v2):** O Assistente 2 (Codex / OpenAI) realizou a segunda auditoria adversarial em [B_relatorio_auditoria_v2.md](B_relatorio_auditoria_v2.md), apontando 17 itens de ajuste remanescentes e novos (R01 a R17).
- **Etapa B (v3):** Primeira redação por Gemini / Antigravity CLI. Após interrupção por limite da conta, a estudante escolheu continuar no Codex / OpenAI, que aplicou e conferiu os oito grupos de ajustes de `contexto/ajustes_v3_codex.txt`, vinculados a R01–R17 da segunda auditoria, sem v4 ou terceira auditoria. Foram corrigidos documentação/NIS, desfechos, bifurcação de ingresso, atribuições e arquitetura presumidas, visibilidade, limites das buscas e perguntas orientadoras. A cópia histórica permanece intacta em [v3 original](contexto/historico/B_relatorio_assistente_v3_antes_ajustes_finais.md). Permanecem lacunas de AJUS, GEGEV, TI, progressão/equivalências, coleta censitária, devolutivas e cobertura dos apoios. A tentativa de reabrir o caderno Inep retornou HTTP 502; não se declara consulta bem-sucedida nesta revisão.
- **Etapa C concluída para revisão:** Entrevista real `$grill-me` no Codex com a implementação auxiliar [grilling](.agents/skills/grilling/SKILL.md), adaptação explícita do Claude Code com `/grill-me` do enunciado. Foram realizadas dez rodadas, uma pergunta por vez, com respostas reais preservadas literalmente em [C_grill_transcript.md](C_grill_transcript.md). Após confirmação final da estudante na Q10, Codex / OpenAI elaborou [C_blueprint_asis.md](C_blueprint_asis.md), com a seleção nominal da Q9, quatro riscos escolhidos e limites da evidência explícitos. Conferência textual/estrutural realizada; não equivale a autograde.
- **Ponto de parada:** Parte C entregue para revisão da estudante. Parte D não produzida. Git, publicação, autograde e submissão não executados nesta continuação.

Os documentos anteriores estão em [contexto/exercicio_2_1](contexto/exercicio_2_1), como referência histórica. Não foram realizadas entrevistas de campo ou observações locais diretas. As etapas futuras, a publicação no GitHub e a validação/submissão pelo autograde estão pendentes.
