Controle de Servo para automatizar lixeira e Sensor de Força para pesar o lixo

Este é um código em C++ Arduino para controlar um servo motor e monitorar um sensor de força. O servo motor é controlado por um botão para utilizar o lixo e o sensor de força monitora o peso do lixo.

Componentes Utilizados:

Arduino Uno
Servo Motor
Sensor de Força
Potenciômetro
Display LCD 16x2
LED
Botão
Cabos Jumpers
Resistores

Instalação:

Conecte os componentes de acordo com a imagem esquema.png
O pino A0 é conectado ao sensor de força.
O display LCD é conectado aos pinos 8, 7, 6, 5, 4 e 3.
O LED é conectado ao pino 11.
O botão é conectado ao pino 13.
O servo motor é conectado ao pino 9.
Instalar biblioteca LiquidCrystal.h e Servo.h na sua IDE do Arduino.
Carregue o código no seu Arduino Uno.

Funcionamento:

O servo motor é controlado por um botão. Pressionar o botão move o servo para a posição de 90 graus, e pressioná-lo novamente o retorna à posição inicial (0 grau).
O sensor de força é monitorado continuamente.

Turma: ESPV1
Stephany Borzi Marques (RM:557351)
Albert Katri (RM556544)
Gabriel Ferreira Flora Carvalheiro (556476)
