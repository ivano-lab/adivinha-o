# Jogo de Adivinhação em Rust

Este é um jogo simples de adivinhação de números implementado em Rust. O jogador deve adivinhar um número gerado aleatoriamente pelo computador. O jogo fornece dicas se o número inserido é maior ou menor do que o número alvo até que o jogador acerte.

## Funcionalidades

- O computador gera um número aleatório entre 1 e 100.
- O jogador insere um palpite, e o jogo retorna:
  - "Muito alto!" se o palpite for maior que o número alvo.
  - "Muito baixo!" se o palpite for menor que o número alvo.
  - "Acertô mizerávi!!!" se o palpite for correto.
- O jogo continua até que o jogador acerte o número.

