# Rouba Pino

Jogo de mesa para 2 a 4 jogadores no mesmo aparelho. Roda direto no navegador, sem login e sem backend.

**Jogar:** https://fau009.github.io/rouba-pino/

## Configuração

- **Jogadores:** 2, 3 ou 4. Cada um tem uma cor e um ícone (● Vermelho, ▲ Azul, ■ Amarelo, ◆ Roxo) e fica num canto da tela. Os nomes podem ser editados.
- **Pinos por jogador:** de 3 a 10. Cada pino mostra o ícone e o número do dono.

## Regras

1. **Escolher o alvo.** Na sua vez, toque no canto de quem você vai roubar. Dá para trocar de alvo até rolar o dado.
2. **Rolar o dado.** Toque no dado 3D no centro da mesa.
3. **Roubar.** Arraste para o seu canto a quantidade de pinos que saiu no dado. Tocar no pino também funciona. Se o alvo tiver menos pinos que o número tirado, você leva todos.
4. **Resgate obrigatório.** Se algum pino seu está com outro jogador, seu alvo precisa ser alguém que está com ele. Nesse roubo, você pega os seus pinos de volta antes de poder pegar os dele.
5. **Pinos roubados circulam.** Pinos de outro jogador que estão com você podem ser roubados de você por qualquer um.
6. **Eliminação.** Quem termina uma jogada com o canto vazio está fora, e a vez pula essa pessoa.
7. **Vitória.** O último jogador com pinos vence.

## Controles

- **Reiniciar:** começa a partida de novo com a mesma configuração.
- **← Configurar:** volta à tela de configuração.
- Durante a partida, os dois botões pedem um segundo toque para confirmar.

## Estrutura

Um único `index.html` (HTML, CSS e JS puros). Publicado pelo GitHub Pages a partir da branch `main`. O dado é o mesmo do projeto [Dado Online](https://github.com/Fau009/dado-online), usado aqui como parte do jogo.
