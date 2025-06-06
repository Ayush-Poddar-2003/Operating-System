# MEMORY ALLOCATION

![alt text](image-2.png)




## 1. CONTIGUOUS ALLOCATION
ADDRESS TRANSLATION -
![alt text](image-14.png)


---
### PARTIONING -
#### 1. FIXED SIZE PARTIONING -    
- Fixed no. of partitions, Size may vary
- No spanning (half in one half in other)
- High Memory Wastage ie INTERNAL FRAGMENTATION  
Memory that is internal to a partition but is not being used
![alt text](image-3.png)
- External Fragmentation can exist too, Has space but not contiguos

---
#### 2. VARIABLE SIZE PARTIONING -
- Memory is divided dynamically, exactly according to the process’s size.
- No internal BUT External fragmentation exists
- No effect on degree of multiprogramming

External Fragmentation:
Free memory is scattered in small pieces, not usable by larger processes even if total free memory is enough

---
MEMORY ALLOCATION -  
We can remove EF but expensive as we need to shift process  
Here we have - 

First Fit, Next Fit, Best Fit, Worst Fit
![alt text](image-30.png)

---
### Fragmentation Solutions
1. Compaction:  
Move all allocated memory to one end to merge free spaces (used in variable partitioning).
2. Paging/Segmentation:  
Advanced memory management techniques used in modern systems to avoid fragmentation.