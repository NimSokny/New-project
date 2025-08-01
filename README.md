### 1. How to Revers string

```
text = 'Hello Baby'

ReverseText = ' '
for index in range(1, len(text) + 1):
    reverseText += text[-index]

print(reverseText)

# Output = ybaB olleH
```

```
text = 'Hello Baby'

lastIndex = len(text) - 1
ReverseText = ' '
for index in range(len(text)):
    reverseText += text[lastIndex - index]

print(reverseText)

# Output = ybaB olleH
```

## 2. Find index of odd

```
arr = [5, 7, 8, 4, 3]
indexOfOdd = []
for i in range(len(arr)):
    if arr[i] % 2 == 1:
        indexOfOdd.append(i)
print(indexOfOdd)

# Output = [0, 1, 4]
```

## 3. Average of number in list

```
arr = [5, 7, 8, 4, 3]
average = 0 
sum = 0
for value in arr:
    sum += value # sum = sum + value






