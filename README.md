# Trabalho-MIPS-AOC

# 🔥 Sistema de Alarme de Incêndio em MIPS

Este projeto consiste no desenvolvimento de um **simulador de alarme de incêndio** implementado em **Assembly MIPS**, com o objetivo de aplicar conceitos fundamentais da disciplina de **Arquitetura e Organização de Computadores**.

O sistema realiza a leitura de valores de **temperatura** e **fumaça**, calcula um **índice de risco ponderado** e classifica o estado do ambiente em níveis de severidade: normal, atenção, alerta e evacuação.

---

## ⚙️ Funcionalidades

* Leitura e validação de dados de entrada
* Cálculo de risco limitado a 100
* Classificação do estado do sistema
* Ativação manual de emergência
* Armazenamento das últimas leituras (buffer circular)
* Interface de entrada e saída via syscalls

---

## 🧮 Cálculo de Risco

O risco é obtido por meio da seguinte função ponderada:

```
Risco = (18 × Temperatura + 32 × Fumaça) / 120
```

Valores acima de 100 são truncados para 100.

---

## 🛠️ Tecnologias Utilizadas

* Assembly MIPS
* Simulador MARS (ou SPIM)

---

## 👥 Autores

* Nicolas David da Cruz Santos
* Davi de Oliveira Custódio
* João Augusto Paixão Rocha
* Bernardo Friske de Souza

---
