### ACCESS METHODS
| Method            | Description                                             | Example                            |
| ----------------- | ------------------------------------------------------- | ---------------------------------- |
| **Sequential**    | Read/write in order, one record after another           | Reading a text file line by line   |
| **Direct/Random** | Access any record directly using its index              | Accessing a student by roll number |
| **Indexed**       | Uses an index to find blocks faster (like a book index) | Database systems                   |

---
### <CENTER> ALLOCATION METHODS
1. Contiguous  
Stores file blocks in a single continuous chunk  
CONS : External fragmentation
2. Linked  
Each file is a linked list of disk blocks.
Each block contains: File data + A pointer to the next block  
PROS : No External Fragmentation  
CONS : Sequential Access Only
3. Indexed  
Uses a separate index block to store all block addresses.

| Method     | Sequential Access | Random Access | Fragmentation | I/O Performance |
| ---------- | ----------------- | ------------- | ------------- | --------------- |
| Contiguous | Excellent         | Good          | External      | ✅ Very Fast     |
| Linked     | Okay              | Poor          | None          | ❌ Slow Random   |
| Indexed    | Good              | Good          | None          | ✅ Balanced/Good |


---
### FREE SPACE MANAGEMENT
| Method          | Description                           |
| --------------- | ------------------------------------- |
| **Bitmap**      | 0 = free, 1 = used                    |
| **Linked List** | Free blocks linked together           |
| **Grouping**    | Stores free block addresses in groups |
| **Counting**    | Stores start + count of free blocks   |


| Attribute                | Description                                          |
| ------------------------ | ---------------------------------------------------- |
| **Name**                 | The name of the file (human-readable)                |
| **Type**                 | File extension/type (e.g., `.txt`, `.jpg`, `.cpp`)   |
| **Location**             | Pointer to the file’s location on disk               |
| **Size**                 | Current size of the file in bytes                    |
| **Creation Time**        | When the file was created                            |
| **Last Access Time**     | When the file was last read                          |
| **Last Modified Time**   | When the file was last changed                       |
| **Owner/User ID**        | Who owns the file                                    |
| **Permissions**          | Who can read/write/execute the file (Access Control) |
| **Hidden/Archive Flags** | Used for backup, system files, or user preferences   |
