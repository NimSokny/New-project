## Exercise : 1

How to Revers string. Example : Hello = olleH

### Code

```python
text = 'Hello Baby'

ReverseText = ' '
for index in range(1, len(text) + 1):
    reverseText += text[-index]

print(reverseText)

# Output : ybaB olleH
```

### Code

```python
text = 'Hello Baby'

lastIndex = len(text) - 1
ReverseText = ' '
for index in range(len(text)):
    reverseText += text[lastIndex - index]

print(reverseText)

# Output : ybaB olleH
```

## Exercise : 2

### Code

Find index of odd. Example : [5, 7, 8, 4, 3] = [0, 1, 4 ]

```python
arr = [5, 7, 8, 4, 3]
indexOfOdd = []
for i in range(len(arr)):
    if arr[i] % 2 == 1:
        indexOfOdd.append(i)
print(indexOfOdd)

# Output : [0, 1, 4]
```

## Exercise : 3

### Code

Average of number in list. Example : [5, 7, 8, 4, 3] = 5.4  we take total of number / total of index.

### Code

```python
arr = [5, 7, 8, 4, 3]
average = 0 
sum = 0
for value in arr:
    sum += value # sum = sum + value
average = sum / len(arr)

print(average)

# Output : 5.4
```

## Exercise : 4

### Code

Loop in Dictionary. Example : 

### Code

```python
arr = [
    {'name': 'bopha', 'age': 18},
    {'name': 'thida', 'age': 18},
    {'name': 'kanha', 'age': 18}
]

for dics in arr:
    print(dics['name'])

# Output : # bopha
           # thida
           # kanha
```

## Exercise : 5

### Code

How to sum number in array. Example : [5, 7, 8, 4, 3] = 27

```python
arr = [5, 7, 8, 4, 3]
sum = 0 
for value in arr:
    sum += value # sum = sum + value

print(sum)

# Output : 27
```

## Exercise : 6

### Code

Find even numbers. Example :

```python
arr = [5, 7, 8, 4, 3]

for value in arr:
    if value % 2 == 0:
        print(value)

# Output : 8 4
```

## Exercise : 7

### Code

Find Min numbers. Example :

```python
arr = [10, 40, 20, 4, 3]

min = arr[0]
for value in arr:
    if value < min:

print(min)

# Output : 3
```

## Exercise : 8

### Code

Move one step to right

```python
arr = [0, 0, 1, 0, 0]
isFound = False
for i in range(len(arr) - 1):
    if arr[i] == 1 and not isFound:
        arr[i] = 0
        arr[i + 1] = 1
        isFound = True
print(arr)

# Output : [0, 0, 0, 1, 0]
```

## Exercise : 9

### Code

Move on step to left

```python
arr = [0, 0, 1, 0, 0]
isFound = False
for i in range(len(arr) - 1):
    if arr[i] == 1 and not isFound:
        arr[i] = 0
        arr[i - 1] = 1
        isFound = True
print(arr)

# Output : [0, 1, 0, 0, 0]
```

## Exercise : 10

### Code

Find Max numbers

```python
arr = [10, 40, 20, 4, 3]

max = arr[0]
for value in arr:
    if value > max:

print(max)

# Output : 40
```

## Exercise : 11

### Code

How to Sum value in row

```python
arr2D = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
sum = 0
arr = []
for row in range(len(arr2D)):
    for col in range(len(arr2D[row])):
        sum += arr2D[row][col]
    arr.append(sum)
    sum = 0

print(arr)

# Output : [12, 15, 18]
```




