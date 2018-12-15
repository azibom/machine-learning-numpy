# machine-learning-numpy
how can you use numpy in python

# Numpy
## NumPy is the fundamental package for scientific computing in Python.

first, you need to import it like this
```python
import numpy as np
```

now you can use it for making array and matrix

```python
a = np.array([[1, 0],[0, 1]])
```

```python
a = np.matrix([[1, 0],[0, 1]])
```

how it is time to know how you can multiple two arrays

### first way
```python
a @ b
```

### second way
```python
np.dot(a,b)
``` 

and you should use it for the matrix in this way
```python
a*b
``` 

# division
you can use "divide" for divide a array into a number 
```python
np.divide([1, 1, 1],5)
``` 



## sqrt
this is code for calculating the five sqrt
```python
np.math.sqrt(5)
``` 

## Generate random numbers
this function makes a random array that you want
```python
np.random.uniform(min, max,(row, columns))
``` 

## you can make your array in another way 
```python
np.arange(start_number, stop_number, step, dtype='float')
# it make sth like it if
# start_number = 1
# stop_number = 14
# step = 3
# array([ 1, 4, 7, 10, 13])
```   
## or
```python
np.arange(start_number, stop_number, count, dtype='float')
# it make sth like it if
# start_number = 1
# stop_number = 10
# step = 4
# array([ 1, 4, 7, 10])
``` 

## you can mask your array like a piece of cake
```python
my_mask = the_array > 2
your_mask_array = the_array[my_mask]
``` 

## some time with two conditions :)
```python
my_mask = np.logical_and(the_array > 1, the_array < 4)
the_array[my_mask]
``` 

I hope this data will be useful to you.








