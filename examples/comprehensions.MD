```python

#general syntax
[expr(item) for item in iterable]

# list comprehension
l = [len(word) for word in words]

# set comprehension
numbers = {1, 2, 3, 4}
s = [pow(number, 3) for number in numbers]

# dict comprehensions

{
    key_expr(item): val_expr(item)
    for key, value in d.items()
}

# filtering

# define predicate function - return bool
def predicate(item):
    return True

# call predicate function, (optionally transform result)
[item for item in iterable if predicate(item)]
[expr(item) for item in iterable if predicate(item)]

# dict
{key: value for item in iterable if predicate(item)}


```

