## 1. How to Revers string


```python
text = 'Hello Baby'

ReverseText = ' '
for index in range(1, len(text) + 1):
    reverseText += text[-index]

print(reverseText)

# Output : ybaB olleH
```

```python
text = 'Hello Baby'

lastIndex = len(text) - 1
ReverseText = ' '
for index in range(len(text)):
    reverseText += text[lastIndex - index]

print(reverseText)

# Output : ybaB olleH
```

## 2. Find index of odd

```python
arr = [5, 7, 8, 4, 3]
indexOfOdd = []
for i in range(len(arr)):
    if arr[i] % 2 == 1:
        indexOfOdd.append(i)
print(indexOfOdd)

# Output : [0, 1, 4]
```

## 3. Average of number in list

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

## 4. Loop in Dictionary

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

## 5. How to sum number in array

```python
arr = [5, 7, 8, 4, 3]
sum = 0 
for value in arr:
    sum += value # sum = sum + value

print(sum)

# Output : 27
```

## 6. Find even numbers

```python
arr = [5, 7, 8, 4, 3]

for value in arr:
    if value % 2 == 0:
        print(value)

# Output : 8 4
```

## 8. Find Min numbers

```python
arr = [10, 40, 20, 4, 3]

min = arr[0]
for value in arr:
    if value < min:

print(min)

# Output : 3
```

## 9. Move one step to right

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

## 10. Move on step to left

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

## 11. Find Max numbers

```python
arr = [10, 40, 20, 4, 3]

max = arr[0]
for value in arr:
    if value > max:

print(max)

# Output : 40
```

## 12.How to Sum value in row

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




