# 🛡️ Análise de Ataque à Rede com Wireshark – Google Cybersecurity Certificate

Este repositório contém a análise de um incidente de segurança simulando um ataque **DoS (Denial of Service)** do tipo **SYN Flood**, parte da atividade prática do curso **"Analisar ataques à rede de computadores"** da **Certificação em Cibersegurança do Google** via **Coursera**.

## 🎯 Objetivo da Atividade

Investigar um problema de segurança identificado em um site corporativo, utilizando logs do **Wireshark**, e produzir um **relatório técnico** explicando:

- O tipo de ataque detectado
- Como o ataque compromete o funcionamento do servidor web
- As evidências nos registros de tráfego de rede
- Medidas de mitigação para evitar futuras interrupções

## 📂 Estrutura do Repositório

├── README.md

├── relatorio_incidente_preenchido.pdf # Relatório técnico (preenchido)

├── Wireshark_TCP_HTTP_log.pdf # Log capturado do tráfego TCP/HTTP

├── como_ler_log_wireshark.pdf # Guia de leitura dos logs


## 🧠 O que foi aprendido

- Como funciona o **three-way handshake** do protocolo TCP
- Como interpretar pacotes SYN, SYN-ACK e ACK nos logs do Wireshark
- Como identificar padrões típicos de um **SYN Flood**
- Diferença entre ataques **DoS** e **DDoS**
- Como um ataque à camada de transporte pode causar falhas na aplicação (HTTP 504, RST-ACK)
- Estratégias de defesa como uso de **firewalls, rate limiting e SYN cookies**

## 🔍 Ferramentas Utilizadas

- [Wireshark](https://www.wireshark.org/)
- Google Cybersecurity Certificate – Coursera
- Análise manual de pacotes TCP/HTTP

> “Segurança não é um produto, é um processo.” – Bruce Schneier
