.mw = Maple Worksheet files
.ipynb = Jupyter Notebook (Python + Sympy)

pdf: Все варианты (SKM_ ...)

## Вариант1.Задание1.

with(plots):
f := x -> 2/(x^2 - 2);
plot(f(x), x = -8 .. 8, title = "Plot of f(x) = 2/(x^2 - 2)", 
     labels = ["x" = "x-axis", "y" = "y-axis"], 
     thickness = 2, resolution = 100, 
     linestyle = line, color = blue);

## Вариант2.Задание1.

```maple
with(plots):
f := x -> sin(2*x)^2;
plotsetup(axislinestyle = [line, line], axisfontstyle = [plain, plain], 
          title = "Plot of f(x) = (sin(2x))^2", 
          labels = ["x" = "x-axis", "y" = "y-axis"], 
          thickness = 2, resolution = 100, 
          linestyle = line, color = blue);
plot(f(x), x = 0 .. Pi);
