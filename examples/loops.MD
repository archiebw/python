```python
# basic loop
for item in items:
    pass

# dictionary
for item in dictionary:
    # reference key
    print(item)

    # reference value
    print(dictionary[item])

# tuple unpacking
for key, value in dictionary.items():
    # reference key
    print(key)

    # reference value
    print(value)



# enumeration
items = [1, 10, 100]
for item in enumerate(items):
    print(item)

# (0, 1)
# (1, 10)
# (2, 100)


# enumeration with tuple unpacking
items = [1, 10, 100]
for index, value in enumerate(items):
    print(f'index:{index}, value:{value}')
# index:0, value:1
# index:1, value:10
# index:2, value:100

```