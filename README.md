# Pong - Refatorado com POO e SOLID

Este projeto consiste em uma implementação do clássico jogo Pong utilizando a biblioteca Pygame em Python.  
O código foi refatorado aplicando conceitos de Programação Orientada a Objetos (POO) e princípios SOLID, com foco em organização, legibilidade e manutenção.

---

## Objetivo

O objetivo deste projeto é demonstrar:

- Aplicação de **abstração**
- Uso de **encapsulamento**
- Separação de responsabilidades
- Aplicação dos princípios **SOLID**
- Melhoria da legibilidade do código
- Estruturação com boas práticas de desenvolvimento

---

## Conceitos Aplicados

### Abstração
As entidades do jogo foram representadas por classes:
- `Bola`
- `Raquete`
- `Game`
- `Menu`

---

### Encapsulamento
Cada classe é responsável por seus próprios dados e comportamentos:

Exemplo:
```python
self.bola.mover()
