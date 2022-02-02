# KwH Pré-pago

Este projeto está em stand-by por tempo indeterminado.
Caso queira contribuir com este projeto favor entre em contato pelo e-mail flaviohpo@yahoo.com

## Descrição do projeto

O kWh-Pré pago é um sistema de gerenciamento de consumo específico para chuveiro, podendo fácilmente ser adaptado para outros equipamentos de até 50A / 110/220V.
O sistema é composto por pelo menos 4 partes:
1. Placa de potência
2. Placa de interface
3. Smartphone / Computador (Com acesso à internet)
4. Chuveiro elétrico ou carga genérica

A placa de potência está conectada em série com um equipamento elétrico e permite seu funcionamento ou não através de um relé de estado sólido.
Para que o equipamento funcione é necessário que algum usuário do sistema, através de um tag RFID, libere seu funcionamento. Para liberar o usuário precisa ter saldo de kWh. Este saldo é renovado periodicamente pelo administrador do sistema.
No momento que o usuário utiliza seu tag no leitor, três opções de utilização são apresentadas, são elas:
1. Limite de tempo: O usuário escolhe um certo tempo o qual o equipamento irá permanecer ligado.
2. Limite de energia: O usuário escolhe quanta energia pretende gastar no equipamento.
3. Modo v1d4 l0k4: O usuário gasta seu saldo, sem se preocupar com o amanhã.

Nos modos 1 e 2, um aviso sonoro é emitido quando estiver faltando 10% do tempo/energia pré-selecionado(a).
Caso o usuário termine a utilização de maneira antecipada, basta passar seu tag no leitor que o equipamento é desligado.

## Hardawre

ESP32-S2 (Franzininho-wifi)
relé estado sólido
Sensor de corrente alternada
Display ST7789
Leitor RFID
