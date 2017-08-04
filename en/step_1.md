- There are four basic string operations that you can use in Python to change the cast of a string.

### Change to lowercase

- You can change any string to lowercase using the `.lower()` method. Like many string operations, it's very greedy, and will change every character.

	```python
	s = 'This is a string with UPPERCASE characters'
	print(s.lower())
	```

### Swap the case

- You can stitch lower to uppercase and upper to lowercase, using the `.swapcase()` method.

	```python
	s = 'uppercase aNd LOWERCASE'
	print(s.swapcase())
	```

### Title case

- You can change the first character of every word to an uppercase letter using the `.title()` method.

	```python
	s = 'the title of my story'
	print(s.title())
	```
### Change to uppercase

- Lastly the `.upper()` method will greedily change all characters to uppercase.

	```python
	s = 'all lower'
	print(s.upper())
	```
