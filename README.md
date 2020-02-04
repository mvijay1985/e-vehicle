# Electric Vehicle
Electric Vehicle Charge station
[python](https://www.anaconda.com/distribution/)
```python
from typing import Iterator

def fib(n: int) -> Iterator[int]:
    a, b = 0, 1
    while a < n:
        yield a
        a, b = b, a + b
```

Python Codes for sine wave generation
```python
import numpy as np
import matplotlib.pyplot as plt
%matplotlib notebook
from scipy.optimize import fsolve

def f(x):
    y = 2.0 * x**2 + 3.0*x - 10
    return y

x= np.linspace(-5,2)
print(x)
plt.plot(x,f(x))
plt.plot(x,np.zeros(len(x)))
plt.tick_params(direction='in')
plt.xlabel('X-Variable')
plt.ylabel('function f(x)')
plt.tight_layout()
```
# [Volatge Sag in Power Quality](vsag.html) 
# [sine](sin.tex) 
