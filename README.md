## Find All Duplicates
Write a function (in python) or method (in Java) that accepts a list of integers and returns a list of only those integers that appear more than once.

## Describe Different Approaches to solving this problem
Q: Describe the two different ways to figure out all of the duplicate values of a list of integers in english. The first solution is the nested loop solution. The second solution is to use a dictionary or a map (similar to the containsPair method we wrote in class. Describe both in as much detail as you can (with no code) and describe the trade-offs between the two solutions.

A: The nested loop solution uses two pointers (i, j). i goes through the list once  and j scans the whole list for each i value to find matches. if a duplicate is found then it is added to the duplicates list. if the duplicate is already on the list, adding it to the list operation is ignored.

With the dictionary solution, we use a hashmap to store our the values we go over with one pointer (i). if the hashmap already has the value stored then we can conclude that we have found a duplicate.
