# understanding_dataclasses_python
Understanding Dataclasses in Python

This repository contains a series of Jupyter notebooks that provide a comprehensive understanding of dataclasses in Python. Below is a brief description of each notebook in the sequence they are written:

1. **00_simple_classes.ipynb**:
   - This notebook introduces simple classes in Python and demonstrates how to create a class, define its attributes, and implement methods. It also shows how to override the `__repr__` and `__eq__` methods for better representation and comparison of class instances.

2. **01_Introduction_to_dataclasses.ipynb**:
   - This notebook provides an introduction to dataclasses in Python. It explains how to use the `@dataclass` decorator to automatically generate special methods like `__init__`, `__repr__`, and `__eq__`. It also covers the use of `ClassVar` for class-level variables.

3. **02_Parameterized_dataclasses.ipynb**:
   - This notebook delves into the parameters of the `@dataclass` decorator, such as `init`, `repr`, `eq`, `order`, `unsafe_hash`, `frozen`, `match_args`, `kw_only`, `slots`, and `weakref_slot`. It explains the purpose of each parameter and how they affect the behavior of the dataclass.

4. **03_Fields_in_dataclasses.ipynb**:
   - This notebook explores the use of fields in dataclasses. It demonstrates how to define fields with default values, use the `field` function for more control over field behavior, and utilize `default_factory` for fields that require a factory function to generate default values.

5. **04_post_init_processing.ipynb**:
   - This notebook covers post-init processing in dataclasses. It explains how to use the `__post_init__` method to perform additional initialization after the `__init__` method has been called. An example is provided to show how to set a field based on the value of another field.

6. **05_inheretance_in_dataclasses.ipynb**:
   - This notebook discusses inheritance in dataclasses. It shows how to create a dataclass that inherits from another dataclass and how to override fields and methods in the subclass. Examples include creating a `Student` class that inherits from a `Person` class and overriding fields in a subclass.

7. **06_asdict_and_astuple.ipynb**:
   - This notebook demonstrates the use of the `asdict` and `astuple` functions to convert dataclass instances to dictionaries and tuples, respectively. Examples are provided to show how these functions can be used to serialize dataclass instances for JSON encoding and other purposes.

By following these notebooks in sequence, you will gain a thorough understanding of how to use dataclasses in Python to create more concise and readable code.
 
 __Step 07 and 08 is for self learning__

 - [Vidoe: 1 hour of Dataclass in depth](https://www.youtube.com/watch?v=2P0i119GXNQ)
 - [Video: 2 Python dataclasses will save you HOURS, also featuring attrs](https://www.youtube.com/watch?v=vBH6GRJ1REM)
 - [Reading: Data Classes in Python 3.7+ (Guide) Realpython.com](https://realpython.com/python-data-classes/)
 - [Reading Python Docs: dataclasses — Data Classes ](https://docs.python.org/3/library/dataclasses.html#module-contents)