## Lets stand in the Baby Pool...

%[https://www.youtube.com/watch?v=tPrzsr5dtBg]

## Variables

Variable is a container that holds data for accessing and changing in the later part of the program.

**Example:**
```
var = 10 # Assigning a Value
.
.
var = 12 # Changing a Value
```
---

## Constants:

Constants are the value that does not change during the execution of the code. Once the value is assigned, then it cant be changed. In python, we does not have a separate feature for declaring a constant but there is a naming convention. Whenever you declare a variable in all uppercase letters, then it is said to be a constant and it should not be changed.

**Example:**
```
PI = 3.14285 # Should not changed in later part of the program
```

> **Note:** Variables and Constants should not follow the [Rules of Identifiers](htttps://blog.saranmaahdev.tech/py2)

---

## Datatypes:

- **Text Type**:	str

Example:
```
s = "Hello Maestro!" # String
```

- **Numeric Types**:	int, float, complex

Example:
```
x = 50 # Integer
y = 195.12 # Float 
z = 24j # Complex
```

- **Sequence Types**:	list, tuple, range

Example:
```
a = ["Elon Musk", "warren Buffett", "Steve Jobs"] # List
b = ("Jeff Bezos", "Bill Gates", "Ratan Tata") # Tuple
c = range(10) # Range
```

- **Mapping Type**:	dict

Example:
```
d = { "name" : "Cloud Maestro", "author": "Saran Mahadev"} # Dictionary
```

- **Set Types**:	set, frozenset

Example:
```
s = {"abc", "def", "ghi"} # Set
fs = frozenset( {"abc", "def", "ghi"}) # Frozen Set
```

- **Boolean Type**:	bool

Example:
```
# bool
t = true
f = false
```

- **Binary Types**:	bytes, bytearray, memoryview

Example:
```
b = b'name' # Bytes
ba = bytearray(5) # Bytearray
mv = memoryview(bytes(5)) # Memoryview
```

---

# Type Conversion

The  process of converting from one datatype to another datatype is called as **Type Conversion**. There are types of Conversion.

-> Implicit Conversion
In this conversion, Python converts the datatype by itself.

**Example:**

```
a = 10  # int
b = 23.2 # float
print(a+b) 

# 'a' is converted to float automatically and prints 33.2

```
-> Explicit Conversion

In this conversion, user converts the datatype to another and performs the operation.

Example:
```
a = 10 # int
b = "20" # str
print( a + int(b)) 

#  Prints 30

```
>**Note:** Zen of Python states that "**Unless explicitly silenced.**", so always prefer explicit conversion in your code.

---

## Python Input and Output:
- **input()** gets input from the user

Example:
```
a = input("Enter Whatever you like!")
```
- **print()** prints output to the user

Example:
```
print(a) # Whatever in 'a' is shown 
```
---

## Operators:
Operators are nothing but special symbols that are used to perform arithmetic and logical operations.

Operators in grouped as:
- Arithmetic operators,
- Assignment operators,
- Comparison operators,
- Logical operators,
- Identity operators,
- Membership operators and
- Bitwise operators.

---

Conclusion:
Make sure to checkout the next blog for learning more.

Wanna Support!





