# Code Snippets :computer:

A compilation of code snippets

# Python :snake:
> Simple Web server
```bash
$ python -m http.server
```
> Run Bash commands in python code
```python
bashCmd = ["cd", ".."]
process = subprocess. Popen(bashCmd, stdout=subprocess. PIPE)
output, error = process.communicate()
```
> Create an Virtual Enviroment(MacOS and Unix)
```bash
$ python3 -m venv virtual-env
$ source virtual-env/bin/activate
```
> Palindrome
```python
word.find(word[::-1])
```
> Reverse a string
```python
word[::-1]
```



## IPython
>Embed an IPython shell in your code for easy debugging
```python
import IPython; IPython.embed(); exit(1)
```

>Write LaTeX with IPython
```python
from IPython.display import Math, display
display(Math('\\text{Keplers Third Law: }R_3 = \\frac{G(M_1 + M_2)}{4\\pi^2}T^2'))
```

## List Comprehensions
>Basic
```python
new_list = [x*x for x in nums]
```
>w/ Conditional
```python
new_list = [x*x for x in nums if x % 2 == 0]
```
>Nested 
```python
[i*j for i in range(100) for j in range(10)]
```

>Map vs List Comprehension
```python
def multiply(i):
    return i * 2
#map
doubled_list = map(multiply, numbers)
list(doubled_list)

# List Comprehension
doubled_list = [multiply(i) for i in nums]
```

> Dictionary Comprehension
```python
hundred_dict = {i:i*100 for i in range(10)}
```





# Math
> Math constants
```python
import math
#pi
math.pi # 3.141592653589793
#Euler's number
math.e # 2.718281828459045
#tau
math.tau # 6.283185307179586

```

# Bit Hacks
>Given a list of pairs return the only single value
```python
import operator
from functools import reduce

def singleNumber(self, nums):
        return reduce(operator.xor, nums)
```
> Multiply a number by 2
```python
>>> 5 << 1
```
> Divide a number by 2
```python
>>> 8 >> 1
```


# Contributions
- All contributions are welcome
















