# Lists
- Write a program that creates an empty list and then asks the user to input integers to add to the list. Print the final list.
- Write a program that creates a list of integers and then asks the user to input an integer to check if it exists in the list. Print a message indicating whether the integer is in the list or not.
- Write a program that creates a list of strings and then sorts the list alphabetically. Print the sorted list.
- Write a program that creates a list of integers and then finds the maximum value in the list. Print the maximum value.
- Write a program that creates two lists of integers and then finds the common elements between those two lists. Print the common elements.
- Write a program that creates a list of strings and then removes all elements that contain a specific substring. Print the final list.
- Write a program that creates a nested list and then accesses a specific element in the list. Print the accessed element.
- Write a program that creates a list of integers and then removes all duplicates from the list. Print the final list.
- Write a program that creates a list of strings and then finds the longest string in the list. Print the longest string.
- Write a program that creates a list of integers and then finds the sum of all the even numbers in the list. Print the sum.
- Write a program that creates a list of integers and then asks the user to input a position to remove an element from the list. Print the final list.
- Write a program that creates a list of strings and then concatenates all the strings into a single string. Print the final string.
- Write a program that creates a list of integers and then finds the median value of the list. Print the median.
- Write a program that creates a list of strings and then reverses the order of the strings in the list. Print the reversed list.
- Write a program that creates a list of integers and then calculates the average of all the numbers in the list. Print the average.
- Write a program that creates a list of integers and then finds the index of a specific element in the list. Print the index.
- Write a program that creates a list of strings and then removes all whitespace characters from each string in the list. Print the final list.
- Write a program that creates a list of integers and then sorts the list in descending order. Print the sorted list.
- Write a program that creates a list of integers and then asks the user to input a value to add to the list. Add the value to the beginning of the list and print the final list.
- Write a program that creates two lists of integers and then concatenates those two lists into a single list. Print the final list.
- Write a program that uses the map function to create a new list that contains the squares of each element in a user inputted list of integers.
- Write a program that uses a lambda expression and the map function to convert a list of integers to a list of strings. Print the new list.
- Write a program that uses a lambda expression and the map function to add 10 to each element in a list of integers. Print the new list.
- Write a program that uses the map function to create a new list that contains the first letter of each string in a user inputted list of strings.
- Write a program that uses a lambda expression and the map function to convert a list of Celsius temperatures to a list of Fahrenheit temperatures. Print the new list.
- Write a program that uses a lambda expression and the map function to convert a list of strings to a list of integers. Print the new list.
- Write a program that uses the map function to create a new list that contains the length of each string in a user inputted list of strings.
- Write a program that uses a lambda expression and the map function to calculate the square root of each element in a list of integers. Print the new list.
- Write a program that uses a lambda expression and the map function to convert a list of integers to their absolute values. Print the new list.
- Write a program that uses the map function to create a new list that contains the uppercase version of each string in a user inputted list of strings.
- Write a program that uses the filter function to create a new list that contains only the even numbers from a user inputted list of integers.
- Write a program that uses a lambda expression and the filter function to create a new list that contains only the strings that start with a vowel from a user inputted list of strings.
- Write a program that uses the filter function to create a new list that contains only the strings with a length greater than 5 from a user inputted list of strings.
- Write a program that uses a lambda expression and the filter function to create a new list that contains only the positive numbers from a user inputted list of integers.
- Write a program that uses the filter function to create a new list that contains only the strings that contain the letter "e" from a user inputted list of strings.
- Write a program that creates a nested list from two user inputted lists of integers. The resulting nested list should contain each element of the first list paired with the corresponding element of the second list.
```
Example input: [1, 2, 3], [4, 5, 6]
Example output: [[1, 4], [2, 5], [3, 6]]
```
- Write a program that creates a nested list of strings from a user inputted list of strings. The resulting nested list should contain each string split into its individual characters.
```
Example input: ['hello', 'world']
Example output: [['h', 'e', 'l', 'l', 'o'], ['w', 'o', 'r', 'l', 'd']]
```
- Write a program that creates a nested list of integers from a user inputted list of integers. The resulting nested list should contain each integer along with its square.
```
Example input: [1, 2, 3, 4, 5]
Example output: [[1, 1], [2, 4], [3, 9], [4, 16], [5, 25]]
```
- Write a program that creates a nested list from a user inputted list of strings. The resulting nested list should contain the unique characters from each string.
```
Example input: ['apple', 'banana', 'cherry']
Example output: [['a', 'p', 'l', 'e'], ['b', 'a', 'n'], ['c', 'h', 'e', 'r', 'y']]
```
- Write a program that creates a nested list of integers from a user inputted list of integers. The resulting nested list should contain each integer along with all of its divisors.
```
Example input: [2, 3, 4, 5]
Example output: [[2, [1, 2]], [3, [1, 3]], [4, [1, 2, 4]], [5, [1, 5]]]
```

---
- You are given a list of integers, nums. Write a function, reverse_list(nums), that takes the list as input and returns a new list that is the reverse of the original list.
**Function signature**
```python
def reverse_list(nums: List[int]) -> List[int]
```
**inputs:**
- A list of integers, nums (1 <= len(nums) <= 1000)
**output:**
- A new list that is the reverse of `nums`

*Example:*
```
Input: nums = [1, 2, 3, 4, 5]
Output: [5, 4, 3, 2, 1]

Input: nums = [7, 6, 5, 4]
Output: [4, 5, 6, 7]
```

*Note:*
You are not allowed to use any built-in Python functions or methods that directly reverse a list. Your function must return a new list that is the reverse of the original list using only standard Python list manipulation techniques. Your function should have a time complexity of O(n) and a space complexity of O(n).

---
