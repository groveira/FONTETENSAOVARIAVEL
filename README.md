# Trabalho 1: Fonte de Tensão Ajustável

## 👥 Integrantes
- Arthur Andrade Carneiro Almeida
- Guilherme Rodrigues de Oliveira
- Kawan da Silva Costa

## 📝 Descrição do Projeto
Projeto realizado para a disciplina de Eletrônica para Computação, ministrada pelo professor Eduardo do Valle Simões. O objetivo deste projeto é o desenvolvimento de uma fonte de tensão ajustável variando entre **3V e 12V**, com uma capacidade de corrente de **100mA**.

## 🛠️ Componentes Utilizados
- 1x Potenciômetro 1W B10K B-16, 5XE-20XR-7MM
- 1x Diodo Zener 13V 1W (1N4743 SEMTECH)
- 1x Transistor BC337-40 N 50V 0,8A TO-92
- 1x Capacitor ELCO 470uF X 50V
- 10x Resistor CR25 1K2 Carvão
- 10x Resistor CR25 100R Carvão
- 10x Diodo Retificador 1N4007 (LGE= 1N4004)
- 1x LED 5mm VM DIFUSO 333-2 SDRD/S530-L PARALIGHT

## 🔍 Função dos Componentes no Circuito
* **Diodo:** Dispositivos semicondutores que permitem a passagem de corrente elétrica em apenas uma única direção. A ponte de diodos é responsável por retificar a corrente alternada, transformando-a em contínua.
* **Capacitor:** Armazena temporariamente a carga durante o declínio da tensão vinda da ponte retificadora, estabilizando a tensão para o resto do circuito.
* **LED:** Indicador visual da passagem de corrente elétrica no circuito.
* **Resistores:** Responsáveis pela limitação da corrente elétrica no circuito.
* **Potenciômetro:** Resistor ajustável utilizado para regular a voltagem de saída entre 3V e 12V.
* **Transistor:** Responsável por ajustar a corrente que alimentará o dispositivo (100mA).
* **Diodo Zener:** Responsável por regular a tensão máxima do circuito.
