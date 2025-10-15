## 📘 Proyecto 1: Regresión Lineal

### 🧠 Descripción

Este repositorio contiene una implementación **desde cero** del algoritmo de **Regresión Lineal**, desarrollada en un Jupyter Notebook.
El objetivo es comprender el funcionamiento interno del modelo **sin depender de librerías externas** como scikit-learn.
Se cubren los fundamentos teóricos, la deducción matemática y una implementación práctica paso a paso.

La `regresión lineal` es un método estadístico utilizado para **predecir** una variable dependiente continua (variable objetivo) a partir de una o más variables independientes.

#### ¿Por qué es importante la Regresión Lineal?

* **Simplicidad e interpretabilidad:** Es fácil de entender e interpretar, por lo que suele ser el punto de partida para aprender sobre aprendizaje automático.
* **Base de otros modelos:** Muchos algoritmos más avanzados, como la regresión logística o las redes neuronales, se construyen sobre los conceptos de la regresión lineal.

#### Supuestos de la Regresión Lineal

1. **Linealidad:** La relación entre las variables de entrada (X) y la salida (Y) debe ser una línea recta.
2. **Independencia de los errores:** Los errores en las predicciones no deben influirse entre sí.
3. **Varianza constante (Homoscedasticidad):** Los errores deben tener una dispersión uniforme a lo largo de todos los valores de entrada.
   Si la dispersión cambia (por ejemplo, se abre o se estrecha), se denomina **heteroscedasticidad**, y representa un problema para el modelo.

![homoscedasticity.png](attachment\:homoscedasticity.png)

4. **Normalidad de los errores:** Los errores deben seguir una distribución normal (en forma de campana).
5. **No multicolinealidad (en regresión múltiple):** Las variables de entrada no deben estar demasiado correlacionadas entre sí.
6. **No autocorrelación:** Los errores no deben mostrar patrones repetitivos, especialmente en datos temporales.
7. **Aditividad:** El efecto total sobre Y es la suma de los efectos individuales de cada X, sin interacciones entre ellas.

---

### 📊 Contenido del Notebook

1. **Introducción teórica a la regresión lineal.**
2. **Regresión Lineal Simple:**

   Se resuelve utilizando **tres métodos diferentes**, explicando cómo funciona cada uno, sus ventajas y desventajas,
   junto con una **representación gráfica** de cada caso.

   * Mínimos Cuadrados (método estadístico)
   * Ecuación Normal (método algebraico)
   * Descenso del Gradiente (método de aprendizaje automático)

---

### ⚙️ Tecnologías Utilizadas

* **Python 3.11+**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**

---

### 🧩 Contenidos

```
├── simple_linear_regression.ipynb     # Notebook principal con teoría y código -> Idioma: Inglés
├── README.md                          # Archivo principal
├── README_ES.md                       # Este archivo (versión en español)
```

---

### 📚 Referencias

> * [https://www.geeksforgeeks.org/machine-learning/linear-regression-python-implementation](https://www.geeksforgeeks.org/machine-learning/linear-regression-python-implementation)
> * [https://www.geeksforgeeks.org/machine-learning/ml-linear-regression](https://www.geeksforgeeks.org/machine-learning/ml-linear-regression)
> * [https://www.geeksforgeeks.org/machine-learning/ml-normal-equation-in-linear-regression](https://www.geeksforgeeks.org/machine-learning/ml-normal-equation-in-linear-regression)
> * [https://www.geeksforgeeks.org/machine-learning/gradient-descent-in-linear-regression](https://www.geeksforgeeks.org/machine-learning/gradient-descent-in-linear-regression)

---

### 👨‍💻 **Autor** : [@RubenGonV](https://github.com/RubenGonV)

> 📬 Si este proyecto te resultó útil, considera dejar una ⭐ en el repositorio — ¡motiva más de lo que parece!
