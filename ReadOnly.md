# Python Basic Data Types

## Numeric Types

### Integer (`int`)

- Whole numbers without a decimal point.
- Examples: `42`, `-7`, `0`

```python
a = 10
b = -5

#Floating-Point Number (float):
##Numbers with a decimal point.
-Examples: 3.14, -0.001, 2.0

python

pi = 3.14
gravity = 9.81

Complex Number (complex):

    Numbers with real and imaginary parts.
    Example: 3 + 4j

python

    z = 3 + 4j

Sequence Types

    String (str):
        Sequence of characters enclosed in single, double, or triple quotes.
        Examples: 'hello', "world", '''multiline string'''

    python

name = "Alice"
greeting = 'Hello, World!'
multiline = """This is
a multiline
string."""

List (list):

    Ordered, mutable collection of items.
    Examples: [1, 2, 3, 'a', 'b', 'c']

python

numbers = [1, 2, 3, 4, 5]
mixed = [1, 'two', 3.0, [4, 5]]

Tuple (tuple):

    Ordered, immutable collection of items.
    Examples: (1, 2, 3)

python

    point = (10, 20)
    dimensions = (1920, 1080)

Mapping Type

    Dictionary (dict):
        Unordered collection of key-value pairs.
        Examples: {'name': 'Alice', 'age': 25}

    python

    person = {'name': 'Alice', 'age': 30}
    inventory = {'apples': 5, 'oranges': 3}

Set Types

    Set (set):
        Unordered collection of unique items.
        Examples: {1, 2, 3}

    python

fruits = {'apple', 'banana', 'cherry'}

Frozen Set (frozenset):

    Immutable version of a set.
    Example: frozenset([1, 2, 3])

python

    frozen_fruits = frozenset(['apple', 'banana', 'cherry'])

Boolean Type

    Boolean (bool):
        Represents one of two values: True or False.
        Examples: True, False

    python

    is_active = True
    is_logged_in = False

None Type

    None Type (NoneType):
        Represents the absence of a value.
        Example: None

    python

result = None