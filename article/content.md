![Capa Artigo](https://i.ibb.co/n7G8Sgw/capa-artigo.png)

# Além das Dimensões: Desbravando Matrizes Multidimensionais com Numpy

### 1. Introdução

Matrizes multidimensionais em numpy são como arranjos de dados organizados em várias dimensões. Elas são a espinha dorsal de muitas operações de ciência de dados e aprendizado de máquina, permitindo lidar com conjuntos de dados complexos de forma eficiente.

Podemos identificar a quantidade de dimensões que uma matriz possui com funções próprias ou contando os colchetes finais do código.
<br><br>

### 2. Como criar matrizes multidimensionais de 2d até 4d.

Com o numpy, você pode criar matrizes de multidimensional em um piscar de olhos! Aqui está um exemplo de código para criar matrizes de 2D a 4D:

```python

import numpy as np

# 2D
matrix_2d = np.array([[1, 2, 3], [4, 5, 6]])

# 3D
matrix_3d = np.array([[[1, 2], [3, 4]], [[5, 6], [7, 8]]])

# 4D
matrix_4d = np.array([[[[1, 2], [3, 4]], [[5, 6], [7, 8]]], [[[9, 10], [11, 12]], [[13, 14], [15, 16]]]])
```

Podemos preencher as matrizes criadas com <i>placeholders</i>, sejam eles zeros ou uns com as funções próprias do numpy. Verificamos isso logo abaixo:
```python

import numpy as np

# Cria uma matriz 2x3 preenchida com zeros
zeros_matrix = np.zeros((2, 3))

```
<br><br>

### 3. Como realizar operações aritméticas em matrizes multidimensionais.

Você pode fazer todo tipo de aritmética com essas matrizes. Isso inclui, soma, subtração, multiplicação e divisão entre outras. Podem ser facilmente aplicadas e possuem muitas utilidades. Podemos observar cada operação no código abaixo:

```python

import numpy as np

# Matriz 3D A
matrix_3d_a = np.array([[[1, 2], [3, 4]], [[5, 6], [7, 8]]])

# Matriz 3D B
matrix_3d_b = np.array([[[9, 10], [11, 12]], [[13, 14], [15, 16]]])

# Soma
result_sum_3d = matrix_3d_a + matrix_3d_b

# Subtração
result_sub_3d = matrix_3d_a - matrix_3d_b

# Multiplicação
result_mul_3d = matrix_3d_a * matrix_3d_b

# Divisão
result_div_3d = matrix_3d_a / matrix_3d_b
```
<br><br>
### 4. Como interagir com uma matriz a partir de outra matriz.

Às vezes, você precisa fazer operações em uma matriz baseadas em outra matriz. Veja como fazer isso:
```python

import numpy as np


# Criando duas matrizes 3D
matrix_3d_a = np.array([[[1, 2], [3, 4]], [[5, 6], [7, 8]]])
matrix_3d_b = np.array([[[9, 10], [11, 12]], [[13, 14], [15, 16]]])

# Exibindo o resultado
print("Matriz A:")
print(matrix_3d_a)

print("\nMatriz B:")
print(matrix_3d_b)

print("\nResultado da multiplicação elemento a elemento:")
print(result_multiply)

# Resultado
# [[[  9  20]
#   [ 33  48]]
#
#  [[ 65  84]
#   [ 91 128]]]
```

### Conclusão

Gostou desse breve mergulho no mundo das matrizes multidimensionais em numpy? Surpresa! todo esse artigo foi gerado por uma inteligência artificial, sendo revisado por humanos 😯. Incrível pensar que a base disso são as matrizes, não é?

Siga-me para mais dicas e truques sobre ciência de dados e programação! 
<br><br>
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucasaribeiro/)  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Lucas-Ribeir0) [![Gmail](https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:lucasantonioribeiro0@gmail.com)

 - Criação da capa: [Lexica.art](https://lexica.art/)
 - Geração de títulos e conteúdo: [ChatGPT](https://chat.openai.com)
 - Revisado por: Humanos! 🤖

<br><br><br/>#DataScience #Numpy #Python