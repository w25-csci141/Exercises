# Lecture 19 - Exercises

### 19A - Mutable Objects and Functions

I recommend drawing the memory diagram as you execute each of the following programs.

1. What does the following program print?

   ```python
   def z0(y):
       y[0] = 4
       return y
   
   b = [5, 6]
   c = z0(b)
   print(b[0], c[0])
   ```

2. What does the following program print?

   ```python
   def z4(d1, d2):
       a = d1
       d1 = {}
       d1 = d2
       d1["A"] = 2
       return a
       
   a = {"A": 4, "B": 6}
   b = {"A": 6, "B": 11}
   f = z4(a, b)
   print(a["A"], b["A"], f["A"])
   ```



