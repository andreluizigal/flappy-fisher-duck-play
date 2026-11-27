# Áudio de Flappy Fisher Duck

## Música

- **Calm Loop**, de **wipics**.
- Fonte: https://opengameart.org/content/calm-loop
- Arquivo original: https://opengameart.org/sites/default/files/Relaxing_0.mp3
- Cópia local do original: `calm-loop.mp3`.
- Arquivo usado no jogo: `calm-loop-seamless.wav`, editado para repetir a cada 19,2 segundos, com a pausa cortada e uma transição curta nas pontas.
- Licença declarada pelo autor: **CC0 1.0 — domínio público**.
- Licença: https://creativecommons.org/publicdomain/zero/1.0/
- Obtido em 8 de novembro de 2026.

- **Basilisk Boss Battle Loop**, de **beardalaxy**. Trilha compartilhada nas lutas contra o Megalodon, o Helicóptero e o Polvo.
- Fonte: https://opengameart.org/content/basilisk-boss-battle-loop
- Arquivo original: https://opengameart.org/sites/default/files/basilisk_boss_battle_in_game.ogg
- Arquivo usado no jogo: `megalodon-battle.mp3`, com fades curtos nas pontas e codificação MP3 para compatibilidade com navegadores.
- Licença declarada pelo autor: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

## Efeitos sonoros

Asas, mergulho, captura, dano, recuperação, tiros e explosões de minas são sintetizados por código original
em `lib/game/audio.ts`, com osciladores e ruído filtrado. Nenhum sample ou gravação
de terceiros é utilizado nesses efeitos.

A explosão submersa combina ruído abafado, uma queda curta de frequência e pequenas
bolhas sintetizadas. Foi criada para este jogo, sem arquivos de áudio ou licença de terceiros.

O som de choque do raio combina ruído filtrado e oscilações curtas para produzir um estalo e um zumbido elétrico.

- **Rugido do Megalodon e do Mini Megalodon.** Arquivo `shark_roar.ogg` fornecido para o projeto, convertido para `shark-roar.wav` para reprodução no navegador. O Mini Megalodon reproduz o mesmo som a 1,2×.
- **Som do Helicóptero.** Arquivo `helicopter_roar.mp3` fornecido para a apresentação e para o início de cada investida, incluído no jogo como `helicopter-roar.mp3`.

Os sons de aviso, tornado, laser, míssil, impacto e explosão do chefe são sintetizados em `lib/game/audio.ts`.

A apresentação do Polvo e os efeitos de tentáculos, investida giratória, redemoinho e tinta usam osciladores e ruído filtrado originais em `lib/game/audio.ts`. O jato de tinta, as bolas lançadas e o impacto no pato têm sons próprios.
