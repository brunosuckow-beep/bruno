# Calculadora Python

Uma calculadora simples com as quatro operaçoes basicas.

## Funcionalidades

- Soma
- Subração
- Multiplicação
- Divisão (com proteção contra divisão por sero)

## Como usar

```python
from calculadora import somar, subtrair, multiplicar, dividir

resultado = somar(10, 5)      # 15
resultado = subtrair(10, 5)   # 5
resultado = multiplicar(10, 5) # 50
resultado = dividir(10, 5)    # 2.0
```

## Testes

```bash
pytest test_calculadora.py
```
