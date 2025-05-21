# Python

## String 
* "str".replace('s','S')     //  original_string.replace(substring_to_remove, "", 1) # once
* string to list = list(str)
* list to string = str(list)
* Contains
  ```
  if "blah" not in somestring: 
    continue
  ```
* "str".find('s', index)
* str.count() : 특정 문자의 반복 횟수
* "Hello world!".replace("world", "universe", count)
* int(str)
* 2진수 리스트로 변환
    ```
    binary_list = [bin(number)[2:] for number in numbers]
    ['1', '10', '11', '100', '101']
    ```
* zero fill
  ```
  '12344'.zfill(10)
    0000012344
  ```
* 숫자의 자릿수 찾기
    ```
    import math

    n = -10
    if n > 0:
        digits = int(math.log10(n)) + 1
    elif n == 0:
        digits = 1
    elif n < 0:
        digits = int(math.log10(-n)) + 2
    print(digits)

    n = -100.90
    digits = len(str(n))
    print(digits)
    ```
## For
* python list for index
```
for i, color in enumerate(colors, start=0):
```
* reversed
```
for i in reversed(range(1,10)
for i in range(9,0,-1)
for i list(range(1,10))[::-1]
```
## Map/Object/Dict 
* Dictionary : get(), keys(), values(), items() 

## List
* list init 초기화
```
a = [38, 21, 53, 62, 19]
two_d_list = [[0 for _ in range(10)] for _ in range(5)]
```
*  found = list.index('melon')
*  list.remove("JavaScript")
*  list.sort()
*  sum(list)
*  list_b = sorted(list_a)
*  list add on position
```
l1 = [1,2,3]
l1.insert(1,100)
l1 => [1, 100, 2, 3 ]
```
* list delete on position
```
del list[0]
```
## Stack
    ```
    stack = []
    stack.append(10)
    top = stack.pop()
    top = stack[-1]
    is_empty = len(stack) == 0
    ```
## Tuple 
* tuple Object
```
point = (3, 5)
points_dict = {point: "This is the point"}
```
* tuple return 
```
def select_choice():
    ...
    return i, card  # or [i, card]

my_i, my_card = select_choice()
```
## Typeof
```
console.log(typeof x); object
```

## Exception
```
raise Exception("에러에러에러!!")
```
## python list param call by reference
```
print('before, outer_list =', outer_list)
try_to_change_list_contents(outer_list)
print('after, outer_list =', outer_list)
```


## ETC
* object.copy()
* deepcopy
  ```
  import copy
  copy.deepcopy(obj)
  ```
* len () function
* 제곱근 3 ** 2 = 9
* While
```
while True:
    print("무한루프")
```
