```python
string = "use either"
string = 'quotes'


string = '''Python 
multi
line
string
'''

string = 'universal \n newline uses platform associated carriage return'

string = r'raw strings do not escape eg. c:\dev\python'

# string built in functions

len('length of string')

joined = '-'.join('join','seperated','by -')

split = joined.split('-')

# partition
before, seperator, after = 'before-after'.partition('-')

# convention for unused/dummy variables _
before, _, after = 'before-after'.partition('-')

# string .format
'{0} lat, {1} long'.format(69.5, 43.6)

'{lat} lat, {long} long'.format(lat=69.5, long=43.6)

# string literals / f'strings

age = 20
literal = f'You are {age} years old!'

import math
f'Math constants: Pi={math.pi}, e={math.e}'

```
