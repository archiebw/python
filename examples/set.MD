```python
# unordered collection of unique items
# mutable

# Sets have similar syntax to dict but contain single values rather than key value pairs
s = {14, 42, 50 245}

# An empty set (cannot use {} as this is an empty dict)
s = set()

# add a single item, will not error if already exists
s.add(15)

# add multiple items
s.update([15, 23])

# remove an item, will not error if key not present
s.discard(23)

# remove an item, error if key not present
s.remove(23)

# copy
t = s.copy()
t = set(s)

# converting a list to a set removes duplicates
l = [1, 1, 2, 3]
s = set(l)
# {1, 2, 3}


# set algebra

a.union(b)
a.intersection(b)

# a not in b
a.difference(b)

# in a or b, but not both
a.symmetricdifference(b)
```
