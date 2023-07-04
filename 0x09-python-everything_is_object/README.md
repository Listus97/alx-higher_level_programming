0x09. Python - Everything is object

0. Who am I?
function to get the type of an object in the file, without ().

1. Where are you?
variable identifier (which is the memory address in the CPython implementation) in the file, without ().

2. Right count
a and b do not point to the same object

3. Right count =
a and b point to the same object

4. Right count =
a and b point to the same object

5. Right count =+
a and b do not point to the same object

6. Is equal
What these 3 lines print

>>> s1 = "Best School"
>>> s2 = s1
>>> print(s1 == s2)

7. Is the same
What these 3 lines print

>>> s1 = "Best"
>>> s2 = s1
>>> print(s1 is s2)

8. Is really equal
What these 3 lines print

>>> s1 = "Best School"
>>> s2 = "Best School"
>>> print(s1 == s2)

9. Is really the same
What these 3 lines print

>>> s1 = "Best School"
>>> s2 = "Best School"
>>> print(s1 is s2)

10. And with a list, is it equal
What these 3 lines print

>>> l1 = [1, 2, 3]
>>> l2 = [1, 2, 3] 
>>> print(l1 == l2)

11. And with a list, is it the same
Whatthese 3 lines print

>>> l1 = [1, 2, 3]
>>> l2 = [1, 2, 3] 
>>> print(l1 is l2)

12. And with a list, is it really equal
What these 3 lines print

>>> l1 = [1, 2, 3]
>>> l2 = l1
>>> print(l1 == l2)

13. And with a list, is it really the same
What these 3 lines print

>>> l1 = [1, 2, 3]
>>> l2 = l1
>>> print(l1 is l2)

14. List append
What this script prints

l1 = [1, 2, 3]
l2 = l1
l1.append(4)
print(l2)

15. List add
What  this script prints

l1 = [1, 2, 3]
l2 = l1
l1 = l1 + [4]
print(l2)

16. Integer incrementation
What this script prints

def increment(n):
    n += 1

a = 1
increment(a)
print(a)

17. List incrementation
What this script prints

def increment(n):
    n.append(4)

l = [1, 2, 3]
increment(l)
print(l)

18. List assignation
What this script prints

def assign_value(n, v):
    n = v

l1 = [1, 2, 3]
l2 = [4, 5, 6]
assign_value(l1, l2)
print(l1)

19. Copy a list object
a function def copy_list(l): that returns a copy of a list.

20. Tuple or not?
a is a tuple

21. Tuple or not?
a is a tuple

22. Tuple or not?
a is not a tuple

23. Tuple or not?
a is not a tuple

24. Who I am?
What this script prints

a = (1)
b = (1)
a is b

25. Tuple or not
What this script prints

a = (1, 2)
b = (1, 2)
a is b

26. Empty is not empty
What this script prints

a = ()
b = ()
a is b

27. Still the same?
 the last line of this script prints 139926795932424

28. Same or not?
the last line of this script does not print 139926795932424

29. #pythonic
function magic_string() that returns a string “BestSchool” n times the number of the iteration (see code):

30. Low memory cost
class LockedClass with no class or object attribute, that prevents the user from dynamically creating new instance attributes, except if the new instance attribute is called first_name.
