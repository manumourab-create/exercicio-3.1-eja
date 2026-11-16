# Origem das skills da entrevista do Exercício 3.1

Preparação: Codex / OpenAI, em 16/11/2026, por escolha da estudante Rosy Emannuele Moura dos Santos Bomfim de continuar no Codex CLI após limite do Gemini / Antigravity.

## Fontes e instalação

As skills foram obtidas do repositório público de Matt Pocock, usando o instalador de skills do Codex, pelo método de download, com destino temporário `/private/tmp/exercicio-3.1-eja/skills_codex`. O comando de preparação da estudante copia os arquivos para `.agents/skills/` do projeto e inicia uma nova sessão do Codex.

- [grill-me — origem](https://github.com/mattpocock/skills/tree/main/skills/productivity/grill-me)
- [grilling — implementação auxiliar](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling)
- [Licença MIT do repositório](https://github.com/mattpocock/skills/blob/main/LICENSE)
- [Skills no Codex — documentação oficial](https://learn.chatgpt.com/docs/build-skills)

Os arquivos `SKILL.md` e `agents/openai.yaml` foram mantidos como recebidos; a licença MIT foi incluída em cada diretório redistribuído. A origem foi a branch `main`, sem identificação de commit fixada nesta preparação; os hashes abaixo identificam os bytes preparados. Não se afirma que sejam a versão original usada pelo docente.

A inspeção dos arquivos preparados encontrou instruções textuais e metadados, sem scripts executáveis ou hooks de inicialização. Isso descreve estes arquivos, não toda configuração do Codex.

## Adaptação explícita à atividade

O enunciado indica Claude Code com `/grill-me`. A estudante escolheu Codex CLI; a invocação será `$grill-me`, com leitura da implementação `grilling`. Se a ferramenta `Skill` citada no alias não estiver disponível, o agente deve ler diretamente o `SKILL.md` de `grilling`.

As instruções específicas da atividade em `contexto/continuacao_codex.md` prevalecem sobre os padrões genéricos: uma pergunta por vez, no mínimo seis rodadas reais, respostas literais salvas progressivamente e consulta direta dos documentos, sem subagentes. O fechamento deve apresentar o entendimento compartilhado e aguardar a resposta real da estudante. Não há autorização para fabricar a entrevista. A adaptação deve constar no README e no transcript; não se declara que houve sessão no Claude.

## Integridade dos arquivos preparados

| Arquivo relativo a `.agents/skills/` | SHA-256 |
|---|---|
| `grill-me/LICENSE` | `0e7ac423bf2c6e223b7c5b156f8cf72da49d748e56a1641402c31f22ad07dbb5` |
| `grill-me/SKILL.md` | `caaf8b8de1684f96e26b28f3c29189db5c89cce4b73e1c93d86164f66ef88637` |
| `grill-me/agents/openai.yaml` | `c061e39c3e0f9d865fb1b97556d485704af2a8a58f4b8221a8917a5c2074a32b` |
| `grilling/LICENSE` | `0e7ac423bf2c6e223b7c5b156f8cf72da49d748e56a1641402c31f22ad07dbb5` |
| `grilling/SKILL.md` | `a146842ed93ca43d833550fa9adf02e58cb63c83fea9d4b4522995b82242d4e2` |
| `grilling/agents/openai.yaml` | `1411d7df7d99b7e621a1ff8283c8133cc2464be63d064e52d8ce169c6800ee9b` |
