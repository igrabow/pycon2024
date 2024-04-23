Solving Problems

use fewer resources, make it lighter, get more users, makue users happy

-> Optimisation


Refactoring, profiling, architecture changem design patterns, parallel programming, caching, DB optiization
CODE CHANGING


How python executes code

CODE -> Compiler -> cpython Bytecode -> Interpreter execution

dis module


import dis

def my_function(a, b):
    return a+b

dis.dis(my_function)

2   0 LOAD_FAST 0 (a)
    2 LOAD_FAST 1 (b)
    4 BINARY_ADD
    6 RETURN_VALUE


