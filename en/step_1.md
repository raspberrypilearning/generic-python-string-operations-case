There are four basic string operations that you can use in Python to change the case of a string.

### Change to lower case

- You can change any string to lower case using the `.lower()` method. Like many string operations, it's very greedy, and will change every character.

	```python
	s = 'This is a string with UPPER-CASE characters'
	print(s.lower())
	```

### Change to upper case

- Similarly, the `.upper()` method will greedily change all characters to upper case.

	```python
	s = 'all lower'
	print(s.upper())
	```

### Swap the case

- You can stitch lower to upper case, or upper to lower case, with the `.swapcase()` method.

	```python
	s = 'upper case aNd LOWER CASE'
	print(s.swapcase())
	```

### Title case

- Lastly, you can change the first character of every word to an upper-case letter using the `.title()` method.

	```python
	s = 'the title of my story'
	print(s.title())
	```
