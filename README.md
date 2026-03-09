![GitHub License](https://img.shields.io/github/license/Scoorpioon/lab-redes-01)

# Laboratório de Redes 01 - Projeto de Rede local
Aluno: Gabriel A.
Professor: José de Assis

Data: 09/03/26

---

## 1. Objetivo
Implementar uma rede local simples conectando 3 notebooks a um roteador wireless com switch e uma impressora de rede.

O projeto será dividido em duas etapas:

1. Simulação da rede no Cisco Packet Tracer
2. Implementação da rede no laboratório real

---

## 2. Equipamentos utilizados neste laboratório:

- 3 Notebooks;
- 1 Roteador wireless com uma porta WAN e quatro portas LAN;
- 1 Impressora de rede;
- Cabos de rede.

---

## 3. Topologia da rede

Diagrama lógico da rede usada neste laboratório:
```mermaid
graph TD

WAN[Internet / WAN do provedor]

Router[Roteador Wireless<br>1 Porta WAN<br>4 Portas LAN]

PC1[Notebook 1]
PC2[Notebook 2]
PC3[Notebook 2]

Printer[Impressora de rede]

WAN --> |Porta Wan| Router

Router --> |LAN 1| PC1
Router --> |LAN 2| PC2
Router --> |LAN 3| PC3
Router --> |LAN 4| Printer
```
