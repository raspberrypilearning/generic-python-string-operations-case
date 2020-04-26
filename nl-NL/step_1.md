Er zijn vier basistekstbewerkingen die je in Python kunt gebruiken om het hoofd- en kleinelettergebruik van een tekenreeks te wijzigen.

### Wissel naar kleine letters

- Je kunt elke string in kleine letters wijzigen met de methode `.lower()`. Net als veel stringbewerkingen is het erg hebzuchtig en zal elk karakter veranderen.

    ```python
    s = 'Dit is een string met HOOFDLETTERS'
print(s.lower())
    ```

### Wissel naar hoofdletters

- Op dezelfde manier verandert de methode `.upper()` gretig alle letters in alle hoofdletters.

    ```python
    s = 'alles klein'
print(s.upper())
    ```

### Verwissel hoofd- en kleine letters

- Je kunt kleine letters in hoofdletters of kleine letters in hoofdletters veranderen met de methode `.swapcase()`.

    ```python
    s = 'hoofdletters eN kleine letters'
print(s.swapcase())
    ```

### Titeltekst

- Ten slotte kun je het eerste teken van elk woord wijzigen in een hoofdletter met behulp van de methode `.title()`.

    ```python
    s = 'de titel van mijn verhaal'
print(s.title())
    ```
