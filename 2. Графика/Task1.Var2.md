```maple
with(plots):
f := x -> sin(2*x)^2;
plotsetup(axislinestyle = [line, line], axisfontstyle = [plain, plain], 
          title = "Plot of f(x) = (sin(2x))^2", 
          labels = ["x" = "x-axis", "y" = "y-axis"], 
          thickness = 2, resolution = 100, 
          linestyle = line, color = blue);
plot(f(x), x = 0 .. Pi);
