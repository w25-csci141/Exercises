# Lecture 20 - Searching and Sorting 

### Exercises: 
#### 1. For the following program, answer the questions:
   ```python
   def linear_search(lst, target):
      for i in range(len(lst)):
          if lst[i] == target:
              return i  
      return -1 

   names = ["Alice", "Bob", "Charlie", "David"]
   print(linear_search(names, "Charlie"))  
   print(linear_search(names, "Eve"))  
   
   ```
 ##### 1.1. What does the program print?
 ##### 1.2. Modify the function to return all occurrences of the target in the list.
 ##### 1.3. On top of 1.2, allow the function to search for partial matches (e.g., "ar" should match "Charlie").

#### 2. For the following program, answer the questions:
   ```python
   def find_substring(text, keyword):
      if keyword in text:
          return text.index(keyword)
      return -1

   sentence = "Python programming is fun!"
   print(find_substring(sentence, "programming"))  
   print(find_substring(sentence, "Java"))  

   ```
 ##### 2.1. What does the program print?
 ##### 2.2. Modify the function to count how many times the keyword appears in the text.
 ##### 2.3. On top of 2.2, make the function handle case-insensitive searches. 

#### 3. For the following program, answer the questions:
   grades = {"Alice": 85, "Bob": 92, "Charlie": 78, "David": 90}
   ```python
   def find_grade(student_name):
       return grades.get(student_name, "Student not found")

   print(find_grade("Charlie")) 
   print(find_grade("Eve")) 

   ```
 ##### 3.1. What does the program print?
 ##### 3.2. Modify the function to set the grade to 0 for students whose names are not found .

 
 #### 4. For the following program, answer the questions:
   ```python
   names = ["Zara", "Alice", "Charlie", "Bob"]
   sorted_names = sorted(names) 
   print(sorted_names) 

   ```
 ##### 4.1. What does the program print?
 ##### 4.2  Modify the function to sort in reverse alphabetical order.
 
 #### 5. For the following program, answer the questions:
  
  ```python
   def bubble_sort(numbers):
       n = len(numbers)
       for i in range(n - 1):
           for j in range(n - 1 - i):
               if numbers[j] > numbers[j + 1]:
                   numbers[j], numbers[j + 1] = numbers[j + 1], numbers[j]  
       return numbers

   nums = [5, 3, 8, 1, 2]
   print(bubble_sort(nums))
   ```
 ##### 5.1. What does the program print?
 ##### 5.2  Modify the sorting to display highest number first.

 
