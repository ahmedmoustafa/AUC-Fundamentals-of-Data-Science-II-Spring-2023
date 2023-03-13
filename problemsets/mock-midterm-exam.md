# Mock Midterm Exam

## Multiple Choice Questions:

1. What is the output of the following code?

```python
x = "Data"
y = "Science"
print(x + y)
```

a) Data

b) Science

c) Data Science

d) None of the above

2. Which of the following is NOT a valid variable name in Python?

a) `data_science`

b) `123_data_science`

c) `_data_science`

d) `dataScience`

3. What does the following code print?

```python
x = [1, 2, 3, 4]
print(x[1:3])
```

a) `[1, 2]`

b) `[2, 3]`

c) `[3, 4]`

d) `[2, 3, 4]`

4. Which of the following is a valid way to define a dictionary in Python?

a) `{1: 'one', 2: 'two'}`

b) `{1, 'one', 2, 'two'}`

c) `(1: 'one', 2: 'two')`

d) `[1: 'one', 2: 'two']`


5. What does the following code print?

```python
x = [1, 2, 3, 4]
for i in x:
    print(i)
```

a) `1 2 3 4`

b) `[1, 2, 3, 4]`

c) `1234`

d) None of the above

6. What is the output of the following code?

```python
x = 5
while x > 0:
    print(x)
    x -= 1
```

a) `1 2 3 4 5`

b) `5 4 3 2 1`

c) `5`

d) None of the above

7. What is the output of the following code?

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

x = factorial(5)
print(x)
```

a) `5`

b) `10`

c) `15`

d) `120`


8. What does the following code print?

```python
x = "Hello, World!"
print(x.split(","))
```

a) `"Hello, World!"`

b) `["Hello", " World!"]`

c) `["Hello,", " World!"]`

d) None of the above

9. What is the output of the following code?

```python
x = [1, 2, 3]
y = [4, 5, 6]
z = x + y
print(z)
```

a) `[1, 2, 3, 4, 5, 6]`

b) `[[1, 2, 3], [4, 5, 6]]`

c) `[(1, 4), (2, 5), (3, 6)]`

d) None of the above

10. What is the output of the following code?

```python
x = {"a": 1, "b": 2, "c": 3}
y = x.pop("b")
print(x)
print(y)
```

a) `{"a": 1, "c": 3}, 2`

b) `{"a": 1, "b": 2, "c": 3}, 2`

c) `{"a": 1, "c": 3}, {"b": 2}`

d) None of the above

## Coding Questions:

1. Write a Python function called "even_numbers" that takes a list of integers as input and returns a list of only the even numbers in the input list. Example input: `[1, 2, 3, 4, 5, 6]`, Example output: `[2, 4, 6]`

2. Write a *recursive* Python function called `fibonacci` that takes an integer n as input and returns the nth number in the Fibonacci sequence. The first two numbers in the Fibonacci sequence are 0 and 1, and each subsequent number is the sum of the two previous numbers. Example input: 6, Example output: 8