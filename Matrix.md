# Matrix

In mathematics, a matrix is an arrangement of numbers, symbols, or expressions arranged in rows and columns so as to form a square shape

## Definition
$$
\begin{equation*}
\begin{Bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{Bmatrix}
\end{equation*}
$$

2 x 3 matrix ( 2 rows, 3 columns )

---

## Transpose

Transpose of a matrix is the operator located in the matrix along its main diagonal. This operator swaps every row and column in the matrix
$$
\begin{equation*}
\begin{Bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{Bmatrix}^T =
\begin{Bmatrix}
1 & 4 \\
2 & 5 \\
3 & 6 \\
\end{Bmatrix}
\end{equation*}
$$
`2 x 3 -> 3 x 2`

---

## Addition / Subtraction

$$
\begin{equation*}
\begin{Bmatrix}
1 & 3 & 2 \\
2 & 4 & 7 \\
\end{Bmatrix} +
\begin{Bmatrix}
0 & 1 & 5 \\
3 & -2 & 8
\end{Bmatrix} =
\begin{Bmatrix}
1 & 4 & 7 \\
5 & 2 & 15
\end{Bmatrix}
\end{equation*}
$$

---

## Multiplication

### Rule

- Matrix multiplication can only be performed if number of first matrix columns  equal to number of second matrix rows
- Multiplication result is the (number of first matrix row) x (number of second matrix column) 

$$
\begin{equation*}
\begin{Bmatrix}
1 & 3 & 2 \\
2 & 4 & 7 \\
\end{Bmatrix} \times
\begin{Bmatrix}
0 & 3 \\
1 & -2 \\
5 & 8
\end{Bmatrix} =
\begin{Bmatrix}
13 & 13 \\
39 & 54 \\
\end{Bmatrix}
\end{equation*}
$$

### Explanation

1. `13 = (0 x 1) + (1 x 3) + (5 x 2)` 
2. `39 = (0 x 2) + (1 x 4) + (5 x 7)`
3. `13 =(3 x 1) + (-2 x 3) + (8 x 2)`
4. `54 = (3 x 2) + (-2 x 4) + (8 x 7) `

---

## Trace

In linear algebra, the trace of a matrix is defined as the sum of each element on the main diagonal of the matrix
$$
\begin{equation*}
trace(\begin{Bmatrix}
1 & 3 & 2 \\
2 & 4 & 7 \\
1 & 3 & 8 \\
\end{Bmatrix}) = 13
\end{equation*}
$$
trace = `1 + 4 + 8 = 13`
$$
\begin{equation*}
trace(\begin{Bmatrix}
1 & 3 & 2 \\
2 & 4 & 7 \\
\end{Bmatrix}) = 5
\end{equation*}
$$
trace = `1 + 4 = 5`

---

## Determinant

In linear algebra,  the determinant is a value that can be calculated from the elements of a matrix. The determinant of matrix A is written with the sign det, det A, or |A|. The determinant can be thought of as a scaling factor of the transformation described by the matrix

### Formula

- 2D Matrix
  $$
  A = \begin{Bmatrix}
  a & b \\
  c & d \\
  \end{Bmatrix}
  
  \newline\newline
  |A| = ab - dc
  $$

- 3D Matrix
  $$
  A = \begin{Bmatrix}
  a & b & c \\
  d & e & f \\
  g & h & i
  \end{Bmatrix}
  
  \newline\newline
  |A| = a(ei - fh) - b(di - fg) + c(dh - eg)
  $$
  

---

## Reference

https://youtu.be/p48uw2vFWQs

https://play.google.com/store/apps/details?id=com.aswdc_linearalgebra

https://www.wikipedia.org

