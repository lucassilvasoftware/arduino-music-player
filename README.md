# Player musical — Arduino

Sketch para **Arduino** que simula um reprodutor simples: menu em display **LCD** 16×2, navegação por botões, reprodução de melodias em buzzer com suporte a pausa, retomada e faixas distintas (arrays de notas).

## Tecnologias

- Arduino (C/C++ compatível com a IDE Arduino)
- Biblioteca **LiquidCrystal** (padrão da IDE)

## Hardware (referência do código)

- LCD compatível com LiquidCrystal nos pinos indicados no sketch (ex.: RS, Enable, dados).
- Botões (pull-up interno) para navegação, play/pause e parar.
- Buzzer no pino de saída definido para `tone()`.
- LEDs opcionais para indicação de estado.

## Como usar

1. Abra `main.ino` na Arduino IDE (ou PlatformIO, se preferir).
2. Ajuste pinos e faixas conforme sua montagem.
3. Selecione a placa e a porta série, compile e envie o sketch para o Arduino.

A reprodução utiliza durações derivadas de arrays de notas; consulte o código para nomes das músicas no menu.
