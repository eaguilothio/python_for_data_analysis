# 🐍 Python — Fundamentos para Análisis de Datos

Ejercicios seleccionados por su relevancia directa en análisis de datos.

Cada notebook cubre un concepto fundamental de Python aplicado a preguntas de negocio reales: ventas, empleados, precios, inventario. Sin conceptos que no se usan en datos — no hay `while` (repite código mientras una condición sea verdadera, en análisis de datos siempre recorres una lista o dataset con un número fijo de elementos, para eso usas `for`), ni tuplas (como las listas pero que no se pueden modificar, en datos siempre usas listas), ni sets (colecciones sin duplicados, en datos usas `.unique()`), ni clases (sirven para construir aplicaciones, no para analizar datos).

---

## 📁 Contenido

| Archivo | Tema | Qué practicas |
|---|---|---|
| `01_variables.ipynb` | Variables y tipos de datos | Tipos, casting, operaciones, comparaciones, limpieza de strings |
| `02_listas.ipynb` | Listas | Longitud, máximo, mínimo, suma, índices, ordenar, añadir |
| `03_diccionarios.ipynb` | Diccionarios | Acceder, modificar, añadir, `.get()`, `.items()` |
| `04_sentencias-control.ipynb` | if / elif / else | Clasificar y etiquetar valores según condiciones de negocio |
| `05_bucles.ipynb` | Bucles for | Recorrer listas y diccionarios, filtrar y clasificar con `.append()` |
| `06_funciones.ipynb` | Funciones | Crear funciones, parámetros, valores por defecto, aplicar a listas |

---

## 🛠️ Requisitos

- Python 3.8 o superior
- Jupyter Notebook, JupyterLab o VS Code con la extensión de Python

```bash
pip install jupyter
jupyter notebook
```

---

## 🚀 Orden de lectura

```
01 Variables → 02 Listas → 03 Diccionarios → 04 Sentencias de control → 05 Bucles → 06 Funciones
```
