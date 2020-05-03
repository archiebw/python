```python
#A tuple is an immutable sequence of objects
tuple = ('norway', 2, 3.56)

# concat
tuple = tuple + (3, 5.45)

# repeat
tuple = tuple * 2

# nested objects
tuple = (('norway', 3), 2, 3.56)

# to reference nested object
value = tuple[1][2]

# empty tuple
tuple = ()

# single element tuple
tuple = (2,)

# brackets can be ommited
tuple = 1, 4, 5, 6

def min_max(number):
    return min(number), max(number)    

# unpacking tuple
 min, max = min_max([1, 5, 7, 8, 3])

# nested unpacking

(a, b, (c, d)) = (1, 2, (3, 4))

```
