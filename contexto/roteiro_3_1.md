# Roteiro da atividade 3.1

Data de preparação: 16/11/2026. Este roteiro resume o enunciado fornecido pela estudante; não é um entregável substituto da pesquisa.

## Sequência

1. Usar o meta-prompt de A para gerar um prompt de pesquisa. Guardar o resultado auxiliar em `contexto/prompt_pesquisa_3_1.md`; A continua contendo o meta-prompt.
2. Gemini/Antigravity produz B_relatorio_assistente_v1.md sobre operação atual, com consulta às fontes públicas e limites de evidência.
3. Codex/OpenAI audita v1; salvar B_relatorio_auditoria_v1.md, com falhas substantivas identificadas.
4. Gemini revisa v1 à luz de cada achado, produzindo B_relatorio_assistente_v2.md. Cada falha é corrigida, defendida com evidência ou mantida explicitamente aberta.
5. Codex audita v2 e salva B_relatorio_auditoria_v2.md, verificando achados anteriores e problemas novos.
6. Gemini produz B_relatorio_assistente_v3.md, relacionando cada mudança ao identificador do achado da segunda auditoria.
7. Somente após B, conduzir uma nova entrevista real `/grill-me`, de pelo menos seis rodadas, uma pergunta por vez. A entrevista 2.1 é contexto, não substitui a 3.1. Registrar as perguntas e respostas integrais, inclusive alternativas selecionadas e respostas livres, sem inventar justificativas.
8. Produzir C_blueprint_asis.md: matriz com cinco camadas (Evidências Físicas, Ações do Cidadão, Frontstage, Backstage, Processos de Suporte), três linhas (interação, visibilidade, interação interna), pelo menos cinco etapas pela ótica do cidadão e pelo menos um ponto de falha explicitado com seu status de evidência.
9. Produzir D_diagrama_asis.md a partir da Parte C, com conexões explícitas, etapas e atores consistentes. Toda etapa/ator de C deverá aparecer na entrevista real.
10. Publicar o repositório público, atualizar o autograde conforme o enunciado, executar `autograde validar 3.1`, conferir a prévia e submeter quando a estudante aceitar.

## Mínimos e integridade

- A_meta_prompt.md: pelo menos 200 palavras. Cada um dos cinco arquivos B: pelo menos 300 palavras.
- Nove entregáveis com nomes e capitalização exatamente como no README; não criar arquivos vazios para simular conclusão.
- README com o nome completo e os nove links. Marcador raiz `.autograde-exercise`: somente `3.1` e quebra de linha.
- Dois assistentes de famílias distintas. Não produzir uma autoauditoria do Gemini como se tivesse sido feita pelo Codex.
- Preservar as versões anteriores e as auditorias integrais. Fontes e evidências devem ser verificáveis.
- O enunciado menciona Claude Code para `/grill-me`; a estudante utilizou Antigravity/Gemini no exercício anterior. A ferramenta efetivamente utilizada na nova entrevista deve ser registrada com transparência.
- Atualização do autograde: localizar seu clone de origem e verificar alterações locais antes de executar `git pull` e reinstalação editável no ambiente correto. Não atualizar ou reinstalar às cegas.
- Até dez prévias por dia; não executar prévias antes de todos os entregáveis estarem prontos.

## Cuidados herdados de 2.1

Não presumir que atribuições da GEGEV estejam comprovadas em 2026 por uma estrutura de 2023; não confundir atendimento geral com suporte técnico; não afirmar abandono automático nem processamento integralmente manual sem prova; não tratar falta como abandono ou conclusão; não prometer abono de faltas por AJUS. Alimentação, transporte e apoios externos dependem de comprovação de cobertura e de fluxo local. As normas são referências do funcionamento previsto, não observação da execução em cada escola.
