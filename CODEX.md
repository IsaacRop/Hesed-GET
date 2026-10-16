# Codex · HESED Produção Audiovisual

Este arquivo complementa o [CLAUDE.md](CLAUDE.md), que mantém o contexto comum do projeto, a hierarquia das fontes e os princípios audiovisuais. Leia os dois. O [AGENTS.md](AGENTS.md) é o ponto de entrada das instruções para o Codex; este arquivo é carregado por essa orientação.

## Começo de cada trabalho

1. Leia o [README.md](README.md) para localizar os documentos e confira as alterações existentes no Git antes de editar.
2. Consulte [decisões](docs/decisoes.md), [status](STATUS.md) e [pendências](docs/pendencias.md) para obter a situação atual. Releia esses arquivos em novas tarefas; não use este documento como cópia do andamento.
3. Para uma tarefa individual, identifique a pessoa pelo contexto ou pergunte seu nome, se ainda não estiver claro, e leia sua página em [equipe/](equipe/).
4. Para uma peça, leia o trecho do [roteiro](docs/roteiro.md), o [briefing](docs/briefing.md), o [mapa de cenas](docs/mapa-de-cenas.md), as [dependências](docs/dependencias.md) e a ficha correspondente em [storyboards/](storyboards/). Cite cena, gatilho, o que recebe e para quem entrega; indique quando uma dessas informações não estiver definida.

Use o checkout existente. Cada tarefa na nuvem já tem um ambiente isolado; não crie worktrees sem pedido explícito.

## Fontes, propostas e materiais novos

- Siga a ordem de fontes definida no `CLAUDE.md`. Decisões aprovadas posteriores prevalecem sobre o briefing; itens 🟡 são propostas, e itens ⚪ foram substituídos. Não apresente propostas como acordos confirmados.
- Os originais em [docs/fontes/](docs/fontes/) prevalecem sobre suas transcrições quando houver divergência de conversão. Preserve os originais, o roteiro e o briefing existentes; alterações de escopo devem ser registradas em decisões.
- Ao receber novos arquivos, identifique título, versão, data e relação com os documentos existentes, quando disponíveis. Leia o material e aponte diferenças e lacunas antes de propor sua incorporação. Se não estiver claro qual versão foi aprovada, peça essa definição sem substituir a base atual.
- Não invente durações, timecodes, calendário, especificações do telão, links de mídia ou acesso a arquivos externos. Exemplos dos guias não são tempos reais das músicas.
- A Bíblia de Produção v0.1 é citada no briefing. Essa citação não significa que o arquivo esteja disponível; confira os materiais recebidos antes de afirmar que o leu.

## Execução e registro

Escreva em português do Brasil, com orientações práticas para uma equipe voluntária. Preserve a linguagem visual comum e prefira as técnicas acessíveis indicadas no `CLAUDE.md`.

Para storyboards e imagens individuais, siga a seção de padrão compartilhado do [CLAUDE.md](CLAUDE.md), o [guia de construção](storyboards/guia-de-construcao.md) e o [caderno de briefings dos quadros](storyboards/briefings-dos-quadros.md). Use o mesmo padrão das pranchas do Dudu e atualize o caderno a cada novo storyboard ou imagem, mantendo IDs, referências, versões e feedback. Mudanças nos procedimentos comuns devem ser refletidas nos guias e nas referências de Claude, Codex e [AntiGravity](ANTIGRAVITY.md).
Para storyboards e imagens individuais, siga a seção de padrão compartilhado do [CLAUDE.md](CLAUDE.md), o [guia de construção](storyboards/guia-de-construcao.md) e o [caderno de briefings dos quadros](storyboards/briefings-dos-quadros.md). Use o mesmo padrão das pranchas do Dudu e atualize o caderno a cada novo storyboard ou imagem, mantendo IDs, referências, versões e feedback. Mudanças nos procedimentos comuns devem ser refletidas nos guias e nas referências de ambos os assistentes.

A consulta ao guia e ao briefing da peça/quadro é **obrigatória antes de toda criação ou edição de imagem**, inclusive estudos e pranchas. Eles são as diretrizes canônicas de criação visual. Antes de acionar a ferramenta, cumpra o procedimento de consulta e registro do guia; se faltar a ficha do quadro, escreva-a primeiro com base nas fontes. Não gere apenas com o pedido do chat ou de memória. Registre fontes/IDs consultados e o prompt efetivamente usado, preservando a hierarquia narrativa e a situação de aprovação de cada proposta.

- Use [templates/](templates/) para fichas e atualizações e siga o [fluxo de trabalho](guias/fluxo-de-trabalho.md): leitura → storyboard → alpha → integração → teste no telão → ajustes → congelamento.
- Edite apenas as linhas ou seções relacionadas ao pedido. Preserve alterações de outras pessoas e os identificadores `MM-XX`, `P-XX` e `D-XX`.
- Ao atualizar andamento, altere a linha da pessoa e a data/nome no topo do `STATUS.md`. Não avance etapas nem marque aceite sem evidência.
- Para decisões confirmadas, registre quem decidiu, data e pessoas/peças afetadas; se responderem a uma pendência, faça a referência cruzada. Sugestões devem ficar identificadas como propostas.
- Se houver impacto em outra pessoa, lembre o usuário de avisar o grupo e registrar a mudança. Não envie mensagens em nome da equipe sem instrução explícita.
- Mantenha mídia pesada e projetos de edição no Drive, conforme o [guia de entrega](guias/entrega-e-arquivos.md). Storyboards leves podem ficar no repositório. Não presuma que a pasta compartilhada já foi definida ou está acessível.

## Validação antes de entregar

- Revise o diff e confira links locais, códigos das peças, responsáveis e continuidade entre os documentos alterados.
- Para playbacks, use o áudio master definitivo e o [guia de playback](guias/playback-visual.md). Sem o master, trabalhe no conceito e explicite que a sincronização está pendente.
- Não confunda 3840×2160 das imagens-base com especificação final de vídeo; consulte a definição do telão antes do render final.
- Siga o [checklist de aceite](guias/checklist-de-aceite.md). Validação documental ou visual no computador não substitui ensaio no telão real.
- Este repositório é documental: não exige instalação, build ou servidor. Informe quais verificações foram realizadas, o que foi alterado e o que ainda depende de materiais ou decisões da equipe.
