# Curso Básico de Manipulación y Transformación de Datos con Pandas y NumPy

### 1. ¿Podemos considerar el array como el objeto principal de NumPy?
    Verdadero

### 2. ¿Cuál es el resultado de esta operación en NumPy es np.array(['hola','2','4','5'],dtype='float64')
    Error en la conversión de los datos.

### 3. ¿Para qué sirve el comando expand_dims de Numpy?
    Sumar una dimensión al array.

### 4. ¿np.arange(0,10) con cuántos elementos creará un array?
    10

### 5. ¿Cuál es el comando de NumPy para crear un array de n elementos con valores de cero (0)?
```python:
np.zeros()
```

### 6. ¿Qué genera np.linspace(0,10,100)?
    100 elementos de cero a 10.

### 7. ¿Qué forma (shape) tiene el siguente array de NumPy?  
[[7 8]
[2 1]
[2 4]]

    (3,2)

### 8. ¿Cuál es el resultado del comando np.max(arr) siendo arr = np.array([13, 6, 3, 5, 10])?
    13

### 9. ¿Cuál es el resultado del comando np.argmax(arr) siendo arr = np.array([13, 6, 3, 5, 10])?
    0

### 10. ¿Qué retorna la propiedad std() en un array de NumPy?
    La desviación estándar

### 11. El comando copia_arr = arr.copy() crea una copia en memoria independiente de arr en un objeto llamado copia_arr. Esto es:
    Verdadero

### 12. ¿Con cuál opción de NumPy se puede filtrar un array de tipo arr = np.array([13, 6, 3, 5, 10]) para solo retornar números superariores a 7?
```python:
arr[arr>7]
```

### 13. ¿Cuál es la estructura base para leer un archivo csv llamado file.csv con Pandas?
```python:
pd.read_csv(‘file.csv’)
```

### 14. ¿Qué se obtiene de comando tipo df_books.loc[0:10, ['Name', 'Author']]?
    Retorna las 11 primeras filas del dataset, pero solo de las columnas Name y Author.

### 15. ¿Qué permite el comando de Pandas df.fillna('missing')?
    Reemplazar los valores nulos con la palabra missing.

### 16. ¿Cuál es el comando de Pandas que retorna count, mean,std, min, max y otras variables para todas las columnas numéricas en un DataFrame?
```python:
describe
```

### 17. ¿Qué comando de Pandas retorna las n filas del final de un DataFrame?
```python:
tail
```

### 18. Es el comando de Pandas que elimina los duplicados de un DataFrame:
```python:
drop_duplicates
```

### 19. En Pandas es posible aplicar más de una función de grupo por sentencia groupby a una columna en especifico. Esto es:
    Verdadero

### 20. ¿Qué debería ir en el parámetro how de la sentencia merge en Pandas para que muestre solo los match en ambos DataFrames?
```python:
inner
```

### 21. ¿En una sentencia de Apply de Pandas a un dataset es necesario enviarle una función definida previamente?
    Falso

