# Python-Data-Structure-Assignment
Mastering Python Data Structures


1: Introduction
A quick guide to the fundamental data structures in Python, based on the recent assignment.

2: Types of Data Structures
List: Mutable, ordered, allows duplicates.

Tuple: Immutable, ordered, allows duplicates.

Set: Mutable, unordered, no duplicates.

Dictionary: Mutable, unordered, no duplicate keys.

3: Lists in Action
Lists are a versatile way to store collections of items.

Example 1: Basic Operations
languages = ['R', 'Python', 'SAS']
len(languages) -> 3
languages.append('Java') -> ['R', 'Python', 'SAS', 'Java']

Example 2: Slicing
words = ['hello', 'world', 'from', 'python']
words[1] -> 'world'
words[:2] -> ['hello', 'world']

4: Sets in Action
Sets are for unique collections. They're great for finding unique elements, unions, and intersections.

Example 1: Removing Duplicates
grades = ['A', 'A', 'B', 'C']
unique_grades = set(grades) -> {'A', 'B', 'C'}

Example 2: Set Operations
set1 = {'apple', 'banana'}
set2 = {'banana', 'cherry'}
set1.union(set2) -> {'apple', 'banana', 'cherry'}
set1.intersection(set2) -> {'banana'}

5: Tuples in Action
Tuples are similar to lists but are immutable, meaning they cannot be changed after creation.

Example: Creating and Accessing
city_info = ('Bangalore', 28.99, 72)
print(city_info[0]) -> 'Bangalore'

Key Takeaway: You can't modify a tuple, which makes them useful for data that shouldn't change, like coordinates or database records.

6: Dictionaries in Action
Dictionaries are key-value pairs, perfect for storing related information.

Example 1: Basic Operations
person = {'name': 'Alice', 'age': 30}
print(person['name']) -> 'Alice'

Example 2: Adding and Updating
person['city'] = 'New York'
print(person) -> {'name': 'Alice', 'age': 30, 'city': 'New York'}

7: Conclusion & Call to Action
Understanding data structures is crucial for writing efficient and effective code.

What's your favorite Python data structure and why? Share your thoughts in the comments!

#Python #DataStructures #Programming #LinkedIn #Learning
