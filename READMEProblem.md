
# Projeto 1 - Organização e Implementação de Computadores

## 📚 Descrição

Este projeto tem como objetivo consolidar os conhecimentos adquiridos na Unidade Curricular de Organização e Implementação de Computadores, através da implementação de um processador monociclo com suporte a um subconjunto das instruções da arquitetura MIPS.

O processador deverá ser implementado em VHDL e simulado com recurso ao ModelSim, permitindo executar programas simples escritos em linguagem Assembly MIPS.

---

## 🎯 Objetivos

- Projetar e implementar um processador monociclo em VHDL.
- Compreender o ciclo de execução de instruções da arquitetura MIPS.
- Simular e validar o comportamento do processador.
- Consolidar os conhecimentos sobre organização interna de um processador.
- Desenvolver competências práticas de depuração e teste de sistemas digitais.

---

## 🧩 Componentes a Implementar

### Módulos principais:

- **Unidade de controlo**: responsável por gerar os sinais de controlo apropriados.
- **ALU (Unidade Lógica e Aritmética)**: executa operações aritméticas e lógicas.
- **Banco de registradores**: armazena os dados temporários utilizados nas operações.
- **Memória de instruções**: contém o programa a ser executado.
- **Memória de dados**: acessada nas instruções de load e store.
- **Módulo principal (top-level)**: integra todos os componentes acima.

### Módulos auxiliares:

- **Extensor de sinal (Sign Extender)**.
- **Multiplexadores (MUX)**.
- **Módulos de controlo de leitura e escrita de memória**.
- **Controlador de PC (Program Counter)**.

---

## 🖥️ Instruções a Suportar

O processador deverá suportar, no mínimo, as seguintes instruções da arquitetura MIPS:

### Tipo R:
- `add`, `sub`, `and`, `or`, `slt`

### Tipo I:
- `lw`, `sw`, `beq`, `addi`

> Nota: O suporte ao salto condicional (`beq`) requer manipulação do PC (Program Counter).

---

## ⚙️ Ferramentas

- **Linguagem de descrição de hardware:** VHDL
- **Ambiente de simulação:** ModelSim
- **Outros:** Text Editor (VS Code, etc.)

---

## 🧪 Validação e Testes

- Implementar bancos de teste para cada componente.
- Simular o processador com **programas de exemplo** em Assembly MIPS.
- Apresentar:
  - **Printscreens das simulações**
  - **Explicação dos resultados**
  - **Comportamento esperado vs. comportamento observado**

---

## 📁 Estrutura do Projeto

```
Projeto1/
│
├── src/                  # Código VHDL do processador
├── testbench/           # Módulos de teste (testbenches)
├── programas_exemplo/   # Códigos Assembly MIPS para testar o processador
├── resultados/          # Printscreens das simulações e explicações
└── README.md            # Ficheiro com a descrição do projeto
```

---

## 📝 Entrega

A entrega deverá incluir:

- Código VHDL completo e funcional.
- Testbenches para todos os módulos relevantes.
- Programa(s) de exemplo utilizados para teste.
- Relatório em PDF com:
  - Printscreens das simulações.
  - Explicação textual do que acontece em cada fase.
- README.md com descrição do projeto e instruções de utilização.
- Organização adequada das pastas e ficheiros.

---

## 📆 Prazo

> **Data limite de entrega: [inserir data]**

---

## 🧠 Dicas

- Testar cada módulo de forma isolada antes de integrar.
- Utilizar comentários no código para facilitar a leitura.
- Confirmar que os sinais de controlo estão corretos em cada ciclo de instrução.
- Utilizar sinais e variáveis com nomes descritivos.

---

## 👨‍🏫 Avaliação

A avaliação terá em conta:

- Funcionamento correto do processador.
- Qualidade do código VHDL (organização, legibilidade, uso correto das construções).
- Clareza do relatório e explicações fornecidas.
- Grau de completude (instruções suportadas, testes realizados).
- Organização da entrega.

---
