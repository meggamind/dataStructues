# dataStructures

# Hash Tables

(Design a system for storing employee records keyed using phone numbers)

### Arrays and linked lists 
- We need to search in a linear fashion.
- If we keep the arrays sorted and keep data sorted, then a phone number can be searched
in O(log n ) time using Binary Serch
- Insert and delete operations become costly as sorted order has to be maintained.

### Direct access table
- Make a big array ans use phone numbers as index in the array.
- Time complexity wise this is the best options
- All operations can be done in O(1) time.
- Problem is with the extra space required is huge, e.g n digits, we need O(m*10^n) space for table where
  m is size of a pointer to record,
- Another problem is an integer in a programming langugage may not store n digits.

# Hashing
- Hashing is an improvement over Direct Acess Table.
- Idea is to use hash function that converts a given phone mnumber or any other key to a smaller number and
uses the small number as index in a table called hash table
