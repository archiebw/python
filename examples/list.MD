```python
#empty list
emptylist = []

#literal list
list = [1,2,3]

# can contain any type
list = [1, 'two' 3]

# multiline
multilinelist = [1,
                 2,
                 3]


# reference from end of list with negative value

list = [0, 1, 2, 3, 4]
print(list[-1]) # 4

print(list[-2]) # 3

# list slicing
lis = [0, 1, 2, 3, 4, 5]

slice = lis[1:3] # [1, 2]
slice = lis[:3] # [1, 2, 3]
slice = lis[3:] # [3, 4, 5]

# copy a list
copy = lis[:]
copy = lis.copy()
copy = list(lis)

# reference items within a copied list are the same although list objects are different
lis is copy # false
lis[1] is copy[1] #true


# index
i = lis.index(2)

# membership
4 in [1, 3, 4] # true
7 in [1, 3, 4] # false
15 not in [1, 3, 4] # true

# delete from index
lis = ['remove', 'a', 'a', 'item']
del lis[1] # ['remove', 'a', 'item']

# removes first instance
lis.remove('a')

# insert
lis = ['this','is','missing','word']
lis.insert('a', 3)

# reverse
lis.reverse()

# <list_reverseiterator> object
reversed(lis)

#sort
lis.sort()

# sort by key (This must be a callable function which accepts a single parameter, sorted on return value)
lis.sort(key=len)

# sorted copy
sorted(lis)


```
