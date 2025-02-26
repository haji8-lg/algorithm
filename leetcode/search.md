# Python

## String 
* "str".replace('s','S')
* string to list = list(str)
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

## Map/Object


## List

## Stack
    ```
    stack = []
    stack.append(10)
    top = stack.pop()
    top = stack[-1]
    is_empty = len(stack) == 0
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
