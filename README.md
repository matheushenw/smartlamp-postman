# Sistema de Controle de Lâmpada IoT

## FIWARE Descomplicado - Smart Lamp 

Este projeto implementa um sistema de Internet das Coisas (IoT) para controlar uma lâmpada e monitorar a luminosidade usando um microcontrolador ESP32. O sistema se conecta a uma rede WiFi e se comunica com um broker MQTT para permitir controle remoto e relatórios de dados.

## Características

- Conectividade WiFi
- Comunicação MQTT para controle remoto e publicação de dados
- Controle de LED (ligado/desligado)
- Detecção e relatório de luminosidade
- Capacidades de reconexão automática para WiFi e MQTT

## Requisitos de Hardware

- Microcontrolador ESP32
- LED conectado ao GPIO 2 (D4)
- Fotoresistor ou sensor de luz conectado ao GPIO 34
