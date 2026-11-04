# Plantão da Meia-Noite

Jogo de terror em primeira pessoa ambientado no Hospital Santa Vitória. Explore o hospital à noite, encontre pistas sobre o desaparecimento de Lia e tente escapar da criatura.

## Como jogar

Não é necessária instalação ou compilação. Abra `index.html` em um navegador moderno para acessar o menu principal. Os capítulos também podem ser iniciados diretamente:

- `index.html` — Capítulo 1
- `capitulo2.html` — Capítulo 2: Linha Ocupada
- `capitulo3.html` — Capítulo 3: O Sótão

Mantenha `susto.png` na mesma pasta dos arquivos HTML: a imagem é usada nas cenas de susto dos capítulos.

## Capítulos

### Capítulo 1 — O Último Plantão

Encontre os 24 prontuários espalhados pelos três pavimentos do hospital e escape pela saída. Procure suprimentos, armários para se esconder e a chave do baú. Ao recuperar todos os prontuários, uma rota até a saída é revelada e a perseguição final começa.

### Capítulo 2 — Linha Ocupada

Explore o porão e complete as três missões para liberar a saída:

- Atenda 5 telefones.
- Encontre 3 vestígios de Lia.
- Examine 2 cadáveres.

A criatura persegue você enquanto a lanterna consome bateria. Encontre baterias de reserva e administre o fôlego durante as corridas.

### Capítulo 3 — O Sótão

Depois de ouvir Lia pedir socorro, procure-a no sótão de aproximadamente 2.304 m², formado por salas amplas conectadas por corredores. A criatura já está perseguindo você. Encontre Lia e escape por uma das duas saídas.

## Controles

Os controles podem variar um pouco entre os capítulos. Consulte a tela inicial de cada um para ver a lista completa.

| Ação | Controle |
|---|---|
| Andar | `W`, `A`, `S`, `D` |
| Olhar | Mouse ou setas esquerda/direita |
| Correr | `Shift` |
| Lanterna | `F` |
| Interagir | `E` — Capítulos 2 e 3 |
| Trocar bateria | `R` — Capítulos 2 e 3 |
| Pausar | `Esc` |

No Capítulo 1, use as setas para subir ou descer escadas, `C` para se esconder ou sair de um armário, `H` para usar remédio, `K` para usar a chave ou abrir o baú, clique para atirar e `G` para recarregar.

## Tecnologias

- HTML, CSS e JavaScript
- Canvas 2D para a renderização em primeira pessoa
- Web Audio API para efeitos sonoros e áudio ambiente

O jogo não usa dependências externas. Para jogar, mantenha os arquivos dos capítulos e `susto.png` juntos na mesma pasta.
