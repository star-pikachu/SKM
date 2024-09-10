.mw = Maple Worksheet (Maple)
.ipynb = Jupyter Notebook (Python + Sympy)

pdf: Все варианты (SKM_ ...) и только Вариант 2 (Lab1.Var2.pdf)


## Задание_10.Вариант_2
### 10.II Maple
```maple
expr := sqrt(x-2*sqrt(x-1)) / (sqrt(x-1) - 1);
simplify(expr);
```
### 10.II Sympy
```maple
from sympy import symbols, sqrt, simplify

x = symbols('x')
expr = sqrt(x-2*sqrt(x-1)) / (sqrt(x-1) - 1)
simplify(expr)
```
