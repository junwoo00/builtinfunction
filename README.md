# Built in function

### 1.all()

- The function checks whether all iterable objects are True.

### ex)

```

ex_list = [True, True, False, True]
print(all(ex_list))  


ex_tuple = (10, 20, 30, 40)
print(all(ex_tuple)) 


ex = "hello"
print(all(ex))  


ex_list = []
print(all(ex_list))  


```

### 2. any() 
- The function is a function that checks whether one or more elements of an iterable object are True.

### ex ) 
```

ex_list = [False, True, False, False]
print(any(ex_list))  


ex_tuple = (0, 0, 0, 5)
print(any(ex_tuple))  


ex_string = "hello"
print(any(ex_string))  


ex_list = []
print(any(ex_list))  

```

### 3 . enumerate( )
- The function takes an iterable object (list, tuple, string, etc.) as input and returns an enumerate object containing each element and its index.
  
### ex )
```

ex_list = ['apple', 'banana', 'cherry']


for index, value in enumerate(my_list):
    print(index, value)

```

### 4. iter( )
- The function returns an iterator of iterable objects.

### ex )
```
ex_list = [1, 2, 3, 4, 5]


ex_iter = iter(ex_list)


print(next(ex_iter))  # 출력: 1
print(next(ex_iter))  # 출력: 2
print(next(ex_iter))  # 출력: 3

```

### 5. zip( )
- The function receives multiple iterable objects as arguments and creates an iterator that groups the elements of each object and returns them in the form of a tuple.

### ex ) 
```

list1 = [1, 2, 3]
list2 = ['a', 'b', 'c']
list3 = [True, False, True]

zipped = zip(list1, list2, list3)

print(list(zipped))  # 출력: [(1, 'a', True), (2, 'b', False), (3, 'c', True)]


```
