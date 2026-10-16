# Harness de contexto · HESED Produção Audiovisual

Este arquivo é lido automaticamente pelo Claude Code e pode ser colado no início de uma conversa com qualquer assistente de IA (Claude, ChatGPT, Gemini) para dar o contexto do projeto. Mantenha curto: ele aponta para os documentos, não repete o conteúdo.

Este é o contexto comum para Claude, Codex e AntiGravity. O [AGENTS.md](AGENTS.md) direciona outros assistentes para cá; o [CODEX.md](CODEX.md) e o [ANTIGRAVITY.md](ANTIGRAVITY.md) complementam os respectivos fluxos. Orientações de produção compartilhadas devem ser mantidas aqui e nos guias correspondentes, para que o trabalho continue da mesma forma independentemente do assistente usado.

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

Só decisões aprovadas prevalecem sobre o briefing: 🟡 significa proposta e ⚪ significa substituída. Os originais em `docs/fontes/` prevalecem sobre suas transcrições em caso de divergência de conversão. Ao receber material novo, identifique versão/data quando disponíveis e compare com a base existente; não substitua documentos por uma versão cuja aprovação esteja incerta. A Bíblia de Produção v0.1 é citada no briefing, mas isso não comprova que seu arquivo foi recebido.

## Ao começar e concluir uma tarefa

- Leia o [README.md](README.md), consulte decisões, status e pendências atuais e confira as alterações existentes no Git antes de editar. Preserve o trabalho de outras pessoas.
- Use o checkout existente; em tarefas na nuvem, não crie worktrees sem pedido explícito.
- Edite apenas o escopo solicitado. Ao atualizar andamento, altere a linha correspondente e data/nome no topo do `STATUS.md`; não avance etapas ou marque aceite sem evidência.
- Registre decisões confirmadas com responsável, data e pessoas/peças afetadas; ligue a decisão à pendência resolvida. Lembre o usuário de avisar o grupo quando necessário, sem enviar mensagens em nome da equipe sem instrução explícita.
- Revise o diff, links locais, códigos, responsáveis e continuidade. Este repositório é documental, sem instalação, build ou servidor. Informe o que foi verificado e o que depende de material, confirmação ou ensaio no telão.

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

## Storyboards e imagens individuais · padrão compartilhado

Siga a estrutura das pranchas de Eduardo (Dudu), adotada como padrão para os demais storyboards: **quadros numerados, descrição, movimento, efeitos, paleta e relação com a música ou a fala**, sempre conectados ao briefing do respectivo MM. Preserve a linguagem realista e cinematográfica e as costuras entre produtores.

O guia de construção e o caderno de quadros são as **diretrizes canônicas de criação visual** para Claude, Codex e demais assistentes. Sua consulta é obrigatória antes de toda criação ou edição de imagem do HESED, incluindo estudos, referências geradas, pranchas e bases definitivas. Aplique o procedimento de consulta e registro do guia antes de acionar qualquer ferramenta de imagem; não dependa apenas do chat ou da memória. Essa autoridade sobre o processo visual não altera a hierarquia das fontes narrativas nem transforma propostas em decisões aprovadas.

Antes de criar ou revisar um storyboard ou imagem, leia:

1. [Guia de construção](storyboards/guia-de-construcao.md): composição, luz, personagens, cenários, continuidade, prompts e passagem da prancha para imagens individuais.
2. [Briefings dos quadros](storyboards/briefings-dos-quadros.md): caderno vivo com o detalhamento de cada imagem; contém os estudos iniciais das quatro pranchas de Dudu.
3. A ficha `storyboards/<MM-XX>/README.md`, a página da pessoa em `equipe/`, o trecho do roteiro e o [mapa de cenas](docs/mapa-de-cenas.md), conferindo as [dependências](docs/dependencias.md).

Se faltar o briefing do quadro, escreva-o no caderno a partir das fontes antes da geração. Se houver conflito que exija decisão da equipe, explicite-o e resolva esse ponto antes de produzir a imagem afetada. Registre os documentos e IDs consultados e, após gerar, o prompt efetivamente usado e o resultado, conforme o guia.

- A cada novo storyboard, acrescente o briefing de seus quadros ao caderno. Use IDs estáveis `MM-XX-QNN` e registre composição, luz, continuidade, animação e prompt conforme o modelo do guia. Não renumere quadros existentes para alterar a ordem de montagem.
- A cada imagem gerada, atualize o quadro com referências reais, localização, versão, tamanho e feedback; registre aprovação apenas quando confirmada. Atualize a ficha-resumo com miniaturas/links existentes. Bases finais e projetos pesados ficam no Drive; esboços leves podem ficar no repositório.
- Diferencie **prancha de planejamento**, com quadros e anotações, de **imagem-base individual**, limpa e sem títulos, números, timecodes ou colagem. Descreva movimento e efeitos separadamente do instante da imagem-base.
- Preserve identidade de personagens, cenário, direção de luz e primeiro/último frame entre imagens e produtores. Use referências aceitas e confira as imagens vizinhas antes de produzir em série.
- Tempos e formas de onda nas referências não comprovam sincronização. Playbacks dependem do master definitivo; MM-10 acompanha uma fala variável; MM-16D integra o filme final e depende da divisão de Lucas. Registre conflitos como pontos de conferência, sem alterar o padrão ou declarar uma solução aprovada.
- 3840×2160 é a referência para imagens-base, não a especificação final dos vídeos. Confira P-01 e o [checklist de aceite](guias/checklist-de-aceite.md); uma revisão no computador não substitui o teste no telão.

Se estes procedimentos mudarem, atualize os guias compartilhados e suas referências neste arquivo, no `CODEX.md` e no `ANTIGRAVITY.md`, evitando cópias divergentes das regras de produção.

## Tarefas comuns e onde olhar

| Pedido | Arquivos |
| --- | --- |
| "O que eu tenho que fazer?" | `equipe/<nome>.md`, `STATUS.md` |
| "Quando minha peça entra?" | `docs/mapa-de-cenas.md`, `docs/roteiro.md` |
| "Com quem preciso falar?" | `docs/dependencias.md` |
| "Me ajuda com o storyboard" | [Guia de construção](storyboards/guia-de-construcao.md), [caderno de quadros](storyboards/briefings-dos-quadros.md), `storyboards/<MM-XX>/README.md` |
| "Vamos criar uma imagem definitiva" | Briefing do quadro no [caderno](storyboards/briefings-dos-quadros.md), referências aceitas e orientações do [guia](storyboards/guia-de-construcao.md) |
| "Me ajuda a mapear a música" | `guias/playback-visual.md` |
| "Como nomeio/exporto?" | `guias/entrega-e-arquivos.md` |
| "Minha peça está pronta?" | `guias/checklist-de-aceite.md` |
| "Atualiza meu status" | `STATUS.md` (só a linha da pessoa + data/nome no topo) |
| "Resumo do andamento do projeto" | `STATUS.md`, `docs/pendencias.md`, `docs/decisoes.md` |

## Casa da Religiosidade · referência atual

D-13 substitui os ramos antigos: única referência [V03 oficial](storyboards/MM-03/V03.jpg), com relógio, bandejinha/renda e menorá; sem foto ou Bíblia; pia à esquerda sob o aéreo, cooktop à direita. V03-01 = noite/todas acesas; V03-02 = noite/só centro; V03-03 = noite/só luar. Usar [guia vigente](storyboards/guia-de-construcao.md#casa-da-religiosidade--diretrizes-atuais) e [contrato MM-03](storyboards/briefings-dos-quadros.md#mm-03--casa-da-religiosidade). Versões anteriores excluídas a pedido do usuário; não reutilizar V04, foto ou Bíblia. As três variações foram solicitadas nesta correção; aprovação artística das imagens e teste no LED permanecem pendentes.
