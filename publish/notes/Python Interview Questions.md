---
title: Python Interview Questions
---
## Basic differences 

- list and tuple:
	- List is Mutable, meaning we can rewrite any element in the list , where as Tuple is Immutable
	- List - More memory 
	- when we want to have something that doesn't need to be updated , we use Tuple as its faster and less memory.
- Iterator vs Iterable :
	- Anything that gives items in sequence, is an iterable
	- Iterator is something that utilizes the functions \_\_iter\_\_ and \_\_next_\__. 
	- In a iterable only \_\_iter\_\_  is mandatory. 
- Mutable data-structures vs Immutable
	- string, int, float, frozenset , tuple are immutable. example - we cant update one character in a string.
	- List, set, Dict are Mutable
- Sets vs Tuples vs Dictionaries
	- **Tuples**: Tuples are similar to lists but are immutable, meaning their elements cannot be changed after creation. Internally, tuples are usually implemented as fixed-size arrays, allowing for memory optimization and better performance in certain scenarios
	- **Sets**: Sets are implemented using hash tables, providing fast access to elements based on their hash values. Sets are unordered collections of unique elements, and time taken to check if an element is present in a set does not depend on the size of the set and expected to run in fast O(1) time.
	- **Dictionaries**: Dictionaries (dicts) are collections of key-value pairs, implemented using hash tables as well. Keys are hashed to determine their position in the table, offering efficient lookups, insertions, and deletions based on keys
- list.sort() vs sorted()
	- `list.sort()` method that modifies the list in-place. Returns **`None`**
		- Syntax : `list.sort(key=key, reverse=reverse)`
	- `sorted()`  builds a new sorted list from an iterable. Returns new list and doesn't modify the iterable.
		- Syntax : `sorted(iterable, key=key, reverse=reverse)`
		- Examples - [Google Education](https://developers.google.com/edu/python/sorting)


## Built In functions: 
- **lambda:** An anonymous function without a name that can be defined using the lambda keyword.
	- Syntax: `lambda argument(s) : expression`
	- These functions can take any number of arguments but can only contain a single expression, which is evaluated and returned. Lambda functions are commonly used in situations where a function is needed briefly and does not require a formal definition.
- **map()**: A built-in function that works as an iterator to apply a single transformation function to all elements of an iterable.
	- Syntax: `map(function, iterable, [iterable 2, iterable 3, ...])`
	- Returns: a `map` object (iterable)
	- **Unequal size**:  If given iterables of different lengths, the resulting combination will only be as long as the smallest iterable passed.
```python Example
base_numbers = [2, 4, 6, 8, 10, 12, 14, 16]
powers = [1, 2, 3, 4, 5]
numbers_powers = list(map(pow, base_numbers, powers))  # converting list to iterator
```

```python output
[2, 16, 216, 4096, 100000]
```
- **filter()**: A built-in function that allows to process an iterable and extract items that satisfy a specific condition.
	- Syntax: `filter(function, iterable)`
	- Returns: a `filter` object (iterable)
	- The function should `True` if the element from iterator satisfied the condition.
- **zip()**: A function used to combine elements from multiple iterables into tuples.
	- **Unequal size**:  If given iterables of different lengths, the resulting combination will only be as long as the smallest iterable passed.
	- Returns: a `zip` object (iterable)
	
- **Generators in Python** are special functions that return iterators, allowing for the generation of a sequence of values on-the-fly. They are created using the `yield` statement instead of `return`, enabling the function to pause its execution and yield a value each time it is called. Once the full sequence is iterated , it gets exhausted so they are meant to be used once.


## Higher-order functions

Higher-order functions in Python refer to functions that can take other functions as arguments or return functions as outputs.
### [`functools`](https://docs.python.org/3/library/functools.html#module-functools "functools: Higher-order functions and operations on callable objects.") : 
- **partial()**: 

## External Modules 
### [[Flask]] 