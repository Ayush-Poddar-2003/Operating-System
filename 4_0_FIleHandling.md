# ACCESS METHODS
| Method            | Description                                             | Example                            |
| ----------------- | ------------------------------------------------------- | ---------------------------------- |
| **Sequential**    | Read/write in order, one record after another           | Reading a text file line by line   |
| **Direct/Random** | Access any record directly using its index              | Accessing a student by roll number |
| **Indexed**       | Uses an index to find blocks faster (like a book index) | Database systems                   |


# ALLOCATION METHODS
1. Contiguous
2. Linked
3. Indexed

# FREE SPACE MANAGEMENT
| Method          | Description                           |
| --------------- | ------------------------------------- |
| **Bitmap**      | 0 = free, 1 = used                    |
| **Linked List** | Free blocks linked together           |
| **Grouping**    | Stores free block addresses in groups |
| **Counting**    | Stores start + count of free blocks   |
