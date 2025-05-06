## **Tarea Escrita: Rotación y Convolución en Imágenes**


### Parte 1: Rotación de Imágenes

#### **Ejercicio 1A: Rotaciones Exactas**

Dada la imagen 3×3:

$$
\text{Imagen A} =
\begin{bmatrix}
100 & 150 & 200 \\
 50 & 100 & 150 \\
  0 &  50 & 100 \\
\end{bmatrix}
$$

1. Rote la imagen **90° en sentido antihorario**.
2. Rote la imagen original **180°**.

#### **Ejercicio 1B: Rotación Aproximada**

Considere la siguiente imagen 2×2:

$$
\text{Imagen B} =
\begin{bmatrix}
255 & 128 \\
  64 &   0 \\
\end{bmatrix}
$$

Desea rotarla **45° en sentido antihorario** respecto al centro de la imagen.

1. Explique el procedimiento paso a paso incluyendo especificando la matriz de rotación usado y el proceso de centrado y traslación al sistema original.

---

### Parte 2: Convolución

#### **Ejercicio 2A: Cálculo de Dimensiones**

1. Para una imagen de tamaño 5×5, y los siguientes kernels, indique el tamaño de la matriz resultante en cada caso si se usa:

* Padding = 0, Stride = 1
* Padding = 1, Stride = 1

2. Explique los términos *padding* y *stride*.
3. Escriba una fórmula que se pueda aplicar para calcular el tamaño de salida de la imagen en el proceso de convolución.


#### **Ejercicio 2B: Convolución Manual**

Aplique la convolución usando la imagen:

$$
\text{Imagen C} =
\begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9 \\
\end{bmatrix}
$$

y el kernel:

$$
\text{Kernel} =
\begin{bmatrix}
1 & 0 \\
0 & -1 \\
\end{bmatrix}.
$$

Escriba los pasos en detalle para dos casos:

1. Sin usar *zero-padding*
2. Usando *zero-padding*