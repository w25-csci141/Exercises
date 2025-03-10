# Practice Problems for the Final Exam

## Section 1: Mark each statement as True (T) or False (F), and explain your answers briefly (15 points)

1. In Python, `while True:` creates an infinite loop.
2. The `import random` statement loads all functions from the random module into the global namespace. 
3. A function in Python must always return a value explicitly using the return statement.
4. A function can return multiple values using tuple unpacking.
5. A tuple can contain both mutable and immutable objects.
6. Strings in Python are immutable, meaning they cannot be changed after they are created.
7. The `append()` method in a list creates a new list instead of modifying the original one.
8. A dictionary key must always be an integer.
9. The statement file = open(filename, "r") automatically closes the file once the block finishes execution.
10. In Python, variables store actual values rather than references to objects.

## Section 2: Multiple Choice: Circle the correct answer.(10 points)
1. What is the output of the following code?
 ```python
 a = [1, 2, 3]
 b = a
 b.append(4)
 print(a)

 ```
  a) `[1, 2, 3]`  
  b) `[1, 2, 3, 4]`  
  c) `Error`  
  d) `[4, 2, 3, 1]`
  
2. Which of the following best describes the difference between a list and a tuple?

a) Lists are immutable, and tuples are mutable.  
b) Lists use parentheses `()` while tuples use square brackets `[]`.  
c) Lists are mutable, and tuples are immutable.  
d) Lists must contain the same data type, whereas tuples can have mixed data types.

3. What is the output of the following Python expression?
 ```python
print(2 ** 3 == 8 and 5 > 2)
```
 a) `True`  
 b) `False`  
 c) `None` 
 d) `Error`

4. What does the following statement do?
 ```python
 random.randint(1, 10)
 ```
 a) Returns a random float between 1 and 10.  
 b) Returns a random integer between 1 and 10, inclusive.  
 c) Raises an error because `randint` is not a valid function.  
 d) Returns a random even number between 1 and 10.  


5. How do you correctly open a file called `data.txt` for writing only?
   
 a) `open("data.txt", "w")`  
 b) `open("data.txt")`  
 c) `open("data.txt", "w+")`  
 d) `open("data.txt", "write")`  

## Section 3: Code Reading.(30 points)
1. What is the output of the following Python code?

 ```python

 s = "hello"
 s_list = list(s)  
 s_list[0] = "H"   
 s = "".join(s_list)  
 print(s) 

 ```

2. Below is a Python program demonstrating different ways to copy a list. Explain the differences of method 1 to 5:
```python
original_list = [1, 2, 3, 4, 5]

# Method 1
copy1 = original_list
print(copy1)

# Method 2
copy2 = []
for item in original_list:
    copy2.append(item)
print(copy2)

# Method 3
copy3 = original_list[:]
print(copy3)

# Method 4
copy4 = list(original_list)
print(copy4)

# Modify the original list
original_list[0] = 99

print("Original list:", original_list)
print("Copy1", copy1)
print("Copy2", copy2)
print("Copy3", copy3)
print("Copy4", copy4) 
 ```

3. E19-2
4. E20


 






