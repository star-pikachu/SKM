[SymPy Live](https://live.sympy.org)

pdf: Все варианты (SKM_ ...) и только Вариант 2 (Lab1.Var2.pdf)

## Задание_10.Вариант_2: Упростить $$\frac{\sqrt{x-2\sqrt{x-1}}}{\sqrt{x-1}-1}$$

<details>
  <summary>Нажми тут >, чтобы получить ответ:</summary> 1
</details>

### 10.II Maple
```maple
expr := sqrt(x-2*sqrt(x-1)) / (sqrt(x-1) - 1);
simplify(expr);
```
### 10.II Sympy (командой limit)
```python
# код для SymPy Live (уже подключены библиотеки, и вывод на экран без print)

x = symbols('x')
expr = sqrt(x-2*sqrt(x-1)) / (sqrt(x-1) - 1)
limit(expr, x, oo)
```
### 10.II Sympy (командой limit)

## Задание_9.Вариант_2

```python
# код для SymPy Live

# Задаем выражения, чтобы их решить
eq_y = Eq(log(y), 4)  # Equation for y
eq_z = Eq(log(z), 2)  # Equation for z
eq_combined = Eq(log(y, z) + log(z, y), x)

# Решаем для y и z
solution = solve((eq_y, eq_z), (y, z))

# Решаем для x, используя полученные значения y и z (предыдущий шаг)
x_value = log(solution[y], solution[z]) + log(solution[z], solution[y])
x_solution = solve(Eq(x_value, x), x)

# Выводим
print(f"y: {solution[y]}")
print(f"z: {solution[z]}")
print(f"{eq_combined}: {x_solution}")
```
