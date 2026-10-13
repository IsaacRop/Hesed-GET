# Entrega e organização de arquivos

## Onde fica o quê

| Tipo | Onde | Por quê |
| --- | --- | --- |
| Texto, status, decisões, guias | **Este repositório** | Histórico, todo mundo vê a mesma versão |
| Vídeos, imagens, projetos, áudios | **Drive compartilhado** (link: _a definir, P-13_) | Arquivos grandes; Git não foi feito para isso |

**Não suba vídeo, projeto de edição ou áudio no repositório.** O `.gitignore` já bloqueia os formatos comuns.

## Estrutura sugerida no Drive

```
HESED_Telão/
├── 00_Fontes/            roteiro, briefing, audio masters (P-02), arquivo de Goel (P-03)
├── 01_Referências/       uma subpasta por MM
├── MM-01_Victor/
│   ├── alpha/
│   ├── final/
│   ├── projeto/          arquivo editável + assets
│   └── emergencia/       still de emergência
├── MM-02_Victor/
├── ...
├── MM-16_Conform_Lucas/
└── 99_Operação/          pasta final que vai para o computador do telão
```

## O que entregar em cada peça

- [ ] Arquivo final renderizado para o telão
- [ ] Arquivo editável / projeto
- [ ] Assets necessários para alterações posteriores
- [ ] Still de emergência (imagem que substitui o vídeo se ele falhar)
- [ ] Versão claramente identificada (v01, v02...)
- [ ] Backup do aprovado em um segundo lugar

## Padrão de nomes

```
Vídeo:       HESED_C[NN]_MM-[NN]_[descricao]_v[NN].mp4
Imagem-base: HESED_C[NN]_[descricao]_3840x2160_v[NN].png
```

Exemplos:

```
HESED_C03_MM-06_retorno-temporal_v01.mp4
HESED_C03_MM-06_loop-bebe_v01.mp4
HESED_C05_MM-11_luz-do-mundo_v03.mp4
HESED_C09_MM-16C_nascimento-vida_v02.mp4
HESED_C03_criacao-base_3840x2160_v01.png
```

Regras: cena sempre com dois dígitos, descrição em minúsculas com hífen, sem acentos e sem espaços. Nunca sobrescreva uma versão; crie a próxima.

## Especificação técnica

| Item | Valor |
| --- | --- |
| Imagens-base | 3840×2160 (definido na Bíblia de Produção) |
| Resolução de vídeo | **a definir (P-01)** |
| Frame rate | **a definir (P-01)** |
| Codec / container | **a definir (P-01)** |
| Áudio embutido? | **a definir** (depende de como a operação roda as músicas) |
| Loops em arquivo separado? | **a definir (P-12)** |

Quando a P-01 for respondida, atualize esta tabela e registre em [decisoes.md](../docs/decisoes.md).
