# tabuada-python — Tabuada em Python

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Terminal](https://img.shields.io/badge/Terminal-000000?style=for-the-badge&logo=gnubash&logoColor=white)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

**Projeto em Python que implementa um gerador de tabuada no terminal, explorando fundamentos da programação como entrada de dados, estrutura de repetição com `for` e formatação de saída com operador `%`.**

</div>

---

## Sobre o projeto

Este projeto foi desenvolvido como exercício prático dos fundamentos da linguagem Python. A proposta foi construir um programa funcional no terminal que demonstrasse, de forma aplicada, a leitura e conversão de dados do usuário, o uso de laço `for` com `range` para iterar sobre uma sequência de valores e a formatação de saída com o operador `%`.

O programa solicita um número inteiro ao usuário e exibe sua tabuada completa de 0 a 10, com cada linha formatada no padrão `n * i = resultado`.

## Objetivos da entrega

- Utilizar **input e conversão de tipo** para capturar um número inteiro do usuário.
- Aplicar o **laço `for` com `range()`** para iterar do 0 ao 10.
- Usar **formatação de string com `%`** para exibir as linhas da tabuada de forma legível.
- Manter o código em **um único arquivo**, legível e direto.

## Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| **Leitura de entrada** | Solicita um número inteiro ao usuário via terminal |
| **Geração da tabuada** | Calcula e exibe as multiplicações de 0 a 10 |
| **Formatação de saída** | Exibe cada linha no formato `n * i = resultado` |

## Conceitos aplicados

```
1. input()          — leitura de dado digitado pelo usuário no terminal
2. int()            — conversão de string para inteiro
3. for              — laço de repetição para iterar sobre a sequência
4. range(11)        — geração da sequência de 0 a 10
5. Operador %       — formatação de string com múltiplos valores inteiros
6. print()          — exibição de cada linha da tabuada formatada
```

## Tecnologias

- **Python 3** — linguagem principal do projeto

Nenhuma biblioteca externa. Roda em qualquer ambiente com Python 3 instalado.

## Estrutura do projeto

```
tabuada-python/
└── main.py    # Código-fonte completo com leitura do número e geração da tabuada
```

## Como usar

### Pré-requisitos

- Python 3 instalado (`python3 --version` para verificar)
- Terminal (Linux, macOS ou Windows com PowerShell/CMD)

### Execução

```bash
# Clone o repositório
git clone https://github.com/jeffsilva03/tabuada-python.git

# Acesse a pasta
cd tabuada-python

# Execute
python3 main.py
```

### Uso no terminal

```
Digite um número: 7
7 * 0 = 0
7 * 1 = 7
7 * 2 = 14
7 * 3 = 21
7 * 4 = 28
7 * 5 = 35
7 * 6 = 42
7 * 7 = 49
7 * 8 = 56
7 * 9 = 63
7 * 10 = 70
```

O programa lê o número e exibe as 11 linhas da tabuada em sequência.

## Lógica de funcionamento

O programa lê um número inteiro e inicia um laço `for` que percorre os valores de 0 a 10 via `range(11)`. A cada iteração, multiplica o número do usuário pelo valor atual do contador e exibe a linha formatada com o operador `%`.

```
Entrada: num
   ↓
for i in range(11):
   ↓
num * i = resultado
   ↓
Saída: 11 linhas formatadas
```

## Limitações conhecidas

| Limitação | Comportamento |
|---|---|
| Apenas números inteiros | O programa usa `int()` — entradas decimais causam erro |
| Sem tratamento de exceção | Entrada não numérica encerra o programa com erro |
| Tabuada fixa de 0 a 10 | O intervalo não é configurável pelo usuário |

> Essas limitações são intencionais para o escopo do exercício. Tratamento de exceções com `try/except` e intervalo configurável podem ser implementados como próximo passo.

## Licença

Este projeto é de uso livre para fins educacionais. Sinta-se à vontade para adaptar, expandir e usar como base de estudo.

---

<div align="center">

Desenvolvido como exercício prático dos fundamentos da linguagem Python.

</div>
