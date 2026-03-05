# Prueba

## Prueba de código ejecutable
<py-config>
{
    "packages": ["pandas"]
}
</py-config>
```{.py .pyscript}
import pandas as pd

pd = pd.DataFrame({"A": [1, 2, 3], "B": [4, 5, 6]})
print(pd)


print("Hello, world!")
```

## Prueba de código sin ejecutable
```python
print("Hello, world!")
```

## Prueba de código sin ejecutable 2
```python
import pyodide_js
await pyodide_js.loadPackage('numpy')

import numpy as np

print(np.random.randn(10, 4))
```
