# 🏐 Simulador de Rodízio de Vôlei 5x1

Este projeto é um jogo desenvolvido em Python utilizando o framework Kivy, que simula um rodízio de vôlei 5x1. O intuito do jogo é ensinar os jogadores a se posicionarem corretamente durante o rodízio, além de demonstrar as movimentações e posicionamentos ideais em diferentes situações de ataque.

## Introdução

O rodízio 5x1 é uma das formações mais populares no vôlei profissional, com cinco jogadores na linha de defesa e um levantador. Entender as posições e o movimento correto durante o rodízio é fundamental para o sucesso no jogo. Este simulador ensina os fundamentos de posicionamento e bloqueio em situações de ataque, visando preparar melhor os jogadores para os desafios do esporte.

## Demonstração


https://github.com/user-attachments/assets/137df963-1534-4add-8dfb-9cce61c00db3



## Objetivo do Jogo

O objetivo principal do jogo é educacional: mostrar aos jogadores como se posicionar corretamente em cada rodada de rodízio, levando em conta:
- Onde bloquear ao atacar de diferentes posições (por exemplo, bloqueio para o ponteiro, central, oposto).
- Movimentação do levantador e como cada jogador deve se adaptar conforme a posição da bola.
- Simulações de ataques e defesas com orientações para tomadas de decisões.

## Funcionalidades

- **Saque**: Um botão de "Saque" para iniciar uma nova jogada e reorganizar o posicionamento dos jogadores.
- **Ataque**: Um botão de "Ataque" que permite ao jogador escolher qual posição está atacando (ex.: ponteiro, central, oposto) e visualizar como os outros jogadores devem se comportar.
- **Rodízio**: Um botão de "Rodízio" para simular a rotação dos jogadores em quadra, mudando as posições automaticamente.
- **Instruções Visuais**: Feedback visual para ajudar a entender onde cada jogador deve estar durante o jogo.
- **Modo Prática**: Permite que o jogador selecione diferentes tipos de ataques e bloqueios para ver como os posicionamentos mudam.
  

## Como Jogar

1. **Saque**: Clique no botão de "Saque" para iniciar uma rodada. Os jogadores se posicionarão de acordo com a posição inicial do rodízio.
2. **Ataque**: Escolha um dos botões de ataque (Ponteiro, Central, etc.) para simular um ataque específico e observe a posição de bloqueio e movimentação recomendada para o ataque selecionado.
3. **Rodízio**: Após cada jogada, clique no botão de "Rodízio" para rotacionar os jogadores de acordo com o sistema 5x1. A nova disposição dos jogadores será exibida.

## Exemplos de Uso

### Rodízio Inicial
O jogo começa com todos os jogadores posicionados para o saque inicial. Após o saque, cada jogador se ajustará para cobrir as posições específicas de defesa ou ataque.

### Exemplo de Ataque
Quando o botão de "Ataque" é pressionado, você pode escolher qual jogador irá atacar. Ao selecionar o atacante (ex: ponteiro), o simulador mostra a posição que os outros jogadores devem ocupar para otimizar o bloqueio e a defesa.

### Exemplo de Bloqueio
Ao escolher o bloqueio do central, o jogo indica onde os jogadores precisam se posicionar para cobrir as áreas de bloqueio e defesa.

## Tecnologias Utilizadas

- **Python**: Linguagem principal para o desenvolvimento do jogo.
- **Kivy**: Framework de Python para desenvolvimento de aplicativos e jogos interativos.
- **KivyMD**: Biblioteca para adicionar componentes de design de material ao Kivy, aprimorando a interface do jogo.
