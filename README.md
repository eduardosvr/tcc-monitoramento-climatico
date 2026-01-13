# tcc-monitoramento-climatico

Projeto de TCC: aplicação móvel de baixo custo para monitoramento climático baseada em IoT.

---

## Descrição do Projeto

Este projeto consiste no desenvolvimento de uma **aplicação móvel de baixo custo para monitoramento climático**, utilizando conceitos de **Internet das Coisas (IoT)**.

A solução permite a coleta de dados ambientais locais **temperatura, umidade e pressão atmosférica** de forma precisa e em tempo real.

Os dados são coletados por um **sensor ambiental conectado a um microcontrolador ESP32**, transmitidos via **MQTT**, armazenados em um **banco de dados** e disponibilizados por meio de uma **API**, sendo posteriormente exibidos em um **aplicativo móvel desenvolvido em Flutter**.

---

## Tecnologias Utilizadas

### Hardware
- ESP32  
- Sensor ambiental BME280  

### Comunicação
- MQTT  
- Mosquitto (Broker MQTT)

### Backend / API
- Node.js  
- MySQL  

### Aplicação Mobile
- Flutter  
- fl_chart (gráficos)
