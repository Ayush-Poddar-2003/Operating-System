# <center> ACCESS METHOD

## 1. SEQUENTIAL
Info inside the file is processed in order.  
One record after other  
Usually compilers/IDEs uses this  

OPERATIONS - 
1. READ NEXT : Reads and moves pointer to next position.
2. WRITE NEXT : ''
3. REWIND : Moving back to earlier position
4. SKIP : To skip records

## 2. DIRECT / RANDOM / RELATIVE
Based on Disk Model, as disk allows random access to any file block  
No restrictions on the order of reading/writing

File Operations must include block number as parameter

1. Read n
2. Write n
3. Jump to record n
4. Query current record


## 3. INDEXED ACCESSED SEQUENTIAL
Index is created which contains a key field and pointer to various blocks