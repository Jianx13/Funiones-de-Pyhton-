# 🐍 Funciones Incorporadas de Python (Built-in Functions)

Este repositorio contiene una referencia de las funciones incorporadas de Python, junto con ejemplos prácticos de uso.

---

## 📋 Lista de Funciones Incorporadas

### 🔢 Funciones Numéricas y Matemáticas

| Función | Definición |
|--------|-----------|
| `abs(x)` | Retorna el valor absoluto de un número. |
| `round(number, ndigits)` | Redondea un número al número de dígitos especificado. |
| `pow(base, exp, mod=None)` | Retorna `base` elevado a la potencia `exp`. Si se pasa `mod`, retorna `(base**exp) % mod`. |
| `divmod(a, b)` | Retorna una tupla con el cociente y el residuo de la división de `a` entre `b`. |
| `sum(iterable, start=0)` | Suma todos los elementos de un iterable, comenzando desde `start`. |
| `min(iterable)` | Retorna el elemento más pequeño de un iterable o de varios argumentos. |
| `max(iterable)` | Retorna el elemento más grande de un iterable o de varios argumentos. |

---

### 🔤 Funciones de Tipo y Conversión

| Función | Definición |
|--------|-----------|
| `int(x)` | Convierte un valor a entero. |
| `float(x)` | Convierte un valor a número de punto flotante. |
| `str(x)` | Convierte un valor a cadena de texto. |
| `bool(x)` | Convierte un valor a booleano (`True` o `False`). |
| `list(iterable)` | Convierte un iterable en una lista. |
| `tuple(iterable)` | Convierte un iterable en una tupla. |
| `set(iterable)` | Convierte un iterable en un conjunto (sin duplicados). |
| `dict(**kwargs)` | Crea un diccionario. |
| `complex(real, imag)` | Crea un número complejo con parte real e imaginaria. |
| `bytes(source)` | Crea un objeto de bytes inmutable. |
| `bytearray(source)` | Crea un objeto de bytes mutable. |
| `chr(i)` | Retorna el carácter Unicode correspondiente al entero `i`. |
| `ord(c)` | Retorna el entero que representa el carácter Unicode `c`. |
| `hex(x)` | Convierte un entero a su representación hexadecimal en string. |
| `oct(x)` | Convierte un entero a su representación octal en string. |
| `bin(x)` | Convierte un entero a su representación binaria en string. |

---

### 🧠 Funciones de Introspección y Objetos

| Función | Definición |
|--------|-----------|
| `type(object)` | Retorna el tipo del objeto. |
| `isinstance(object, classinfo)` | Retorna `True` si el objeto es una instancia de la clase especificada. |
| `issubclass(class, classinfo)` | Retorna `True` si la clase es subclase de otra. |
| `id(object)` | Retorna el identificador único del objeto en memoria. |
| `dir(object)` | Retorna una lista con los atributos y métodos del objeto. |
| `vars(object)` | Retorna el `__dict__` del objeto (atributos como diccionario). |
| `hasattr(object, name)` | Retorna `True` si el objeto tiene el atributo especificado. |
| `getattr(object, name)` | Obtiene el valor de un atributo del objeto. |
| `setattr(object, name, value)` | Establece el valor de un atributo del objeto. |
| `delattr(object, name)` | Elimina un atributo del objeto. |
| `callable(object)` | Retorna `True` si el objeto es llamable (como una función). |
| `hash(object)` | Retorna el valor hash del objeto. |
| `repr(object)` | Retorna una representación en string del objeto (para desarrolladores). |

---

### 🔁 Funciones de Iteración y Secuencias

| Función | Definición |
|--------|-----------|
| `len(s)` | Retorna el número de elementos de un objeto (lista, string, etc.). |
| `range(start, stop, step)` | Genera una secuencia de números. |
| `enumerate(iterable, start=0)` | Retorna un iterador con índice y valor de cada elemento. |
| `zip(*iterables)` | Combina varios iterables en tuplas elemento a elemento. |
| `map(function, iterable)` | Aplica una función a cada elemento de un iterable. |
| `filter(function, iterable)` | Filtra elementos de un iterable según una función que retorna booleano. |
| `sorted(iterable, key, reverse)` | Retorna una lista ordenada del iterable. |
| `reversed(sequence)` | Retorna un iterador que recorre la secuencia en orden inverso. |
| `iter(object)` | Retorna un iterador del objeto. |
| `next(iterator, default)` | Obtiene el siguiente elemento de un iterador. |
| `any(iterable)` | Retorna `True` si al menos un elemento del iterable es verdadero. |
| `all(iterable)` | Retorna `True` si todos los elementos del iterable son verdaderos. |
| `slice(start, stop, step)` | Crea un objeto `slice` para indexar secuencias. |

---

### 📂 Funciones de Entrada/Salida

| Función | Definición |
|--------|-----------|
| `print(*objects, sep, end)` | Imprime objetos en la consola. |
| `input(prompt)` | Lee una línea de texto ingresada por el usuario. |
| `open(file, mode)` | Abre un archivo y retorna un objeto de archivo. |
| `format(value, format_spec)` | Formatea un valor según una especificación dada. |

---

### 🏗️ Funciones de Construcción de Clases y Funciones

| Función | Definición |
|--------|-----------|
| `object()` | Retorna un nuevo objeto base. |
| `super()` | Retorna un objeto proxy que delega llamadas a la clase padre. |
| `property(fget, fset, fdel)` | Crea un atributo administrado (getter/setter/deleter). |
| `staticmethod(function)` | Convierte una función en método estático. |
| `classmethod(function)` | Convierte una función en método de clase. |

---

### 🛠️ Funciones de Evaluación y Ejecución

| Función | Definición |
|--------|-----------|
| `eval(expression)` | Evalúa una expresión Python dada como string. |
| `exec(object)` | Ejecuta código Python dinámicamente. |
| `compile(source, filename, mode)` | Compila código fuente en un objeto de código ejecutable. |
| `globals()` | Retorna el diccionario de la tabla de símbolos global actual. |
| `locals()` | Retorna el diccionario de la tabla de símbolos local actual. |

---

### 🧩 Otras Funciones Útiles

| Función | Definición |
|--------|-----------|
| `help(object)` | Muestra documentación de ayuda del objeto. |
| `memoryview(object)` | Crea una vista de memoria de un objeto que soporta el protocolo buffer. |
| `frozenset(iterable)` | Crea un conjunto inmutable. |
| `breakpoint()` | Llama al depurador en el punto donde se invoca (Python 3.7+). |
| `__import__(name)` | Importa un módulo dinámicamente (uso avanzado). |

---

## 📁 Estructura del Repositorio

```
📦 python-builtins/
├── 📄 README.md                  ← Este archivo
└── 📁 ejemplos/
    ├── 📄 funciones_ejemplo.py   ← Ejemplos de uso de funciones incorporadas
    └── 📄 llamar_ejemplo.py      ← Importa y llama funciones del otro archivo
```

---

## 🚀 Cómo usar los ejemplos

```bash
# Ejecutar el archivo de ejemplos directamente
python ejemplos/funciones_ejemplo.py

# Ejecutar el archivo que llama al otro
python ejemplos/llamar_ejemplo.py
```

---

## 📚 Recursos adicionales

- [Documentación oficial de Python - Built-in Functions](https://docs.python.org/3/library/functions.html)
- [Python Tutorial en Español](https://docs.python.org/es/3/tutorial/)

---

> 💡 **Tip:** Puedes explorar todas las funciones incorporadas en Python ejecutando `dir(__builtins__)` en tu intérprete.
