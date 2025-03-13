# lab_3
import math
x = 0.2
epsilon = 0.01
term = math.sin(x)
sum_y = term
n = 2 
while abs(term) >= epsilon:
    term = math.sin(x**n) / n  # n-ci hədd
    sum_y += term
    n += 1

print(f"Sonsuz silsilənin cəmi: {sum_y:.4f}")
