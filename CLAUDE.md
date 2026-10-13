# Harness de contexto · HESED Produção Audiovisual

Este arquivo é lido automaticamente pelo Claude Code e pode ser colado no início de uma conversa com qualquer assistente de IA (Claude, ChatGPT, Gemini) para dar o contexto do projeto. Mantenha curto: ele aponta para os documentos, não repete o conteúdo.

## Quem você está ajudando

Um membro da equipe de produção audiovisual (telão) do **HESED**, musical de Natal 2026 do GET Planalto e GET Santa Amélia. A equipe tem cinco pessoas (Victor, Melissa, Isaac, Eduardo, Lucas), cada uma responsável por peças codificadas como `MM-XX`. São voluntários de igreja, com níveis variados de experiência em edição e nenhuma obrigação de saber Git.

## Fontes de verdade (nesta ordem)

1. `docs/decisoes.md`: decisões tomadas depois do briefing. **Prevalecem sobre o briefing.**
2. `docs/briefing.md`: Briefing Definitivo v1.0 (escopo, linguagem, distribuição). Original em `docs/fontes/`.
3. `docs/roteiro.md`: roteiro do musical. Original em `docs/fontes/`.
4. `docs/mapa-de-cenas.md`: cruzamento roteiro × briefing com gatilhos e conflitos.
5. `STATUS.md`: andamento atual de cada peça.
6. `docs/pendencias.md`: perguntas abertas (`P-XX`).

Se uma informação não está nesses arquivos, diga que não está e sugira registrar como pendência. **Não invente** durações, datas, especificações técnicas ou decisões.

## Princípios do projeto

- Cinco produtores, **uma única linguagem audiovisual**.
- Progressão: cotidiano → criação → queda → promessa → luz → nascimento → graça → celebração.
- Paleta de Natal: branco, dourado, azul-noturno, luz quente.
- Still nunca fica parado; vira clipe com movimento sutil.
- Diálogo de duração variável pede **loop**.
- Playback é coreografia com a música; nunca lyric video.
- O telão não compete com atores, dança ou falas.
- Tom reverente na história bíblica; o humor das falas das personagens é do palco, não do telão.

## Como ajudar bem

- **Pergunte quem é a pessoa** (ou leia `equipe/<nome>.md`) antes de responder sobre tarefas.
- Ao falar de uma peça, sempre cite: gatilho no roteiro, de quem recebe, para quem entrega.
- Ao sugerir execução, prefira técnicas acessíveis (parallax, máscaras, partículas, zoom lento) em editores comuns (Premiere, After Effects, DaVinci, CapCut) a soluções 3D.
- Ao mapear uma música, peça o audio master; não estime tempos de faixas de memória.
- Se a pessoa decidir algo que afeta outra, lembre de registrar em `docs/decisoes.md` e avisar no grupo.
- Ao editar arquivos do repo: só altere a linha/seção da pessoa; não reescreva `docs/briefing.md` nem `docs/roteiro.md`; mantenha códigos `MM-XX`, `P-XX`, `D-XX` estáveis.
- Escreva em português do Brasil.

## Tarefas comuns e onde olhar

| Pedido | Arquivos |
| --- | --- |
| "O que eu tenho que fazer?" | `equipe/<nome>.md`, `STATUS.md` |
| "Quando minha peça entra?" | `docs/mapa-de-cenas.md`, `docs/roteiro.md` |
| "Com quem preciso falar?" | `docs/dependencias.md` |
| "Me ajuda a mapear a música" | `guias/playback-visual.md` |
| "Como nomeio/exporto?" | `guias/entrega-e-arquivos.md` |
| "Minha peça está pronta?" | `guias/checklist-de-aceite.md` |
| "Atualiza meu status" | `STATUS.md` (só a linha da pessoa + data/nome no topo) |
| "Resumo do andamento do projeto" | `STATUS.md`, `docs/pendencias.md`, `docs/decisoes.md` |
