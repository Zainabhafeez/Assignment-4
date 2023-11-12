### Assignment-04 (List)
- Change the notebook name with your name and Roll Number.
- Try this as your own, no chatgpt (it's for your learning)
- after completing the assignment, submit this book on google class room.

Create an empty list and print it.



```python
empty_list= list()
print(empty_list)
```

    []
    

Create a list of your favorite colors and print it.



```python
colors = ["black" , "mustard" , "navy blue" , "red" , "voilet"]
print(colors)

```

    ['black', 'mustard', 'navy blue', 'red', 'voilet']
    

Create a list that includes a mix of data types (integers, strings, floats).



```python
data = [16.09 , "python" , 6 , "programming"]
print(data)
```

    [16.09, 'python', 6, 'programming']
    

Access the first element of a list.



```python
list=[2,4,6,8,10]
first_element = list[0]
print(first_element)
```

    2
    

Access the last element of a list.


```python
list=[2,4,6,8,10]
last_element = list[-1]
print(last_element)
```

    10
    

 Access the second and third elements of a list.



```python
list=[2,4,6,8,10]
element = list[1:3]
print(element)
```

    [4, 6]
    


Slice a list to extract the first three elements.



```python
list=[2,4,6,8,10]
element = list[:3]
print(element)
```

    [2, 4, 6]
    

Slice a list to extract the last three elements.



```python
list=[2,4,6,8,10]
element = list[-3:]
print(element)
```

    [6, 8, 10]
    

Slice a list to get every second element.



```python
list=[2,4,6,8,10]
element = list[::2]
print(element)
```

    [2, 6, 10]
    

Reverse a list using slicing.


```python
list=[2,4,6,8,10]
reverse = list[::-1]
print(reverse)
```

    [10, 8, 6, 4, 2]
    

 Create two lists and concatenate them.



```python
list_1 = [1,2,3,4,5]
list_2 = [6,7,8,9,10]
concatenate = (list_1 + list_2)
print(concatenate)
```

    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    


Repeat a list multiple times using the repetition operator


```python
list_1 = [1,2,3,4,5]
repeat = list_1 * 3
print(repeat)
```

    [1, 2, 3, 4, 5, 1, 2, 3, 4, 5, 1, 2, 3, 4, 5]
    

Add a new element to the end of a list using the append() method.



```python
list_1 = [1,2,3,4,5]
new_element = 6
list_1.append(new_element)
print(list_1)
```

    [1, 2, 3, 4, 5, 6]
    


Extend a list with elements from another list using the extend() method.



```python
list_1 = [1,2,3,4,5]
list_2 = [6,7,8,9,10]
list_1.extend(list_2)
print(list_1)
```

    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    

Insert an element at a specific index in a list using the insert() method.


```python
list = [1,2,3,5]
insert = 4
index = 3
list.insert(index, insert)
print(list)
```

    [1, 2, 3, 4, 5]
    

 Remove the last element from a list using the pop() method.




```python
list = [1,2,3,5]
removed_element = list.pop()
print("Updated List:", list)
print("Removed Element:", removed_element)
```

    Updated List: [1, 2, 3]
    Removed Element: 5
    

Remove a specific element from a list using the remove() method.



```python
list = [1,2,3,5]
remove_element = 3
list.remove(remove_element)
print("Updated List:", list)
```

    Updated List: [1, 2, 5]
    

Clear all elements from a list.



```python
list = [1,2,3,4,5]
clear_list = list.clear()
print("new List:", list)
```

    new List: []
    

Delete an element at a specific index using the del statement.


```python
list = [1,2,3,4,5]
index = 3
del list[index]
print("Updated List:", list)
```

    Updated List: [1, 2, 3, 5]
    

Convert a string to a list of characters and vice-versa.


```python
string = "Easy Python"
list_of_character = [char for char in string]
print(list_of_character)
```

    ['E', 'a', 's', 'y', ' ', 'P', 'y', 't', 'h', 'o', 'n']
    


```python
list_of_character= ['E', 'a', 's', 'y', ' ', 'P', 'y', 't', 'h', 'o', 'n']
new_string = ''.join(list_of_character)
print("New String:", f'"{new_string}"')
```

    New String: "Easy Python"
    


```python
Sort a list in ascending order using the sort() method.

```


      Cell In[29], line 1
        Sort a list in ascending order using the sort() method.
             ^
    SyntaxError: invalid syntax
    



```python
list = [5,4,3,2,1]
sorted_list = sorted(list)
print("Original List:", list)
print("Sorted List (Ascending):", sorted_list)
```

    Original List: [5, 4, 3, 2, 1]
    Sorted List (Ascending): [1, 2, 3, 4, 5]
    


```python

Sort a list in descending order using the sort() method.

```


```python
list = [10,13,9,6,14]
sorted_list = sorted(list, reverse=True)
print("Original List:", list)
print("Sorted List (Descending):", sorted_list)
```

    Original List: [10, 13, 9, 6, 14]
    Sorted List (Descending): [14, 13, 10, 9, 6]
    

Reverse the order of a list using the reverse() method.



```python
list = [1,2,3,4,5]
reversed = list.reverse()
print(list)
```

    [5, 4, 3, 2, 1]
    

Check if an element is present in a list using the in operator.



```python
list = [1,2,3,4,5]
element_to_check = 4
if element_to_check in list:
    print(f"{element_to_check} is present in the list.")
else:
    print(f"{element_to_check} is not present in the list.")
```

    4 is present in the list.
    

Compare two lists to see if they are equal in both value and identity.


### Condition1


```python
list1 = [1, 2, 3, 4, 5]
list2 = [1, 2, 3, 4, 5]
if list1 == list2:
    print("The lists are equal in value.")
else:
    print("The lists are not equal in value.")
```

    The lists are equal in value.
    

### Condition 2


```python
list1 = [1, 2, 3, 4, 5]
list2 = [1, 2, 3, 4, 5]
list1 = list2
if list1 is list2:
    print("The lists are identical.")
else:
    print("The lists are not identical.")
    
```

    The lists are identical.
    

Create a shallow copy of a list and modify one of the lists to observe the effects on the other.



```python
original = [2,4,6,8,10]
shallow = original[:]
original[2] = 13
print("Original:", original)
print("Shallow Copy:", shallow)
```

    Original: [2, 4, 13, 8, 10]
    Shallow Copy: [2, 4, 6, 8, 10]
    

Create a deep copy of a nested list and modify one of the lists to observe the effects on the other.


```python
import copy
nested_list = [[2, 3], [4, 5]]
deep_copy = copy.deepcopy(nested_list)
nested_list[0] [0]= 16
print("Nested List:", nested_list)
print("Deep Copy:", deep_copy)
```

    Nested List: [[16, 3], [4, 5]]
    Deep Copy: [[2, 3], [4, 5]]
    

Pickle and Unpickle a list and display its content.


```python
import pickle
my_list = [2,4,6,8,10]
with open('my_list.pkl', 'wb') as file:
    pickle.dump(my_list, file)
with open('my_list.pkl', 'rb') as file:
    unpickled_list = pickle.load(file)
print("Original List:", my_list)
print("Unpickled List:", unpickled_list)
```

    Original List: [2, 4, 6, 8, 10]
    Unpickled List: [2, 4, 6, 8, 10]
    
