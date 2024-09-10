.mw = Maple Worksheet (Maple)
.ipynb = Jupyter Notebook (Python + Sympy)

pdf: Все варианты (SKM_ ...) и только Вариант 2 (Lab1.Var2.pdf)

Вариант_2:

## Задание_10. Упростить выражение Maple (задаем выражение, упрощаем функцией simplify).

```maple
expr := sqrt(x-2*sqrt(x-1)) / (sqrt(x-1) - 1);
simplify(expr);
```

## Задание_10. Упростить выражение Sympy (задаем выражение, упрощаем функцией simplify).

```maple
from sympy import symbols, sqrt, simplify

x = symbols('x')
expr = sqrt(x-2*sqrt(x-1)) / (sqrt(x-1) - 1)
simplify(expr)
```
