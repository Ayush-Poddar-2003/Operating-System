# MEMORY ALLOCATION

![alt text](image-2.png)




## 1. CONTIGUOUS ALLOCATION
### ADDRESS TRANSLATION -
![alt text](image-14.png)
Physical Address(On main memory) = Base Address + Logical Address(Provided by CPU)



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
- Dynamic
- No internal BUT External fragmentation exists
- No effect on degree of multiprogramming

We can remove EF but expensive as we need to shift process  
Here we have - 

First Fit, Next Fit, Best Fit, Worst Fit
![alt text](image-30.png)


## 2. NON CONTIGUOUS ALLOCATION
Spanning is allowed
![alt text](image-31.png)