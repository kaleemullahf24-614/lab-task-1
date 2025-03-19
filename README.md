# lab-task-3
# EXCRISE NO 1:
my_list = [10, "hello", 3.14, True]

# Access elements using indexing & slicing
print(my_list[0])  # First element
print(my_list[-1])  # Last element
print(my_list[1:3])  # Slicing

# Modify list elements
my_list[1] = "world"
print(my_list)

# OUTPUT:
10
True
['hello', 3.14]
[10, 'world', 3.14, True]
# EXCRISE NO 2:
list1 = [1, 2, 3]
list2 = [4, 5, 6]
combined = list1 + list2
print(combined)
1.
# Repeat elements:
repeated = list1 * 3
print(repeated)
2.
# Check membership:
print(2 in list1) # True
print(7 not in list2) # True
# OUTPUT:
[1, 2, 3, 4, 5, 6]
[1, 2, 3, 1, 2, 3, 1, 2, 3]
True
True

