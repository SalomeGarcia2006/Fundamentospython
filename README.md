# Fundamentos de Python

## Descripción

Este repositorio contiene el desarrollo de los laboratorios correspondientes a las secciones 1, 2, 3 y 4 de la guía **Fundamentos de Python**.

El objetivo del proyecto es aplicar los conceptos básicos del lenguaje Python mediante programas sencillos que permiten comprender el funcionamiento de la función `print()`, el uso de literales, variables, operadores aritméticos y operadores de comparación.

---

# Estructura del proyecto

```
fundamentos_python/
│
├── README.md
├── seccion1/
├── seccion2/
├── seccion3/
├── seccion4/
└── src/
```

Cada carpeta contiene los laboratorios desarrollados para la sección correspondiente.

---

# Contenido de las secciones

## Sección 1 - Función print()

En esta sección se realizaron ejercicios para aprender a mostrar información en pantalla utilizando la función `print()`. También se practicó el uso de argumentos, separación de textos y formato de salida.

**Conceptos aprendidos**

- Función `print()`
- Parámetros `sep` y `end`
- Salto de línea (`\n`)
- Tabulación (`\t`)
- Formato de impresión

---

## Sección 2 - Literales y cadenas

En esta sección se trabajó con las cadenas de texto y los diferentes tipos de literales que ofrece Python.

Se realizaron ejercicios donde se imprimieron mensajes, se almacenaron textos en variables y se realizaron operaciones de concatenación y repetición de cadenas.

**Conceptos aprendidos**

- Literales
- Cadenas de texto (`string`)
- Concatenación (`+`)
- Repetición (`*`)

**Ejemplo**

```python
nombre = "Salomé"
apellido = "García"

print(nombre + " " + apellido)
```

**Salida**

```
Salomé García
```

---

## Sección 3 - Operadores

En esta sección se aplicaron los operadores matemáticos y de comparación para resolver diferentes ejercicios.

Se realizaron operaciones como suma, resta, multiplicación, división, potencia, módulo y comparaciones entre valores.

### Operadores aritméticos

| Operador | Descripción |
|----------|-------------|
| + | Suma |
| - | Resta |
| * | Multiplicación |
| / | División |
| // | División entera |
| % | Módulo o residuo |
| ** | Potencia |

### Operadores de comparación

| Operador | Significado |
|----------|-------------|
| == | Igual que |
| != | Diferente de |
| > | Mayor que |
| < | Menor que |
| >= | Mayor o igual |
| <= | Menor o igual |

### Ejemplo

```python
a = 10
b = 5

print(a + b)
print(a > b)
```

**Salida**

```
15
True
```

---

## Sección 4 - Variables

En esta sección se aprendió a crear variables para almacenar información y realizar operaciones utilizando datos ingresados por el usuario.

También se desarrolló un convertidor simple y ejercicios con expresiones matemáticas.

**Conceptos aprendidos**

- Variables
- Asignación de valores
- Entrada de datos con `input()`
- Conversión de datos con `int()` y `float()`
- Expresiones matemáticas

### Ejemplo

```python
kilometros = float(input("Ingrese los kilómetros: "))
millas = kilometros * 0.621371

print(millas)
```

---

# Lógica utilizada

Para resolver los ejercicios se siguió la siguiente metodología:

1. Declarar las variables necesarias.
2. Solicitar datos cuando el ejercicio lo requería.
3. Aplicar los operadores correspondientes.
4. Mostrar el resultado utilizando la función `print()`.
5. Mantener un código claro, organizado y fácil de comprender.

---

# Requisitos

Para ejecutar los programas es necesario tener instalado:

- Python 3
- Visual Studio Code o PyCharm (opcional)
- Git (opcional para control de versiones)

---

# Ejecución

Abrir una terminal dentro del proyecto y ejecutar:

```bash
python nombre_del_archivo.py
```

Ejemplo:

```bash
python laboratorio1.py
```

---

# Autor

**María Salomé García Calle**

**Programa:** Análisis y Desarrollo de Software (ADSO)

**SENA**