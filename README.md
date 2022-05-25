# Transmissor e Receptor Serial UART  - _PIC 18F4520_

![DEMO](https://github.com/jbrun0r/Transmissor-e-Receptor-Serial-UART-PIC-18F4520/blob/main/Serial.gif?raw=true)

Transmissor e Receptor Serial UART 1200, 8, N, 1.

## Resumo:
Desenvolva um _Transmissor_ e _Receptor_ serial **UART 1200,8,N,1** que
ao receber um _byte_ do terminal virtual, retransmita-o de volta
imediatamente. Assim, tudo que for teclado no terminal será
ecoado de volta.


## Design:

![fundo](https://github.com/jbrun0r/Transmissor-e-Receptor-Serial-UART-PIC-18F4520/blob/main/SERIAL.png?raw=true)
Utilizei o **Proteus Design Suite (Proteus)** para a criação do projeto eletrônico, composto por uma suíte de ferramentas, incluindo captura esquemática, simulação e módulos de projetos de placas de circuito impresso, usadas principalmente para o projeto de circuitos integrados. Utilizei O **MPLAB IDE** para gerenciamento do projeto e **Compilador C18**.\
Seguindo as orientações do datasheet do PIC supracitado, escreveremos o código/lógica em linguagem .c e compilamos com **C18** para arquivo **.cof** ou **.hex.**
___

#### Ferramentas:

* [PIC-18F4520](https://ww1.microchip.com/downloads/en/DeviceDoc/39631E.pdf)
* Proteus 7.8 Professional Portable
* [MPLAB IDE](https://www.microchip.com/en-us/tools-resources/archives/mplab-ecosystem)
* C18 Compiler
* **SO:** Windows 10/11 (64-bit Required)


