```python
# ordered by insertion from >=3.7
# keys -> immutable
# values -> mutable

emptydict = {}

#dictionary / map object
d = {'k1': 'value1', 'k2': 'value2'}

# add to dict
d['new'] = 'value'

# convert list of tuples to dict
names_and_ages = [('alice', 32), ('bob', 22), ('charlie', 55)]
d = dict(names_and_ages)
# {'alice': 32, 'bob': 22, 'charlie': 55

# create dict from key-value pairs
d = dict(a='alpha', b='bravo', c='charlie')
# {'a': 'alpha', 'b': 'bravo', 'c': 'charlie'}

# copy a dict
e = d.copy()
f = dict(d)

# update dict with multiple values
d.update(e)

# remove a item
del d['key1']

# membership checks for key presence
d = {'k1': 1, 'k2': 2, 'k3': 3}
k1 in d # true

```
