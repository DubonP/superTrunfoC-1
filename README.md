# Super Trunfo em C - Nível Novato

Este é um programa desenvolvido em linguagem C para cadastrar e exibir informações de duas cartas do jogo **Super Trunfo**, com o tema **Cidades**.

## Objetivo

Praticar os fundamentos da linguagem C, como:
- Declaração de variáveis
- Entrada e saída de dados com `scanf` e `printf`
- Organização e indentação de código

## Funcionalidades

- Cadastro de 2 cartas com os seguintes dados:
  - Estado (char de A a H)
  - Código da carta (ex: A01)
  - Nome da cidade
  - População
  - Área (em km²)
  - PIB (em bilhões de reais)
  - Número de pontos turísticos
- Exibição das informações organizadas ao final.

## Como compilar e executar (Windows)

### Pré-requisitos:
- GCC instalado (via MinGW)

### Comandos:
```bash
gcc super_trunfo.c -o super_trunfo
super_trunfo
