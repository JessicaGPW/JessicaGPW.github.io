# Calculadora de Apostas Múltiplas 🧮

Calculadora web que mostra o **retorno potencial** e o **lucro** de uma aposta múltipla: multiplica as odds informadas e aplica ao valor apostado.

> **EN:** Small vanilla JS web app that calculates potential return and profit for accumulator bets (product of odds × stake).

Criada em conjunto por **Jessica Baptista** e **Thayná Pinheiro**.

## Como funciona

1. Digite as odds separadas por vírgula (ex.: `1.50, 2.10, 1.80`).
2. Digite o valor da aposta (*stake*).
3. Clique em **Calcular**.

```
retorno = stake × (odd₁ × odd₂ × … × oddₙ)
lucro   = retorno − stake
```

A multiplicação das odds é feita com `Array.reduce()`.

## Stack

HTML5 · CSS3 · JavaScript (DOM)

## Como executar

Abra `SRC/index.html` no navegador. Não precisa de instalação.

## Próximos passos

- [ ] Validar entradas (odds vazias, vírgula decimal, valores negativos)
- [ ] Aceitar odds uma a uma, com botão de adicionar/remover
- [ ] Formatação de moeda com `Intl.NumberFormat`
- [ ] Testes unitários da função de cálculo

## Autora

**Jessica Baptista** · [GitHub](https://github.com/JessicaGPW) · [LinkedIn](https://www.linkedin.com/in/baptistajessica/)
