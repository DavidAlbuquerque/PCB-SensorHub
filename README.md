# PCB-SensorHub
 Projeto de PCB - Gangorra para Simulação de Estabilização de Drone
Este projeto faz parte do desenvolvimento de uma gangorra que simula o sistema de estabilização de um drone. O objetivo é testar algoritmos de controle de estabilidade utilizando sensores e microcontroladores embarcados.

Esta PCB é a primeira de três que compõem o sistema. Sua função é integrar os microcontroladores e sensores responsáveis pela coleta de dados e controle dos motores.

🎯 Objetivo do Projeto
Projetar uma PCB eficiente para integrar os sensores e microcontroladores necessários para a simulação do sistema de estabilização do drone.

🔧 Componentes Principais
Microcontroladores: ESP32 e Raspberry Pi Pico
Sensores:
INA219 (Monitoramento de corrente e tensão)
MPU6050 (Acelerômetro e giroscópio)
Time-of-Flight (TOF) (Dois sensores para medição de distância)
Controle de Motores:
ESC 10A para controle de velocidade dos motores via PWM
Conectores:
Utilização de conectores JST XH para facilitar a conexão dos sensores, que serão acoplados na gangorra ao invés de serem soldados diretamente na PCB
