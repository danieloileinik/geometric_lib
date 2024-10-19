
# How to use calculator:
1. Run `python calculate.py`
2. Enter the figure name. Available are Circle, Square.
3. Enter the function: Area or Perimeter.
4. Enter figure sizes. Radius for circle, one side for square.
5. Get the answer!

# Math formulas
## Area
- Circle: `S = πR²`
- Rectangle: `S = ab`
- Square: `S = a²`
- Triangle: `S = sqrt(p * (p-a) * (p-b) * (p-c))` where p is semiperimeter

## Perimeter
- Circle: `P = 2πR`
- Rectangle: `P = 2a + 2b`
- Square: `P = 4a`
- Triangle: `P = a + b + c`

# How to use calculator:
1. Run `python calculate.py`
2. Enter the figure name. Available are Circle, Square.
3. Enter the function: Area or Perimeter.
4. Enter figure sizes. Radius for circle, one side for square.
5. Get the answer!

# Math formulas
## Area
- Circle: `S = πR²`
- Rectangle: `S = ab`
- Square: `S = a²`
- Triangle: `S = sqrt(p * (p-a) * (p-b) * (p-c))` where p is semiperimeter

## Perimeter
- Circle: `P = 2πR`
- Rectangle: `P = 2a + 2b`
- Square: `P = 4a`
- Triangle: `P = a + b + c`
# Общее описание решения

Этот проект предназначен для расчета различных геометрических фигур. Он решает проблему вычисления площади, периметра и других характеристик фигур, таких как треугольники и круги. Основные функции включают:

- Расчет площади и периметра  круга
- Расчет площади и периметра квадрата

# Описание функций

## Функция 1: `def area(r)`:

**Описание**: Эта функция рассчитывает площадь круга.

**Содержание функции**:
```python
import math
def area(r):
    return math.pi * r * r
```

            
                        
## Функция 2: `def perimeter(r)`:

**Описание**: Эта функция рассчитывает периметр круга.

**Содержание функции**:
```python
import math
def perimeter(r):
    return 2 * math.pi * r
```
        
## Функция 3: `def area(r)`:

**Описание**: Эта функция рассчитывает площадь квадрата.

**Содержание функци**:
```python
def area(a):
    return a * a
```
        
## Функция 4: `def perimeter(r)`:

**Описание**: Эта функция рассчитывает периметр квадрата.

**Содержание функци**:
```python
def perimeter(a):
    return 4*a
```
## Функция 5: `def area(a, b, c)`:

**Описание**: Эта функция рассчитывает площадь треугольника.

**Содержание функци**:
```python
def area(a, b, c):
    return (a + b + c) / 2
```
       
## Функция 6: `def perimeter(a, b, c)`:

**Описание**: Эта функция рассчитывает периметр треугольника.

**Содержание функци**:
```python
def perimeter(a, b, c):
    return a + b + c
```
     

