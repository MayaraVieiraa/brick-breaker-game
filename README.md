# Brick Breaker Game

## Sobre o Projeto
Jogo Brick Breaker (Breakout) desenvolvido com Flutter e Flame Engine.
O objetivo e controlar uma plataforma para rebater uma bola e quebrar todos os blocos coloridos.

## Funcionalidades
- Bola com fisica e colisoes precisas
- Taco controlado por mouse e teclado (setas)
- 50 blocos coloridos em grid
- Sistema de pontuacao (1 ponto por bloco)
- Dificuldade progressiva (velocidade aumenta)
- Telas: Welcome, Game Over, You Won
- Interface arcade com animacoes

## Como Executar

### Pre-requisitos
- Flutter SDK instalado
- Navegador Chrome

### Passos

git clone https://github.com/MayaraVieiraa/brick-breaker-game.git

cd brick-breaker-game

flutter pub get

flutter run -d chrome


## Como Jogar
- Mouse: Arraste para mover o taco
- Setas: Esquerda e direita para mover o taco
- Espaco ou Enter: Iniciar novo jogo
- Clique na tela: Iniciar novo jogo

## Estrutura do Projeto

lib/
├── main.dart
└── src/
├── brick_breaker.dart
├── config.dart
├── components/
│ ├── ball.dart
│ ├── bat.dart
│ ├── brick.dart
│ └── play_area.dart
└── widgets/
├── game_app.dart
├── score_card.dart
└── overlay_screen.dart


## Tecnologias
- Flutter
- Flame
- google_fonts
- flutter_animate

## Autor
Mayara Vieira

## Status
Completo - Testado no Chrome
