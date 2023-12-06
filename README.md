# Fundamentos de Programação Paralela - Hackathon

## Filtro Laplaciano

### EQUIPE
- Danilho Scheltes
- Felipe Lima
- Guilherme Martinho
- Rafael Santos
- Rodrigo Macedo

### PROBLEMA
O problema consiste em otimizar a aplicação do filtro laplaciano em matrizes quadradas. Este filtro é particularmente útil para detecção de bordas em imagens.

Considerando uma imagem como uma matriz \( M \), sua filtragem consiste em realizar uma operação de convolução entre \( M \) e uma matriz de pesos \( K \), denominada kernel.

Em outras palavras, a matriz da imagem filtrada \( F \) é definida como \( F = M * K \).

Para o caso do filtro laplaciano, pode-se utilizar a seguinte matriz como kernel:

$$
K = \begin{bmatrix}
     0 & -1 &  0 \\
    -1 &  4 & -1 \\
     0 & -1 &  0
\end{bmatrix}
$$
