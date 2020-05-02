```python

# Default value
def banner(message, border='-'):
    line = border * len(message)
    print(line)
    print(message)
    print(line)

# Named value when invoking function
banner('hello world with stars', border='*')


# Default values are initialised once, use immutable values and create in function

def add_spam(menu=none):
    if menu == none:
        menu = []
    menu.append('spam')

```
