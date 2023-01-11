# Curso Básico de Manipulación y Transformación de Datos con Pandas y NumPy

1. ¿Cuál es el método para definir un array en Numpy?

```python
np.array([1,2,3])
```

2. ¿Cuál es el resultado de esta operación en NumPy es np.array(['hola','2','4','5'],dtype='float64')

Error en la conversión de los datos.

3. ¿Con qué propiedad de NumPy puede saber la cantidad de dimensiones en un arreglo?

ndim

4. ¿np.arange(0,10) con cuántos elementos creará un array?

10

5. ¿Cuál es el comando de NumPy para crear un array de n elementos con valores de cero (0)?

```python
np.zeros()
```

6. ¿Qué genera np.linspace(0,10,100)?

100 elementos de cero a 10.

7. ¿Qué forma (shape) tiene el siguente array de NumPy?
   [[7 8]
[2 1]
[2 4]]

(3,2)

9. ¿Qué retorna la propiedad std() en un array de NumPy?

La desviación estándar

10. ¿Cuál es el resultado del comando np.sort(arr) siendo arr = np.array([13, 6, 3, 5, 10])?

```python
array([3, 5, 6, 10, 13])
```

11. El comando copia_arr = arr.copy() crea una copia en memoria independiente de arr en un objeto llamado copia_arr. Esto es:

Verdadero

12. ¿Con cuál opción de NumPy se puede filtrar un array de tipo arr = np.array([13, 6, 3, 5, 10]) para solo retornar números superariores a 7?

```python
arr[arr>7]
```

13. ¿Cuál es la estructura base para leer un archivo csv llamado file.csv con Pandas?

```python
pd.read_csv(‘file.csv’)
```

14. ¿En qué se basa el filtrado por iloc a diferencia de loc?

Index

15. ¿Qué se obtiene de comando tipo df_books.loc[0:10, ['Name', 'Author']]?

Retorna las 11 primeras filas del dataset, pero solo de las columnas Name y Author.

16. ¿Qué indica que el comando df.isnull() en Pandas si retorna True en una posición?

Que ese valor es nulo.

17. ¿Qué permite el comando de Pandas df.fillna('missing')?

Reemplazar los valores nulos con la palabra missing.

18. ¿Qué comando de Pandas retorna las n filas del final de un DataFrame?

```python
tail
```

19. Es el comando de Pandas que elimina los duplicados de un DataFrame:

```python
drop_duplicates
```

20. En Pandas es posible aplicar más de una función de grupo por sentencia groupby a una columna en especifico. Esto es:

Verdadero

21. ¿En una sentencia de Apply de Pandas a un dataset es necesario enviarle una función definida previamente?

    Falso
