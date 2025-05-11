This repository contains examples of common, and uncommon sorting and search algorithms with video and text references to explain their function and implementation.


## Search Functions 
---

All of these functions take in the following...
1. An array of numbers to search - (Search list)
2. An array of numbers to find in the first list - (Interest list)
3. An array of number occurances to stop search at - (Duplicate limit list)
4. A boolean that makes the function return the list in sorted order - (Return final list) Default=true


The function will return a list of lists, if return final list is true, the first list in the returned list will be the sorted list
each subsequent list will be a list of indexes that the relative number in the interest list was found
if there are values in the duplicate limit list, it will only find the relative number of indexes given from their value in the same index of the interest list

Example -

Search list - [ 5, 4, 7, 8, 2, 2, 8, 9, 110, 56 ]
Interest list - [ 2 ]
Duplicate list - [ ] or none given
Return final list - none given

linearsearch(search list, interest list, duplicate list, return final list)

returns

[ [ 2, 2, 4, 5, 7, 8, 8, 9, 56, 110 ], [ 4, 5 ] ]




### Implemented
---



### TODO
---
