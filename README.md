Aim:

To study and implement basic Python list operations using built-in functions and methods such as max() and append().

Theory:

Python provides a built-in data structure called a list, which is used to store multiple elements in a single variable. Lists are ordered, mutable, and allow duplicate values. The elements of a list can be accessed using their index positions, starting from zero.

1. List Creation

A list is created by placing elements inside square brackets [], separated by commas. Lists can store elements of the same or different data types. Since lists are mutable, their contents can be modified after creation.

Example concept:
numbers = [10, 20, 30, 40]

2. max() Function

The max() function is a built-in Python function used to find the largest element in an iterable such as a list or tuple. It compares all elements in the list and returns the maximum value.

Important points:

All elements must be comparable (generally of the same data type).

It improves efficiency by avoiding manual comparison using loops.

Syntax:
max(list_name)

3. append() Method

The append() method is used to add a single element to the end of an existing list. This method modifies the original list and does not return a new list.

Important points:

Only one element can be added at a time.

The element can be of any data type.

Syntax:
list_name.append(element)

4. Traversing a List

Traversing a list means accessing each element of the list one by one, usually using a loop. This operation is useful for displaying elements or performing calculations on each item.

Commonly used loop:
for loop

5. Displaying List Elements

List elements can be displayed directly using the print() function or by printing each element individually during traversal. This helps in verifying the contents of the list after operations like appending or modification

Algorithm 1: Finding the Maximum Element in a List

1.Start

2.Create a list containing numeric elements

3.Apply the built-in max() function on the list

4.Store the maximum value returned by the function in a variable

5.Display the maximum element

6.Stop

Algorithm 2: Appending an Element to a List

1.Start

2.Create a list with initial elements

3.Input the element to be added

4.Use the append() method to add the element at the end of the list

5.Display the updated list

6.Stop

Algorithm 3: Displaying Elements of a List

1.Start

2.Create a list with elements

3.Traverse the list using a loop

4.Display each element one by one

5.Stop

Algorithm 4: Combined List Operations

1.Start

2.Create a list with numeric elements

3.Find the maximum element using max() and display it

4.Append a new element to the list using append()

5.Display the final updated list

6.Stop

Conclusion

The list operations such as creation of a list, finding the maximum element using max(), adding elements using append(), and traversing the list form the foundation of data handling in Python. These operations make programs concise, efficient, and easy to understand.
