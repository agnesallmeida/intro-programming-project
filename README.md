# 🚦 Projeto Semáforo em C

Este projeto simula o funcionamento de um semáforo utilizando a linguagem C. O objetivo é aplicar conceitos básicos de programação, como estruturas de repetição, condições e controle de tempo, simulando a alternância entre os estados do semáforo.

---

## 📌 Objetivo

Desenvolver uma simulação simples de um semáforo para reforçar conceitos de lógica de programação, como:

- Estruturas condicionais (`if`, `switch`)
- Laços de repetição (`while`, `for`)
- Uso de temporização (`sleep` ou equivalente)
- Organização de código em linguagem C

---

## ⚙️ Funcionalidades

- Simulação dos estados do semáforo:
  - 🔴 Vermelho (pare)
  - 🟡 Amarelo (atenção)
  - 🟢 Verde (siga)

- Transição automática entre os estados
- Tempo definido para cada cor
- Execução contínua até interrupção do programa

---

## 🧠 Lógica do Programa

O programa segue o ciclo:

1. Verde → tempo definido
2. Amarelo → tempo definido
3. Vermelho → tempo definido
4. Repete o ciclo

---

## 💻 Tecnologias utilizadas

- Linguagem C
- Biblioteca padrão (`stdio.h`, `stdlib.h`, `unistd.h` ou equivalente)

---

## ▶️ Como executar

### No Linux / WSL:
```bash
gcc semaforo.c -o semaforo
./semaforo
