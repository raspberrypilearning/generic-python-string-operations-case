Hay cuatro operaciones de cadena básicas que puedes usar en Python para cambiar las mayúsculas y minúsculas de una cadena.

### Cambiar a minúsculas

- Puedes cambiar cualquier cadena a minúsculas usando el método `.lower()`. Como muchas operaciones de cadena, este método es muy codicioso y cambiará todos los caracteres.

    ```python
    s = 'Esta es una cadena con caracteres en MAYÚSCULAS'
    print(s.lower())
    ```

### Cambiar a mayúsculas

- De manera similar, el método `.upper()` cambiará codiciosamente todos los caracteres a mayúsculas.

    ```python
    s = 'todo en minúsculas'
    print(s.upper())
    ```

### Intercambiar mayúsculas y minúsculas

- Puedes unir minúsculas a mayúsculas, o mayúsculas a minúsculas, con el método `.swapcase()`.

    ```python
    s = 'mayúsculas cOn MINÚSCULAS'
    print(s.swapcase())
    ```

### Títulos

- Por último, puedes cambiar el primer carácter de cada palabra a una letra mayúscula utilizando el método `.title()`.

    ```python
    s = 'el título de mi historia'
    print(s.title())
    ```
