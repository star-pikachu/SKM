[SymPy Live](https://live.sympy.org)

pdf: Все варианты (SKM_ ...) и только Вариант 2 (Lab1.Var2.pdf)

## Задание_10.Вариант_2 Опечатка?
### 10.II Maple
```maple
expr := sqrt(x-2*sqrt(x-1)) / (sqrt(x-1) - 1);
simplify(expr);
```
### 10.II Sympy
```python
# библиотека уже подключена в SymPy Live
#from sympy import symbols, sqrt, simplify

x = symbols('x')
expr = sqrt(x-2*sqrt(x-1)) / (sqrt(x-1) - 1)
simplify(expr)
```
