# Prueba

## Ejemplos de codigo ejecutable

### Bloque de codigo Python normal (sin ejecucion) 
```python
print("This is a test")

import numpy as np

print(np.random.randn(10, 4))
```

# Ejemplo ejecutado 
> Este codigo se ejecuta al construir el sitio, y el resultado se muestra en la pagina, en vez del codigo.


```python exec="on"
print("This is a test")
```

Para que el resultado se muestre debajo podemos usar source="above" o source="material-block".

```python exec="on" source="material-block"
print("This is a test")

import numpy as np

print(np.random.randn(10, 4))
```

## Ejemplo con pyodide (ejecucion en el navegador)
```pyodide install="numpy"
print("This is a test")

import numpy as np

print(np.random.randn(10, 4))
```



Fuente: [mkdocs-exec](https://pawamoy.github.io/markdown-exec/usage/)