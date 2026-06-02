# 🎛️ Controle de Servo Motor com ESP32 e Display OLED

## 📖 Descrição

Projeto desenvolvido utilizando um ESP32 para controlar a posição de um servo motor através de dois botões. O sistema conta com um display OLED SSD1306 para exibir informações em tempo real e LEDs indicadores para sinalizar o estado do servo.

## 🚀 Funcionalidades

- Controle de posição do servo motor.
- Exibição do ângulo atual no display OLED.
- Controle através de botões físicos.
- Indicação visual utilizando LEDs.
- Atualização em tempo real das informações.

## 🛠️ Componentes Utilizados

- ESP32
- Display OLED SSD1306 (I2C)
- Servo Motor SG90
- 2 Botões Push Button
- LED Verde
- LED Vermelho
- Resistores 220Ω
- Protoboard
- Jumpers

## 🔌 Esquema do Circuito

![Circuito](circuito.png)

> Adicione a imagem do circuito com o nome **circuito.png** na pasta do projeto.

## ⚙️ Funcionamento

- O botão verde aumenta o ângulo do servo.
- O botão azul diminui o ângulo do servo.
- O display OLED exibe o ângulo atual.
- Os LEDs indicam a movimentação do servo.

## 📂 Estrutura do Projeto

```bash
📦 Projeto-ESP32-Servo
 ┣ 📜 codigo.ino
 ┣ 📷 circuito.png
 ┗ 📄 README.md
```

## 📚 Bibliotecas Utilizadas

```cpp
#include <Servo.h>
#include <Wire.h>
#include <Adafruit_GFX.h>
#include <Adafruit_SSD1306.h>
```

## ▶️ Como Executar

![imagemservomotor](
## 🎯 Objetivo

Este projeto tem como objetivo praticar:

- Programação embarcada
- Controle de servomotores
- Comunicação I2C
- Manipulação de displays OLED
- Leitura de entradas digitais
- Desenvolvimento com ESP32
