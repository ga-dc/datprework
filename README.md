### Python Self-Assessment: Questions

This assessment covers many of the most common elements of Python you'll need early on in the course, but is not comprehensive. Don't study exclusively to these fifteen questions, but rather start with one of the resources above and aim to really _understand_ these fundamentals.

1. How do you create an empty list named "mylist"?
2. What will the following code return? `5 > 3 or 5 < 3`
3. What will be stored in the "nums" object? `nums = range(10)`
4. How do you check the type and the length of the "nums" object?
5. How do you return the last number in the "nums" object?
6. Slice the "nums" object to return a list with the numbers 2, 3, 4.
7. What is the difference between `nums.append(10)` and `nums + [10]`?
8. How do you divide 3 by 2 and get a result of 1.5?
9. Import the "math" module, and then use its "sqrt" function to calculate the square root of 1089.
10. What type of object is created by this code? `d = {'a':10, 'b':20, 'c':30}`
11. In the "d" object, what are "a", "b", and "c" called? What are 10, 20, and 30 called?
12. How do you return the 10 from the "d" object?
13. How do you change the 30 to a 40 in the "d" object?
14. From the "people" object, return Brandon's state only: `people = {'Alice': ['Washington', 'DC'], 'Brandon': ['Arlington', 'VA']}`
15. Define a function "calc" that takes two variables, "a" and "b", and returns their sum.


### Python Self-Assessment: Answers
Use this answer-key to evaluate your responses to the Python Self-Assessment. Next to most answers is a hint in square brackets `[]` that will point you in the right direction to understand the answer. In other words, if you're not sure why an answer is correct, try Googling those keywords!

1. `mylist = []` or `mylist = list()` [lists]
2. True [boolean operators and comparisons]
3. A list of the integers 0 through 9 [built-in functions and range()]
4. `type(nums)` and `len(nums)` [built-in functions, type(), and list()]
5. `nums[9]` or `nums[-1]` [lists]
6. `nums[2:5]` [lists and slices]
7. `nums.append(10)` modifies the original list, whereas `nums + [10]` does not actually modify the list.
8. In Python 3: `3/2`. In Python 2: `3/float(2)` or `3/2.0`.
9. `import math` and then `math.sqrt(1089)`. Alternatively, `from math import sqrt` and then `sqrt(1089)`. [modules]
10. A dictionary [dictionaries and objects]
11. "a", "b", and "c" are the keys, and 10, 20, and 30 are the values. [dictionaries and objects]
12. `d['a']` [accessing values in objects]
13. `d['c'] = 40` [modifying values in objects]
14. `people['Brandon'][1]` [accessing values in objects]
15. `def calc(a, b): return a + b` (usually written as two separate lines) [creating functions]
